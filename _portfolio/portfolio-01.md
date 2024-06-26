---
title: "Comparative Analysis of the Performance of Deep Learning Models in Identifying Sarcasm in News Titles"
excerpt: "<img src='https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSCO7rrr-2vFfGBwy6SkvB_16nY8ijWT-S_APCSCy5i9g&s'>"
collection: portfolio
---

![Sarkas](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSCO7rrr-2vFfGBwy6SkvB_16nY8ijWT-S_APCSCy5i9g&s)

### Introduction
This project is conducted as part of the course "Unstructured Data Analysis". In today's digital landscape, the proliferation of satirical content presents unique challenges for natural language understanding and sentiment analysis. Distinguishing between genuine news headlines and sarcastic ones is crucial for discerning accurate information and preventing the spread of misinformation. To address this, we leverage a dataset comprising news headline titles collected from two distinct sources: The Onion and HuffPost. The Onion is renowned for producing satirical news content, while HuffPost offers genuine news headlines. This dataset presents an invaluable resource for training and evaluating models to detect sarcasm in news headlines. By employing advanced classification techniques, specifically deep learning models such as Recurrent Neural Networks (RNNs), Long Short-Term Memory (LSTM) networks, Gated Recurrent Units (GRUs), and Convolutional Neural Networks (CNNs), we aim to develop robust algorithms capable of accurately identifying sarcastic headlines amidst a sea of genuine news titles.

### Methods
The analysis methodology revolves around employing deep learning techniques for classification tasks tailored to unstructured text data. The dataset of news headlines will be preprocessed to tokenize and vectorize the textual content, facilitating input into the deep learning models. Various deep learning architectures, including RNNs, LSTMs, GRUs, and CNNs, will be implemented to learn intricate patterns and contextual nuances present in the headline texts.

Initially, the dataset will be divided into training, validation, and testing sets to ensure model performance generalizes well to unseen data. The deep learning models will undergo training on the training set, where the model parameters are iteratively adjusted to minimize the classification error. Hyperparameter tuning may be performed to optimize model performance and prevent overfitting.

Following training, the models will be evaluated on the validation set to assess their effectiveness in distinguishing between sarcastic and genuine news headlines. Metrics such as accuracy, precision, recall, and $$F1$$-score will be calculated to quantify the model's performance. Additionally, the best-performing model(s) will undergo further evaluation on the test set to validate their robustness and real-world applicability.

Through this rigorous approach, we aim to develop state-of-the-art classification models capable of accurately detecting sarcasm in news headlines, thereby enhancing our ability to navigate and interpret information in today's digital media landscape.

### Uploaded File Description
- `Sarcasm_Headlines_Dataset.json`: Raw dataset containing information about sarcasm news.
- `UTS Analisis Data Tidak Terstruktur_Diki Wahyudi_2106709131.ipynb`: Python script for performing on the sarcasm news dataset.
- `UTS Analisis Data Tidak Terstruktur_Diki Wahyudi_2106709131.pdf`: Comprehensive report summarizing the findings and conclusions of classification analysis.

### GitHub Repository
The code and file for this project can be found [here](https://github.com/dikiwahyudi11/Sarcasm-News-Detection). 
