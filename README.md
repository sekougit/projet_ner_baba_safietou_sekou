# projet named entity of recognition (NER)
Mise en place d'un modèle pour la reconnaissance d'entité normée: les données sont issues de la plateforme kaggle:https://www.kaggle.com/datasets/debasisdotcom/name-entity-recognition-ner-dataset.

Pour réaliser ce projet, on a principalement utilisé deux bibliothéques que sont : spacy et transformers

Le dossier application contient le script python de l'appplication developpé avec streamlit et un fichier texte contenant les dependances

Le dossier data contient les données de base au format csv ainsi que les données train, test et validation obtenu avec les deux bibliothéques

Le fichier code contient un code pour le modéle ner entrainéavec sapcy et un autre code pour le modéle ner entrainé avec transformers

application/

    |--app-ner.py
    
    |--requirements.txt
    
data/

    |--Ner_dataset.csv
    
    |--data_spacy/
    
              |--train.spacy
              
              |--test.spacy
              
              |-valid.spacy
              
    |--data_transformers/
    
              |--train_transformer/
              
                  |--data-00000-of-00001.arrow
                  
                  |--dataset_info.json
                  
                  |--state.json
                  
              |--valid_transformer/
              
                  |--data-00000-of-00001.arrow
                  
                  |--dataset_info.json
                  
                  |--state.json
                  
code/

    |--code_final_transformers.ipynb
    
    |--code_final_spacy.ipynb

