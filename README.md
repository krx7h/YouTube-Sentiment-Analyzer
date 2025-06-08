By sharing a YouTube link, the tool performs the following tasks:



- Extracts the video transcript

- Categorizes each line as positive, negative, or neutral through a Logistic Regression model

- Assesses the model's accuracy

- Illustrates an overall sentiment distribution through a bar graph



The machine learning model was custom-trained using labeled text data. The project utilized:

- pytubefix for transcript extraction

- scikit-learn for TF-IDF vectorization and Logistic Regression

- matplotlib for visualization
