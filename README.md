# Amazon-alexa-reviews-sentiment-analysis
This dataset consists of a nearly 3000 Amazon customer reviews (input text), star ratings, date of review, variant and feedback of various amazon Alexa products like Alexa Echo, Echo dots, Alexa Firesticks etc. for learning how to train Machine for sentiment analysis.
• Performed data cleaning activity by removing the rows containing null and garbage values.
• Built visualizations on the cleaned data to get thorough insights.
• Performed pre-processing steps like removing html tags, digits, URL’s. The words were decontracted. The stop words were removed, and Lemmatization was performed.
• The model was built with 2 embedding layers, 1 LSTM layer and 1 dense layer. Adam optimizer was used.
• The model is trained with the training data using batch size as 64 and 4 epochs.
• When applied on testing set, model achieved an accuracy of 93% and F1-score of 0.97
