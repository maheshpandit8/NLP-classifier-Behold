# NLP-classifier-Behold
Automatic brand classifier built for behold.com

A common problem for Behold is the extremely manual classification of new products into their specific brands. Behold has supplier relationships from many global clothing vendors and marketplaces, but has found that the bottleneck for scaling out the number of products they can sell is identifying the brands associated with each new product. In this project I use the brands’ biographical description (behold_brands.csv), product descriptions (products.csv) and any externally collected metadata, to build an NLP classification model to predict which brand a new product should be assigned.

We are given brands for each product in the products.csv file, along with a variety of metadata fields, including:
  - Name: the name of the product
  - Details: details about the product that the supplier has elected to provide 
  - Description: generally a natural language text field that contains a description of the product, materials used in its construction, and recommended pairings


#### The data is first pre-processed in the file "Data_Preprocessing.ipynb". The NLP model for classification is built in the file "Classification_RNN_LSTM.ipynb"
