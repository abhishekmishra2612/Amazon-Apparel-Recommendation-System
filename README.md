# Amazon-Apparel-Recommendation-System

### This is a simple Apparel Recommendation system which used Amazon women tops data to recommends some tops/shirts for a query top/shirt.

### Source of dataset is https://www.kaggle.com/ajaysh/women-apparel-recommendation-engine-amazoncom
This dataset contains informations for women tops only, This is the real world data from Amazon.com

This recommendation system is built using some features('Title of product', 'Type of product', 'Brand of product', 'Color of Product', 'Price of product', 'Image of product') of the products.
Title of the product is very important feature because it is short text but it is very informative.
Since users don't want to being recommended identical items of item that he/she searched for, hence we removed all the possible duplicate items from the dataset.
### The main objective of this system is to recommends some relevant items of query item.
### This is low letency problem
### This system recommends some relevant items based of similarity between items.
### Similarity is computed using Euclidean distance between items(Vector representation of items), less distance implies more similarity(more revelant).

## Some of the recommended items for a query item/tops/shirt are:
Here the Heatmap represents interpretability of the output, each cell shows the euclidean distance between words.
![Screenshot (247)](https://user-images.githubusercontent.com/41646536/89728892-42213c00-da4e-11ea-8c5f-bcda6902af79.png)
![Screenshot (248)](https://user-images.githubusercontent.com/41646536/89728928-94faf380-da4e-11ea-836b-6671d2f2d674.png)
![Screenshot (249)](https://user-images.githubusercontent.com/41646536/89728936-9fb58880-da4e-11ea-8443-63fb26ebc326.png)

