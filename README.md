# recommendtationSystem
2023 Machine Learning team project_using AWS sagemaker


### Game Recommendation Based on Data provided
* Combine item-based and content-based filtering methods to analyze game features, similarities between games and user preferences
* Build a nuanced and tailored model of game suggestions, ensuring that users receive personalized recommendations based on characteristics of games and their gaming behavior
<br>

### Datasets used
* users.csv - 
 a table of user profiles' public information: the number of purchased products and reviews published
* games.csv - 
 a table of games (or add-ons) information on ratings, pricing in US dollars $
* recommendations.csv - 
a table of user reviews: whether the user recommends a product. The table represents a many-many relation between a game entity and a user entity.
<br>

### Modeling
* Item-based, Content-based filtering using 
KNN and DecisionTreeClassifier, SVD
<br>

### Model description
![image](https://github.com/baeksh0330/recommendtationSystem/assets/78344141/cead0eee-63bb-4192-9857-666bf606d482)
<br>
<br>
<hr>

### members
#### Kang Minjae https://github.com/kangminjae0099
* presentation
  
#### Shin Hyoyoung https://github.com/HyoYoungShin
* dataset preprocessing
* SVD model building
  
#### Baek songhee https://github.com/baeksh0330
* dataset preprocessing
* item-based model building
 
#### Wang Minkyung https://github.com/wmk-10
* dataset preprocessing
* item-based model building
* content-based model building
  
<br>

### References
[MEDIUM] Building a Movie Recommendation Engine in Python using Scikit-Learn<br>
https://medium.com/code-heroku/building-a-movie-recommendation-engine-in-python-using-scikit-learn-c7489d7cb14 <br>
[Kaggle] Game Recommendations on Steam <br>
https://www.kaggle.com/datasets/antonkozyriev/game-recommendations-on-steam
