# NFL-Network-Analysis
The National Football League is the biggest sports league on the planet by revenue. In general, professional sports are a major source of income for the USA. As a result, the use of sports science has been very notable throughout the last decade, and many experts in the NFL are using sports science to make informed decisions on matters like who to hire or who to trade from the team. However, much of the data that people currently look at for football sports science tends to have a recency bias. Our project will be unique in that it will provide both a historical and recent visualization of NFL player data, and it will allow for decisions to be made based on data that is more historical.

# Structure
The ```data``` directory contains all the csv files used in our project
* ```data/raw``` contains all of the raw data used as input for our project. This data was found [here](https://github.com/nflverse).
  * ```player_stats_season.csv``` contains statistical and fantasy data for each player
  * ```players.csv``` contains personal and collegate data for each player
* ```gephi_node_list.csv``` and ```gephi_edge_list.csv``` are processed versions of the data formatted for use in Gephi
<br/><br/>

The ```notebooks``` directory contains all the notebooks used in our project
* ```create-network-from-dataset.ipynb``` Takes in the raw data and converts it into a node and edge list

# Installation
You will need a working version of [Anaconda](https://www.anaconda.com/docs/getting-started/anaconda/install) or [Miniconda](https://www.anaconda.com/docs/getting-started/miniconda/install) and [Python3](https://www.python.org/downloads/)

The repository contains a ```conda_env.txt``` file that can be used setup a conda environment. This is done with
``` 
$ conda create --name <name of env> --file <path to conda_env.txt>
```
Once created, the environment can be activated with
``` 
$ conda activate <name of env>
```
Once the correct environment is activated, you can launch JupyterNotebook and navigate to the desired notebook
``` 
$ jupyter-notebook
```
