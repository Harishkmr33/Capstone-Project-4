# Capstone-Project-4
![62847850327 (1)](https://github.com/Harishkmr33/Capstone-Project-4/assets/122456211/59b55a7e-23fe-46d2-a085-cc4cb696bd35)

Zomato is an Indian restaurant aggregator and food delivery start-up founded by Deepinder Goyal and Pankaj Chaddah in 2008. Zomato provides information, menus and user-reviews of restaurants, and also has food delivery options from partner restaurants in select cities. India is quite famous for its diverse multi cuisine available in a large number of restaurants and hotel resorts, which is reminiscent of unity in diversity. Restaurant business in India is always evolving. More Indians are warming up to the idea of eating restaurant food whether by dining outside or getting food delivered. The growing number of restaurants in every state of India has been a motivation to inspect the data to get some insights, interesting facts and figures about the Indian food industry in each city. So, this project focuses on analyzing the Zomato restaurant data for each city in India.


### Project Overview

* This project focuses on analyzing the Zomato restaurant data for Hyderabad city in 
India to gain insights and provide useful conclusions for both customers and the company. The project involves sentiment analysis of customer reviews and clustering of restaurants into different segments. By visualizing the data, it becomes easier to analyze and draw instant insights.

* The project begins by procuring data from Zomato, including information such as restaurant names, cuisines, average cost for two, ratings, and user reviews. The data is then cleaned and preprocessed, which involves eliminating duplicate entries, addressing missing values, and transforming the data into an analyzable format.

* clustering is implemented using the k-means algorithm to group similar restaurants together and identify patterns in the data. The features used for clustering include cuisines,Number of cuisines, and average cost for two. The number of clusters is determined using the Elbow method and Silhouette method.

* Sentiment analysis is then conducted on user reviews with the help of VADER using Sentiment Intensity Analyzer to understand the overall sentiment towards the restaurants. The reviews are classified as positive, negative, or neutral using appropriate libraries. Additionally, the most impactful words in the reviews are extracted through the application of Latent Dirichlet Allocation and visualized through word clouds.

* The analysis reveals that the restaurants in the city are grouped into two clusters based on their Cuisines, Number of cuisines, and Average cost for two. The sentiment analysis indicates that customers generally hold a positive sentiment towards the restaurants.

### **Libraries used in EDA & Machine Learning:**
1. Pandas
2. Numpy
3. Matplotib
4. Seaborn
5. Plotly
6. Sklearn
7. Scipy
8. NLTK
9. Regex 
10. Gensim
11. PyLDAvis


### **Graphs used for representation:**
1. Bar plot
2. Pie plot
3. Box Plot
4. Point plot
5. Tree Map
6. Heatmap
7. Pair plot
8. Word Cloud
9. Violin plot
10. Scatter plot


### **ML Models used for training & testing:**
1. KMEANS CLUSTERING
2. AGGLOMERATIVE CLUSTERING
3. LATENT DRICLET ALLOCATION
4. VADER

> In conclusion, this project demonstrates the effectiveness of clustering and sentiment analysis in gaining a deeper understanding of Zomato restaurant data. The insights derived from the analysis can greatly benefit both restaurants and customers in making informed decisions. The project can be extended to other cities or countries to gain insights into eating habits and preferences in different regions.


