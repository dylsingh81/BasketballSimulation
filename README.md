# BasketballSimulation Test
Java project that generates basketball players and allows the user to pick 
their team and simulate games across multiple seasons.

## Images
Startup
![startup](images/startup.png)

Roster example
![roster](images/roster.png)

Season result
![result](images/seasonResult.png)

Game example (LAL x PHI)
![lakers](images/lakeGame.png)
![sixers](images/sixerGame.png)
## System Requirements / Installation
- Minimum Java 8 JDK installed on system

## Running Project
- Command line execution
    - Set directory to BasketballSimulation/src
    - Run command "javac Application.java"
    - Code will compile, then run command "java Application"
- IDE execution
    - Run Application in src
    
## Project Information
- Ratings
    - Google sheets document containing ratings chart can be found
    at following link: https://docs.google.com/spreadsheets/d/1tk86oxKHMditV0BVOPA5ccWqQACw86BUwhzOJUEwbwI/edit?usp=sharing
- League restrictions
    - Teams available: Lakers, Warriors, Sixers, Celtics
- Simulation
    - Scores generated by taking a player's rating and role and comparing it to
    the opposing team's ratings. Individual player stat lines are generated and added to
    produce box scores.

## Possible Improvements
- Add more teams to league
- Adjust ratings for a wider range of outcomes
- Add championship MVP
- Player and coach retirement
- New players entering league
- Ratings change as players ages
- Free agent pool with ability to add & drop players
- Switch from console UI to JavaFX UI

## Acknowledgments
First names credit:
https://www.cs.cmu.edu/afs/cs/project/ai-repository/ai/areas/nlp/corpora/names/male.txt

Last names credit:
https://github.com/arineng/arincli/blob/master/lib/last-names.txt

