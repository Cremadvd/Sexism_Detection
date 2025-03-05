# Sexism Detection
The project aims at confronting two Deep Learning architectures towards sentiment analysis with the objective of finding the best way to detect sexist sentiments or arguments inside tweets. 

Inside the notebook, we show a comparison between two fully implemented LSTMs and one fine-tuned transformer network, based on [Twitter-roberta-base-hate](https://huggingface.co/cardiffnlp/twitter-roberta-base-hate).

The project was developed as part of the Natural Language Processing course, part of the Artificial Intelligence Master's Degree, at the University of Bologna. 
The backbone structure of the project was provided by Dr. Eleonora Mancini, under the guidance of Prof. Paolo Torroni, the course supervisor. The project itself is based on the [EXIST 2023 Task 1](https://clef2023.clef-initiative.eu/index.php?page=Pages/labs.html#EXIST)

A short report detailing the main achievements of the project is provided; for more info on the code and other design choices, we reference the full interactive Python notebook.
## Dataset
The dataset is a [smaller version](https://github.com/nlp-unibo/nlp-course-material/tree/main/2024-2025/Assignment%201/data) of the one provided by the original task. It contains tweets in English and Spanish; for each tweet, a list of annotators is provided in order to be used for different sexism detection tasks and provide insight on the tweet itself.

## Authors
- Davide Cremonini
- Fabio Giordana

## Technologies
![Python](https://img.shields.io/badge/Python-3.x-blue)
![Tensorflow](https://img.shields.io/badge/Keras-FF0000?style=for-the-badge&logo=keras&logoColor=white)
![Keras](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white)
![HuggingFace](https://img.shields.io/badge/-HuggingFace-FDEE21?style=for-the-badge&logo=HuggingFace&logoColor=black)
