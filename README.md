# Golf Tracker
## Google Spreadsheet to track the golf scores of my friends.

Refer to the [Golf Tracker](https://docs.google.com/spreadsheets/d/1-UuXrx3pnWoeeiqAMxPN1uJgUaPxBWK3X6odDJyIv1k/edit#gid=1193067924).

![image](https://user-images.githubusercontent.com/84108349/150269191-1fe073e2-5b14-452d-bec3-1fcc824958f5.png)

The Golf Tracker documents the performances of each member of our friend group. The main goal of the spreadsheet was to demonstrate that we are in fact improving and to add some competition to our golf game.

## Legend (Tab 1)
The Golf Tracker has a legend outlines the colour scheme used within the tracker.

![image](https://user-images.githubusercontent.com/84108349/150245221-af8903b7-c76b-4593-b6d7-0179ce4b54c7.png)


## Courses (Tab 2-3)
The courses that have been played on are document here.

The coloured tees with the corresdoning slope and rating are listed here, along with the par for each hole and the last time the course was verrified.

![image](https://user-images.githubusercontent.com/84108349/150245718-f11afff6-47b1-423a-99dd-14322677a37a.png)


![image](https://user-images.githubusercontent.com/84108349/150245637-620589dc-90fe-411d-bbd6-d07da63c92bf.png)


## Overall Leaderboards (Tab 4-5)
The 18-hole rounds and 9-hole rounds of all players are listed in the corresponding tab. They are both in descending order of the "True Score" (TrSc) of each player's round. 

![image](https://user-images.githubusercontent.com/84108349/150379329-66896366-81a4-47ec-9586-6aba832f9c56.png)

![image](https://user-images.githubusercontent.com/84108349/150379152-acebefe3-15df-45a6-b41c-b364256ebf12.png)

#### True Score (TrSc)
The True Score considers the score of the round as well as the difficulty of the course, allowing for a more fair comparisson between rounds.

The 18-Hole True Score is linked in the following areas:
    - Overall(18) - Column AW
    - Players Pages - Column AT
    
The 9-Hole True Score is linked in the following areas:
    - Overall(9) - Column AE
    - Players Pages - Column BX

The True Score is calculated using the same formula used to calculate a player's handicap. The formula for the True Score can be seen below.

<img src="https://latex.codecogs.com/svg.image?True&space;Score&space;=&space;\frac{(Round&space;Score&space;-&space;Course&space;Rating)*113}{Course&space;Slope}" title="True Score = \frac{(Round Score - Course Rating)*113}{Course Slope}" />

The True Score is calculated using the main formula used to help calculate a player's handicap.

## Personal Pages (Tab 6-15)
Each member of our friend group who golfs has their own player page detailing their personal stats and rounds.
  
#### Player Score (PSc)
The Player Score allows players to see if they are improving and how they compare to other golfers in an impartial manner.

The Player Score is calculated and documented in the BZ Column of the 9-Hole Table on a Player Page.  The Player Score history is plotted in the top left of a Player Page.

![image](https://user-images.githubusercontent.com/84108349/150268116-f8f6bdd9-785f-4020-a20d-90aefa6e3a44.png)

The Player Score is calculated using the generic formula used to calculate a player's handicap, just with some added liberties. A Player Score is calculated based on the 10 best rounds in a player's most recent 20 rounds. The Player Score formula may be seen below.

<img src="https://latex.codecogs.com/svg.image?Player_Score&space;=&space;\frac{\sum&space;{Best&space;B&space;Scores&space;In&space;Most&space;Recent&space;R&space;Rounds}}{B}" title="Player_Score = \frac{\sum {Best B Scores In Most Recent R Rounds}}{B}" />

    ....where B=10 and R=20

However, if less than 20 rounds have been played, consult the table below to find the value of B.

| Rounds (R) | Best __ Scores (B) |
| ---------- |:--------------------:|
| 1-2        | 1                    |
| 3-4        | 2                    |
| 5-6        | 3                    |
| 7-8        | 4                    |
| 9-10       | 5                    |
| 11-12      | 6                    |
| 13-14      | 7                    |
| 15-16      | 8                    |
| 17-18      | 9                    |
| 19         | 10                   |

The player score is then recalculated based on the table below.

| Player Score (P) | Max Per Hole |
| ---------------- |:------------:|
| P<10             | +2           |
| 10<P<20          | 7            |
| 20<P<30          | 8            |
| 30<P<40          | 9            |
| 40<P             | 10           |


    ![image](https://user-images.githubusercontent.com/84108349/150244120-de26b8eb-9195-4268-b6bc-91c3ca6d2d12.png)
  - Tracks their hole scores based on par

    ![image](https://user-images.githubusercontent.com/84108349/150244395-9aec0723-8aba-4536-a861-4744d4aa077c.png)
  - Plots their average round (18-hole and 9-hole)
  
    ![image](https://user-images.githubusercontent.com/84108349/150244322-359d883b-ceaa-4c63-a965-3f64a9aa5f52.png)
  - Tracks player rounds and their averages
  
    ![image](https://user-images.githubusercontent.com/84108349/150244586-53f96397-dc3d-430c-84a3-3e762f20a78b.png)
    
    ![image](https://user-images.githubusercontent.com/84108349/150244607-c0d7e96a-e930-4e7e-ae90-e145fa872c78.png)

