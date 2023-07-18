# IMBD_Review_Classify

The overall approach in the provided code includes multiple phases of a typical text classification tasks.

1. loading and preprocessing the data- IMBD reviews are read from text files and then preprocessed using various techniques such as stemming, removing special characters, and eliminating stopwords.

2. feature extraction- cleaned text data is converted into a numeric form using two techniques - Bag of Words (BOW) and Term Frequency-Inverse Document Frequency (TF-IDF).
   
3. Split data.

4. Model training and evaluation- two different types of models are trained - Logistic Regression and a deep learning model using a Keras Sequential model with an LSTM layer. The Logistic Regression model is trained and evaluated on both BOW and TF-IDF data, while the deep learning model utilizes tokenization, sequencing, and padding before being trained and evaluated.

5. Model evaluation and comparison. 
