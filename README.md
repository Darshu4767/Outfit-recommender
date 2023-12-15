# Outfit-recommender

An outfit recommendation system which uses color and pattern to recommend top for bottoms and bottom for tops. A cnn model has been trained to detect patterns and kmeans clustering is used to find colour of clothing items. creat_dataset.py is used to extract the dataset for training the cnn model.

Next a compatibility matrix is created to match color and pattern of tops to that of bottoms , and for this FashionVC dataset is used. The compatibility matrix is updated based on user's feedback.
