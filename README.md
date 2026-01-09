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
<br>
<br>Abilities: 
<br>1. (Basic) Return 10 most similar anime to the given one based on osine similarity
<br>2. (Extended) If <u>limit</u> parameter is set, function will return requested number of similar anime
<br>3. (Filtration) If cours parameter is set, function will return only those anime that started airing in the specified season (support list with length 1 and more)
<br>4. (Filtration) If genres parameter is set, function will return only those anime that belong to the specified genres (support list with length 1 and more)
<br>5. (Filtration) If ratings parameter is set, function will return only those anime that belong to the specified age ratings (support list with length 1 and more)
<br>6. (Filtration) If studios parameter is set, function will return only anime produced by specified studios (support list with length 1 and more)
<br>7. (Filtration) If types parameter is set, function will return only anime of certain types (support list with length 1 and more)
<br>8. (Clustering) If cluster_method is set, function will return only anime from one cluster with a given (support single string value)
