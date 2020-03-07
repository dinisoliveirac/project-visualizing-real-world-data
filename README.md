#   Project: Visualizing Real World Data

Dinis Oliveira Costa
Data Part-time Dic 2019


## Content
- [Project Description](#project)
- [Data](#data)
- [Workflow](#workflow)
- [Results](#results)


## Project Description

- The goal of this project was to practice interpreting different types of visualizations by collecting relevant information about players from different teams and nationalities that were playing during the year of 2019 in order to compare their attributes and analyse the differences between the leagues where each of them plays.


- The commands assume a basic understanding of the Pandas, Matplotlib and Seaborn libraries.

## Data

The data used in this project was collected from:

- `FIFA 19 complete player dataset` - a free dataset from Kaggle containing 18k+ FIFA 19 players and ~90 attribute points extracted from the latest FIFA database

The attributes' list includes: 

- Age, Nationality, Overall, Potential, Club, Value, Wage, Preferred Foot, International Reputation, Weak Foot, Skill Moves, Work Rate, Position, Jersey Number, Joined, Loaned From, Contract Valid Until, Height, Weight, LS, ST, RS, LW, LF, CF, RF, RW, LAM, CAM, RAM, LM, LCM, CM, RCM, RM, LWB, LDM, CDM, RDM, RWB, LB, LCB, CB, RCB, RB, Crossing, Finishing, Heading, Accuracy, ShortPassing, Volleys, Dribbling, Curve, FKAccuracy, LongPassing, BallControl, Acceleration, SprintSpeed, Agility, Reactions, Balance, ShotPower, Jumping, Stamina, Strength, LongShots, Aggression, Interceptions, Positioning, Vision, Penalties, Composure, Marking, StandingTackle, SlidingTackle, GKDiving, GKHandling, GKKicking, GKPositioning, GKReflexes, and Release Clause.


## Workflow

The project follows three essential steps: 
- **1) Data Cleaning**, 
- **2) Data Manipulation** and 
- **3) Data Visualization** - in order to make it easy to keep track of changes and better structure the clean data set.


### Step 1 - ` Data Cleaning`

- using the given dataset, it is possible to get a clear idea of how each row is characterised given the original column names; 

- since the objective is to interpretate a few attritubes from the list, we will begin by cleaning those which do not support our analysis.

1.1 - Dataset exploration
1.2 - Data columns cleaning
1.3 - Data Cleaning

### Step 2: `Data Manipulation`:

- resorting to each player's attributes, it is possible to draw conclusions by comparing their average team numbers and countries of origin; 

- using a list of all the major european leagues, we will be able to compare differences between the average player attribute's that plays on each of them;

2.1 - Defining the attributes to compare
2.2 - Divide and group the players by team and league where they play at
2.3 - Divide and group the players by country of origin
2.4 -Creating new DataFrames with the data collected


### Data Visualization:

3.1 - Data Cleaning of the final DataFrame
3.2 - Analysis of the results



## Results

- Clean data set containing all the attributes from each of the players from the teams that we analysed;
- Set of figures that help visualize the results and draw conclusions about the dataset


## Deliverables
- `data.csv` - with all the data collected from Kaggle
- `Fifa.ipynb` - containing all the code that built the project
- `figures` - containing the product of all the visualization that supported the project