---
title: "Unmasking Misinformation: A Data Mining Approach to Hoax Detection and Topic Modeling"
excerpt: "<img src='https://assets-a1.kompasiana.com/items/album/2020/10/21/hoax-5f900f978f179733c710fac2.jpg'>"
collection: portfolio
---

![Hoax](https://assets-a1.kompasiana.com/items/album/2020/10/21/hoax-5f900f978f179733c710fac2.jpg)

### Introduction
This project is conducted as part of the course "Data Mining and Business Intelligence". In the age of digital information, combating misinformation and identifying hoaxes are paramount for maintaining the integrity of online discourse and safeguarding societal trust. With the proliferation of social media platforms, the dissemination of false information has become increasingly pervasive, necessitating robust analytical approaches to discern fact from fiction. In this project, we leverage a dataset obtained legally from Mafindo, a reputable fact-checking organization in Indonesia, containing labeled data on hoax posts. Each post is labeled as either "0" for non-hoax or "1" for hoax, enabling supervised learning approaches for classification. Additionally, the dataset encompasses textual content that lends itself to topic modeling techniques, offering insights into the thematic trends and narratives surrounding hoaxes. Through a combination of classification and topic modeling methodologies, this study aims to enhance our understanding of hoax dissemination patterns and develop predictive models for identifying and mitigating the spread of misinformation.

### Methods
The methodology comprises two primary analytical approaches: classification and topic modeling. For classification, supervised learning algorithms such as logistic regression, decision trees, random forests, or support vector machines will be employed to train predictive models on the labeled dataset. Features extracted from the textual content of the posts, such as word frequencies, $n$-grams, or word embeddings, will serve as inputs to the classification algorithms. The performance of the models will be evaluated using metrics such as accuracy, precision, recall, and $F1$-score to assess their effectiveness in distinguishing between hoax and non-hoax posts.

In parallel, topic modeling techniques, such as Latent Dirichlet Allocation (LDA) or Non-negative Matrix Factorization (NMF), will be applied to uncover latent themes and topics within the dataset. By analyzing the distribution of words across topics and examining the coherence of topic clusters, we aim to identify prevalent narratives and discourses associated with hoax posts. The results of topic modeling will complement the classification analysis, providing deeper insights into the underlying motivations and patterns driving the dissemination of misinformation.

Through the integration of classification and topic modeling methodologies, this study seeks to provide actionable intelligence for detecting and understanding hoaxes, empowering stakeholders with tools to combat misinformation and foster a more informed and trustworthy online environment.

### Credit to Team Members
This project was a collaborative effort, and credit goes to the entire team for their contributions to data collection, analysis, and interpretation.

### Uploaded File Description
- `Case Study 2 DMDBI_Kelompok A.ipynb`: Python script for performing classification and topic modeling on the hoax posts dataset.

### GitHub Repository
The code and file for this project can be found [here](https://github.com/dikiwahyudi11/Hoax-Detection-and-Topic-Modeling). 
