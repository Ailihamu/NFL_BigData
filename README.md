## Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

Python 3* were used in creating this project. There's no need to install libraries for running the code in this project beyond the Anaconda distribution of Python. 

## Project Motivation<a name="motivation"></a>

In this project, I used data from the NFL_BigData competition on kaggle.com, and I was mainly interested in exploring and answering following questions:

1. How the number of plays and the yards gained per play differ in terms of the different quarters during a game? And what relations they have with each others?
2. What are the most frequently used offense formations by NFL teams, and whether/how it would affect the yards covered in a play?
3. Whether/how would the number of defenders in the box affect the yards covered in a play and the actual distance that run by the rusher after a handoff?
4. Whether/how well can we predict yards covered in a play by using the given features in the data? 

## File Descriptions <a name="files"></a>

Threr are five notebooks available here:

1. NFL_GameIntencity.ipynb - a notebook mainly related to the first question above to explore the the number of plays and the yards gained per play in different quarters during a game.
2. NFL_TeamFormationByYards.ipynb - a notebook for finding the most frequently used offense formations by NFL teams, and its affects on he yards covered in a play.
3. NFL_DefendersInTheBox.ipynb - a notebook for answering the third question by exploring the relations between the number of defenders in the box and the yards covered in a play or the actual distance that run by the rusher after a handoff.
4. NFL_PredictingYards.ipynb - with this notebook I tried to predict the yards covered in a play with linear regression models. 
5. NFL_PlayVisualisationWithPlayId.ipynb - in order to have a better visual understanding of a team formation and players positions in a specific play, in this notebook I tried to draw a football field and plot the players' positions of the two teams in a play.

I used both markdown cells and # in the code to help walk through the processes of individual steps.

## Results<a name="results"></a>

Please see the main findings of this project at the post available [here](https://medium.com/@elham.abdurusol/visualising-relationships-in-sports-data-findings-from-nfl-big-data-daf301d5f867?sk=f52ca71ce2213679b17fc80bc98459db)

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

I must give credit to NKL_BigData competition on kaggle.com for the data. You can find the Licensing for the data and other descriptive information at the Kaggle link available [here](https://www.kaggle.com/c/nfl-big-data-bowl-2020/data) 
