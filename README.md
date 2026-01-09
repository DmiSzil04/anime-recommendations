# anime-recommendations
Stages:
<br>1. Preprocessing:
   1.1. Get info about dataset
   1.1. Drop duplicates
   1.2. Drop empty values by some columns
2. Type casting
3. Categoical parameters preprocessing
4. Numerical parameters preprocessing
5. Anime cours and year seasons detection
6. Release year preprocessing
7. Assembling data into a dictionary
8. Dimensionary reduction
9. Clustering
10. Writing recommendation function and attendent functions for filtration

Data: Anime dataset (URL: https://www.kaggle.com/datasets/tanishksharma9905/top-popular-anime)
Input: Anime name
Output: List of some most similar anime for input based on cosine distances
