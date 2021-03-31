# Cryptocurrencies
- The purpose of this analysis was to apply unsupervised machine learning to analyze a database of cryptocurrencies. Refer to [crypto_clustering.ipynb](../main/crypto_clustering.ipynb)

## Challenge
- Perform the analysis from [crypto_data.csv](../main//Resources/crypto_data.csv) for the following four technical analysis deliverables:
- Preprocessing the Data for PCA (Deliverable 1):
  ![alt text](../main/Deliverable1.png) 

- Reducing Data Dimensions Using PCA (Deliverable 2):
   ![alt text](../main/Deliverable2.png) 

- Clustering Cryptocurrencies Using K-means (Deliverable 3):
  - The best k value appears to be 4:                                       
   ![alt text](../main/Deliverable3_Elbow.png) 
  - Cluster DataFrame:
   ![alt text](../main/Deliverable3_KMeans.png) 

- Visualizing Cryptocurrencies Results (Deliverable 4):
  - 3D-Scatter plot:
   ![alt text](../main/Deliverable4_3Dplot.png) 
  - Tradable Cryptocurrencies Table:
   ![alt text](../main/Deliverable4_table.png) 
  - hvplot scatter plot:
   ![alt text](../main/Deliverable4_hvplot.png) 
   
 ## Results
 - Using unsupervised machine learning, we can decide whether or not a crypto currency is tradable.
 - The total number of tradable cryptocurrencies is 532 based on similarities of their features.
   
