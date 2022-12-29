# Wish.com Product Rating Prediction 
Machine learning model  classifies the rating of any product based on its features.

We have a dataset from an e-commerce website, each row in the data describes some features for a product and its rating in the website.

Our goal is to make a machine learning model that is able to classify the rating of any new product based on its features.

the input features we have for each product:

      'price', 'retail_price', 'currency_buyer', 'units_sold',
       'uses_ad_boosts', 'rating_count', 'badges_count',
       'badge_local_product', 'badge_product_quality', 'badge_fast_shipping',
       'tags', 'product_color', 'product_variation_size_id',
       'product_variation_inventory', 'shipping_option_name',
       'shipping_option_price', 'shipping_is_express', 'countries_shipped_to',
       'inventory_total', 'has_urgency_banner', 'urgency_text',
       'origin_country', 'merchant_title', 'merchant_name',
       'merchant_info_subtitle', 'merchant_rating_count', 'merchant_rating',
       'merchant_id', 'merchant_has_profile_picture',
       'merchant_profile_picture', 'theme', 'crawl_month', 'id' 

the target variable is 'rating'.

We'll use classification technique to help solve this problem.

The experimental protocol is trying Decision Tree with random hyperparameter values then find the best values using GridSearch, applying the same thing with random forest, SVM and finally applying Naive Bayes

The preprocessing will be explained in steps as we investigate the dataset. The challenge is that the dataset is extremely unclean and need alot of preprocessing

There won't be a huge or critical effect on real life for this project as it is only predicting the rating of a product to be sold.


It is always expected to get better results when using GridSearchCV
