# ZS_YDS-2019
ZS Associates Young Data Science Challenge 2019

The task was to predict whether Christiano Ronaldo will shoot a goal or not given the details of his movements and shots in the match. <br/>
Main Variables used: <br/>

1) Power_of_shot               
2) Knockout_match             
3) Game_season                
4) Distance_of_shot           
5) Area_of_shot                
6) Shot_basics                 
7) Range_of_shot            
8) Date_of_game        
9) Against                   
10) Flag_home                                     
11) Remaining_time             
12) No_of_attempts   

Models Used:

1) Cat Boost Classifier with GridSearchCV - Since there were a lot of categorical variables and CatBoost handles them implicitly without the need of encoding.
