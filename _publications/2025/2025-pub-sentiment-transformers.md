---
title:          "Exploring Transformer-based Approaches in Sentiment Prediction of Philippine Tweets"
date:           2025-06-26 12:00:00 +0800
selected:       false
pub:            "DLSU Research Congress 2025"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
# pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
pub_date:       "2025"

abstract: >-
  Sentiment analysis is a valuable tool for understanding public opinions and trends, particularly given the rapid growth of social media in the Philippines. However, several challenges must be addressed to further advancements in this field. Previous research in Philippine sentiment analysis has largely depended on traditional machine-learning approaches and manual annotation processes, resulting in smaller, less representative datasets. This study explores an emoji-based automatic annotation combined with transformer models to enhance sentiment analysis in Philippine social media. The Multidimensional Lexicon of Emojis (MLE) by Godard and Holtzman (2022) is used to leverage the sentiment scores of emojis. We used two private tweet collections from X (formerly Twitter), comprising over 17 million tweets. After data preprocessing, we labeled sentiment using MLE sentiment scores, with human annotators verifying a sample of 2,754 tweets. Spearman’s rank correlation was used between MLE scores and human-annotated sentiment scores, obtaining a correlation of 0.4747 for positive and 0.6181 for negative sentiment, indicating a moderate to strong agreement. The study assessed various BERT-based transformer models, including mBERT, Tagalog-BERT, RoBERTa-Tagalog, and TwHIN-BERT, through single-output and multi-output regression configurations for sentiment analysis. The models' performance was evaluated using RMSE and R2 metrics. The results reveal that TwHIN-BERT scored 0.1596 RMSE and 0.3018 R2 for both single and multi-output configurations, outperforming other models, with RoBERTa-Tagalog consistently placing second in both configurations.

# cover:          /assets/images/covers/cover3.jpg
authors:
  - Marcus Calalang
  - Miguel Estañol
  - Jon Jacinto
  - Mauries Lopez
  - Eric Denver Co
  - John Matthew Gan
  - Jose Noel Noblefranca
  - Jason Jan Jabanes
  - Edward Tighe*#
---

