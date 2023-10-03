# TITAN SPORTS SIMULATOR
Developed as a Final portfolio webstack project for alx-software engineering course
![alt text](https://github.com/JackTravisKyeyune/Titan_sports_simulator/blob/master/static/sss.png)
## Main Page
This project consists in a website, made in Flask, and use some different languages, such as 
*HTML5*, 
*CSS and JavaScript*, 
*SQlite*,  
*Python*. 
The main theme of the web application is soccer. 
The simulation of matches is the core of the web application, however that isn't all, the Titan Simulator also has Statitics and Comparison tabs.

## Installation
To run the Titan simulation Game locally, follow these steps:
Clone the repository:
git clone https://github.com/JackTravisKyeyune/Titan_sports_simulator.git

Navigate to the project directory: cd Titan_sports_simulator

Install the dependencies: pip install -r requirements.txt

Start the development server: flask run

Open your browser and visit localhost:5000 to access the application.

## Simulate
In the simulation tab, Titan Sports Simulator can predict the result for a soccer match and the simulation is made using the open-source CatBoost regressor, a machine learning algorithm that uses gradient boosting on decision tree, only considering previous home and away results for both home and away teams, respectively, on the database. Another consideration is that the simulation is made as if the game took place immediately after the last one in the database.

## Statistics
The website also has statistics tabs: statistics comparison. In the statistics tab, you can choose a team and view its wins, losses and draws on all matches in the database presented dynamic graphics, made with JavaScript, such as pie charts and a line chart showing team's performance throught seasons.

## Compare
In the comparation tab, you can make comparations between teams from the same country to see which one is the best, based on their previous results against each other, as shown below.

The database used for this application belongs to Hugo Mathien and it is available 
[kaggle.com](https://www.kaggle.com/datasets/hugomathien/soccer)
