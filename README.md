# Board Game Analysis

In this project, we analyzed data from BoardGameGeek.com (https://www.kaggle.com/mrpantherson/board-game-data) to understand:

1. What features can we recommend our clients to produce the highest ratings in a new game?
2. If a user inputs certain characteristics, can we recommend a similar game for them to try? 

By running exploratory analysis using Net Promoter Score and implementing a multiple regression and decision tree model, we concluded that a board game maker should create longer, complex games, target audiences of at least 13 years, and conceptualize wargame centered games.

There were multiple learning points along the way - namely, I learned that a significant flaw of survey data is the bias of respondents. As people answer within a range of "polite" scores, the data doesn't accurately reflect the truth. Therefore, we implemented the Net Promoter Score, a method of measuring the willingness of customers to recommend a company’s products or services to others. It is used as a proxy for gauging the customer’s overall satisfaction with a company’s product or service and the customer’s loyalty to the brand. 


![alt text](https://github.com/helenashi95/Board-Game-Analysis-Project/blob/master/survey.PNG)
![alt text](https://github.com/helenashi95/Board-Game-Analysis-Project/blob/master/NPS.PNG)
![alt text](https://github.com/helenashi95/Board-Game-Analysis-Project/blob/master/tree.png)

We also created an interactive bokeh app that allowed users to input preferred characteristics and view recommended games based on game rank.

![alt text](https://github.com/helenashi95/Board-Game-Analysis-Project/blob/master/bokeh%20app.png)
