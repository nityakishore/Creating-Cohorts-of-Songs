# Creating Cohorts of Songs

In this project, I have created cohorts of songs for Spotify to aid in recommending songs to users based on relevant features. The project involved data inspection, cleaning, exploratory data analysis, feature engineering, and cluster analysis to gain insights into song characteristics and patterns.

## Data Inspection and Cleaning:
Sarted by inspecting the dataset for duplicates, missing values, irrelevant entries, and outliers. After careful examination, addressed the issues found. I removed duplicate records, handled missing values using appropriate methods (e.g., imputation), and dealt with erroneous entries and outliers using various techniques like data transformations or capping/extending values.

## Exploratory Data Analysis and Feature Engineering:
During exploratory data analysis, I used various visualizations to find patterns and relationships between different features of songs. One specific analysis involved identifying two albums that could be recommended to anyone based on the number of popular songs in an album. This was achieved by grouping songs by albums, calculating the popularity of each song, and then aggregating the popularity scores for each album. The two albums with the highest aggregated popularity were recommended.

Explored how a song's popularity related to various factors like genre, artist, release year, and more. We observed trends and fluctuations in popularity over time. This analysis helped us understand which factors significantly influenced a song's popularity and how they changed over time.

I also performed dimensionality reduction techniques, such as Principal Component Analysis (PCA) or t-SNE, to reduce the number of features while preserving the most relevant information. These techniques were helpful in visualizing high-dimensional data and identifying patterns within it.

## Cluster Analysis:
For cluster analysis, I aimed to group songs into cohorts based on their characteristics. To identify the right number of clusters, I used methods like the Elbow Method or the Silhouette Score to find the optimal number of clusters that would minimize intra-cluster variance while maximizing inter-cluster variance.

Using an appropriate clustering algorithm (e.g., K-Means, Hierarchical Clustering), also divided the songs into distinct clusters based on features like tempo, energy, danceability, and more. Each cluster was then defined and described based on the dominant characteristics of the songs within it.
