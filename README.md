# Analyzing_food_views_and_Recommending_Customers_Wanted_Restaurants
We use Python to scrape over 500,000 customer reviews from restaurant review websites such as Google and EZtable. Later we use 2 NLP models to analyze the views. The first model is BERT and we re-train it to re-evaluate each restaurant based on user reviews. The second model is Jieba and we use it to create labels of high relevance for each searching.

#Website
https://honestreview.herokuapp.com/

<img src="https://github.com/greglll/Analyzing_food_views_and_Recommending_Customers_Wanted_Restaurants/blob/master/heatmap_test_y_3X3_0922.png" width="50%" height="50%" merge="20%">
fig1. After re-training BERT model by three labels(positive, neutral, and negative), we use BERT to test the validation dataset. Result shows high accuracy on the positive and negative labels. But there are uncertain when validating neutral labels. The total accuracy is 68.36%.

![image](https://github.com/greglll/Analyzing_food_views_and_Recommending_Customers_Wanted_Restaurants/blob/master/heatmap_test_y_2X2_0922.png)
fig2. After re-training another BERT model by two labels(positive and negative),we use BERT to test the validation dataset. Result shows high accuracy on the positive and negative labels. The total accuracy is 83.30%.
