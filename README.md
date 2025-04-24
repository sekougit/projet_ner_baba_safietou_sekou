# projet_ner_baba_safietou_sekou
Mise en place d'un modèle pour la reconnaissance d'entité normée: les données sont issues de la plateforme kaggle:https://www.kaggle.com/datasets/debasisdotcom/name-entity-recognition-ner-dataset.

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

