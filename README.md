# anime-recommendations
Stages:
<br>1. Preprocessing:
<br>   1.1. Get info about dataset
<br>   1.1. Drop duplicates
<br>   1.2. Drop empty values by some columns
<br>2. Type casting
<br>3. Categoical parameters preprocessing
<br>4. Numerical parameters preprocessing
<br>5. Anime cours and year seasons detection
<br>6. Release year preprocessing
<br>7. Assembling data into a dictionary
<br>8. Dimensionary reduction
<br>9. Clustering
<br>10. Writing recommendation function and attendent functions for filtration
<br>
<br>Data: Anime dataset (URL: https://www.kaggle.com/datasets/tanishksharma9905/top-popular-anime)
<br>Input: Anime name
<br>Output: List of some most similar anime for input based on cosine distances
