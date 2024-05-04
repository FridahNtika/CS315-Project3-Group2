# CS315-Project3-Group2
Investigating Content Engagement on  TikTok among Wellesley College Students
Overview
This repository contains code and data for a research project aimed at analyzing content preferences and trends among Wellesley College students on the popular social media platform TikTok. Leveraging post metadata and analytical methods such as Jacard_Index, K clustering,Topic Modeling, and TF_ IDF the study provides insights into the content consumption habits of Wellesley students on TikTok.
 Table of Contents

- [Introduction](introduction)
- [Literature Review](literature-review)
- [Data](data)
- [Methods](methods)
- [Results](results)
- [Data Analysis](data-analysis)

  
Introduction
In recent years, social media platforms like TikTok have become integral parts of daily life, particularly among younger demographics. Understanding what type of content students engage with on TikTok sheds light on their interests and preferences, providing valuable insights for content creators, marketers, and researchers. This study focuses specifically on Wellesley College students to uncover their content consumption patterns and preferences.


Methods
 
Results

Data Analysis

To analyze the results of our research on whether Wellesley students view similar content on TikTok, we utilized these methods:

1. Topic Modeling with LDA:
   - We performed topic modeling to understand the spread of TikTok content. Our approach involved converting the data into a document-term matrix to obtain keywords in each document. We then applied the Latent Dirichlet Allocation (LDA) model, which grouped words into topics. We set the number of topics to 5 based on the optimal number of components obtained through GridSearch with cross-validation. The resulting topics were interpreted to understand common themes in the TikTok content consumed by Wellesley students.
2. KMeans Clustering on Embeddings:
   - KMeans clustering was employed to group similar hashtags extracted from the TikTok data. This unsupervised machine-learning algorithm partitioned data into clusters based on similarity. We utilized scikit-learn's implementation of KMeans and determined the number of clusters (`k=5`) based on the elbowMethod(). By examining the hashtags within each cluster, we gained insights into common themes or topics represented in the TikTok content.
   
3:Jaccard Index

4:Tf_IDF


