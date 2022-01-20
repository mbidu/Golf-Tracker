# Golf Tracker
## Google Spreadsheet to track the golf scores of my friends.
### Mackenzie Biduk 2020

Refer to the [Golf Tracker](https://docs.google.com/spreadsheets/d/1-UuXrx3pnWoeeiqAMxPN1uJgUaPxBWK3X6odDJyIv1k/edit#gid=1193067924).

![image](https://user-images.githubusercontent.com/84108349/150382379-fad6b771-9240-4a8e-8f85-b35c6ec20a51.png)

The Golf Tracker documents the performances of each member of our friend group. The main goal of the spreadsheet was to demonstrate that we are in fact improving and to add some competition to our golf game.


## Legend (Tab 1)
The Golf Tracker has a legend outlines the colour scheme used within the tracker. Other than the colours used to identify players, the best scores are colder colour.

**(Worst/Hardest)**  RED < PINK < ORANGE < GREEN < BLUE  **(Best/Easiest)**

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
The True Score considers the score of the round as well as the difficulty of the course, allowing for a more fair comparisson between rounds. The **lower** the True Score, the better.

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
Each member of our friend group has their own player page detailing their personal stats and rounds.

![image](https://user-images.githubusercontent.com/84108349/150382379-fad6b771-9240-4a8e-8f85-b35c6ec20a51.png)

#### 18-Hole Rounds Table
The 18-Hole Rounds Table records every 18-Hole round the player has played. 

![image](https://user-images.githubusercontent.com/84108349/150385971-f2500fb3-7f90-4806-aebc-d309e7881fba.png)

All formatting for the table is automatic but the player must enter the following:
    - Course Played (B)
    - Tee Played From (C)
    - Rating of the Course (D)
    - Slope of the Course (E)
    - Date Played (F)
    - Score and Par of Each Hole (J-AS)

Then, the following will be automatically calculated:
    - Course Ranking (A)
    - Round Score (G)
    - Round Par (H)
    - Round Score +/- (I)
    - True Score (AT)
    - Round Overall Ranking (AU)
    
As the player progresses, their career average will be tracked in row 20, along with their yearly average.

#### 9-Hole Rounds Table
The 9-Hole Rounds Table records every 9-Hole round the player has played. *If an 18-Hole round was played, the front 9 and back 9 of the round are added to this table (not automatically yet).

![image](https://user-images.githubusercontent.com/84108349/150385843-4ee0ed3c-578e-499f-986b-00084d4940f8.png)

All formatting for the table is automatic but the player must enter the following:
    - Course Played (AX)
    - Tee Played From (AY)
    - Rating of the Course (AZ)
    - Slope of the Course (BA)
    - Date Played (BB)
    - Score and Par of Each Hole (BF-BV)

Then, the following will be automatically calculated:
    - Course Ranking (AW)
    - Round Score (BC)
    - Round Par (BD)
    - Round Score +/- (BE)
    - True Score (BX)
    - Round Overall Ranking (BY)
    - Player Score (BZ)
    
As the player progresses, their career average will be tracked in row 20, along with their yearly average.

#### Player Score (PSc)
The Player Score allows players to see if they are improving and how they compare to other golfers in an impartial manner. The **lower** the Player Score, the better.

The Player Score is calculated and documented in the BZ column of the 9-Hole Table on a Player Page. The current Player Score is the Player Score of latest entry in the 9-Hole Table. The Player Score history is plotted in the top left of a Player Page.

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

#### Hole Performance
The individual hole performance of the player over their career is depicted in two tables and four pie charts.

![image](https://user-images.githubusercontent.com/84108349/150386147-d9d492fd-4362-468a-9be4-9def99e309c2.png)

The individual hole performance is automatically tallied into the top-left table. The rate is calculated automatically in the bottom-left table. The results of the bottom-left table are illustrated in the four pie charts to the right. 

The table is sorted by par (3-5) and hole result. The hole result legend may be found below.

| Hole Result  | Abbreviation | Score |
| ------------ |:------------:|:------:
| Eagle        | E            |-2     |
| Birdie       | Bi           |-1     |
| Par          | P            | 0     |
| Bogey        | B            |+1     |
| Double Bogey | DB           |+2     |
| Triple Bogey | TB           |+3     |
| Blow Up Hole | Bl           |+3<    |

#### Round Progression
The average round progression over a player's career is illustrate for both 18-Hole and 9-Hole rounds. 

Y-axis - Score of the Hole
X-axis - Hole

![image](https://user-images.githubusercontent.com/84108349/150386199-78a13876-4619-4677-a28d-417e978ef9fb.png)
