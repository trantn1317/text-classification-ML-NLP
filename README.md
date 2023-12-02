# Meta-Learning with DistilBERT for Sentiment Analysis on Amazon Health & Self-Care Product Reviews

## Project Overview

This project employs meta-learning through the Reptile algorithm to enhance a DistilBERT model for sentiment analysis specifically tailored to Amazon product reviews within the health and self-care product category. The XML data undergoes loading, preprocessing, and meticulous cleaning procedures to ensure the creation of well-formed XML. The reviews are then extracted and transformed into a Pandas DataFrame for further analysis.

## Data Loading and Preprocessing

The XML data originating from Amazon health and self-care product reviews undergoes loading, escaping, and meticulous cleaning procedures to ensure the creation of well-formed XML. The reviews are then extracted and transformed into a Pandas DataFrame for further analysis.

## Rating Distribution Visualization

To provide a comprehensive understanding of the product ratings in the health and self-care category, a countplot visualization is generated to illustrate the distribution of these ratings.

## Review Activity Over Time Visualization

A histogram is employed to visually represent the distribution of reviews over time, shedding light on the temporal dynamics of product reviews within the health and self-care category.

## Helpfulness Ratio Distribution Visualization

An additional histogram is utilized to visually convey the distribution of the helpfulness ratio associated with reviews, offering insights into the perceived value of reviews in this specific product category.

## Sentiment Analysis

The DistilBERT model is employed in the training process of a sentiment analysis model, enhancing its ability to discern sentiments within Amazon health and self-care product reviews.

## Meta-Learning with Reptile

The application of the Reptile algorithm to train the DistilBERT model involves strategically managing batches and perturbing model parameters towards the current batch, contributing to the meta-learning process.

## Model Evaluation

The meta-trained model undergoes a rigorous evaluation on a dedicated test set comprising reviews. Evaluation metrics include accuracy, a comprehensive classification report, and a confusion matrix, providing a nuanced understanding of the model's performance.

### Model Performance

The meta-trained model achieves an approximate accuracy of 89% after one meta-epoch, showcasing its efficacy in sentiment analysis for reviews.

## Conclusion

This project exemplifies the application of meta-learning through the Reptile algorithm to fine-tune a DistilBERT model, specifically tailored for sentiment analysis on Amazon health and self-care product reviews. The included visualizations serve to enrich the insights into the distribution of ratings, review activity over time, and the helpfulness ratio of reviews within this particular product category.

