# animal-description-classifier
A text classifier that maps sentences to animals.

# Overview
A fine-tuned BERT model to classify text in 10 classes of animals. The animal classes are the same from the classes in the [Animal-10](https://www.kaggle.com/datasets/alessiocorrado99/animals10/data) dataset. They are: dog, cat, horse, spyder, butterfly, chicken, sheep, cow, squirrel, elephant. The model receives a phrase about those animals and outputs a probability distribution above the classes.

# Model
The classes were trained using chat-gpt simple phrases about the animals ([animal_descriptions.txt](https://github.com/JoaoP-Silva/animal-description-classifier/blob/main/data/animal_descriptions.txt)). The network was fine tuned using the HugginFace transformers API and Pytorch. The model code is in [model.ipynb](https://github.com/JoaoP-Silva/animal-description-classifier/blob/main/model.ipynb).
