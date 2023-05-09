# Bitcoin-price-forecasting-using-twitter-sentiment

Looking for an exciting project that showcases advanced techniques in deep learning and data preprocessing? Our team took on the challenge of predicting Bitcoin prices using social media sentiment analysis, and the results were nothing short of remarkable!

Our project involved collecting over 107,000 tweets per minute interval from January to September 2020, and then preprocessing them using advanced techniques like Vader sentiment analysis and keyword extraction. We stored the data in a MySQL database and used tools like Spark, PySpark, Pandas, Numpy, and multiprocessing to preprocess it based on keywords.

To prepare the data for modeling, we resampled it at 8-hour intervals and converted it into a supervised dataset, using features like opening and closing prices, user follower count, user friend count, and sentiment score. We then used deep learning techniques like Recurrent neural networks (RNN) and Long short term memory (LSTM) to predict future prices based on past data.

Our analysis led us to discover a clear correlation between Bitcoin prices and social media sentiment. Negative sentiment led to a fall in prices, while positive sentiment induced by Twitter influencers with huge followings led to a rise in prices. We visualized these patterns using state-of-the-art tools like PowerBI, resulting in captivating and insightful graphics.

To differentiate between the models in terms of their performance, we used metrics like root mean squared error (RMSE) and Adjusted R square (R2). LSTM outperformed RNN with an R2 value of 0.65 compared to 0.35 for RNN. We also used Monte Carlo dropout to improvise the phenomenon of exploding gradient in LSTM.

The final output of our model demonstrated the effectiveness of our approach, with the predicted prices shown to be fairly accurate despite the noise. Our project demonstrates the potential of social media sentiment analysis in predicting cryptocurrency prices, and highlights the power of deep learning and advanced techniques in data preprocessing and modeling.

Overall, our project showcases our team's proficiency in advanced data preprocessing and modeling techniques, as well as our ability to leverage cutting-edge technology to gain valuable insights and make informed decisions.
