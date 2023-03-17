# java-term-project-Julian12m
java-term-project-Julian12m created by GitHub Classroom   
Author:Julián Martínez Lacovic   
   

## Structure of the project's folders
* **/src**: Folder with source code.
  * **fp.points**: Package which contains the different types of the project.
  * **fp.points.test**: Package which contains the test classes of the project.
  * **fp.utils**:  Package that contains the utility classes. 
* **/data**: Contains the dataset of the project.
    * **points.csv**: CSV file that contains the data of the nba players who have scored the most points.
    
## Structure of the *dataset*

The dataset NBA all-time scoring leaders can be obtained from the following link, https://www.kaggle.com/datasets/mathurinache/nbaalltimescoringleaders?resource=download. This dataset has 20 rows, one for each NBA player in the top 20 all-time scoring and it has 64 columns.Here are the descriptions of the 64 columns of the dataset:

* **Leaders Names**: of type string, it has the jersey number and the name of the NBA player.
* **All-time Rank**: of type integer, it indicates the all-time rank of points scored of each player.
* **1960-2019(60 columns)**: of type integer, these 60 columns include 60 years, from 1960 to 2019(both included), in which each column corresponding to each year indicates how many total points each NBA player had by that year.
* **Total Points**: of type integer, it indicates the number of total points scored by each player.This column actually has the same values as column 2019.

## Types implemented

The types that have been implemented in the project are the following:

### Type Base - Mostpoints
Represents the NBA players with most points.   
**Properties**:

- _topscorer_, of type _Boolean_, consultable. Indicates the player with the most points.   
- _scorers_, of type _string_, consultable. Indicates the names of the top 20 NBA scorers.   
- _mostpoints_, of type _integer_, consultable. Indicates the number of points that the topscorer has scored.   
- _leastpoints_, of type _string_, consultable. Indicates the number of points that the player with least number of points has scored.   
- _top3scorers_, of type _List<string>_, consultable. Contains a list of the 3 players that have scored the most points.   

