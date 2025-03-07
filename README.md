# Player-NBA-Analysis-
Uncovering the Powerhouses: Analyzing Historical Player Data (1880-2010) to Reveal Which Schools and Teams Produced the World’s Best NBA Players!"
Business Situation:
You have access to decade worth of data including player statics like school attended , salaried, team played, height and weight
Use advanced SQL querying technique to track how player statistics have changed over time and across different teams in the league.
Objectives and Key Findings:
Objective 1: "School Analysis"
a) In each decade, how many schools were there that produced MLB players?
In the year 1980 produced 473 players
b) What are the names of the top 5 schools that produced the most players?
>"University of Texas at Austin"
>"University of Southern California"
"Arizona State University"
"Stanford University"
"University of Michigan"
c) For each decade, what were the names of the top 3 schools that produced the most players?
University of Florida
University of Texas
Georgia Institute of Technology
Objective 2: "Salary Analysis"
a) Return the top 20% of teams in terms of average annual spending
Team ID SFG with average spending in Millions up to 143.5
b) For each team, show the cumulative sum of spending over the years
Sample output as ANA/1997/31.1
c) Return the first year that each team's cumulative spending surpassed 1 billion
Sample output as ARI/2012/1.02
Objective 3 : "Player Career Analysis":
a) For each player, calculate their age at their first (debut) game, their last game, and their career length (all in years). Sort from longest career to shortest career.
Sample Output as Nicholas/21/57/35
b) What team did each player play on for their starting and ending years?
>Sample Output "Shigetoshi"/	"ANA"/1997/"SEA"/2005
c) How many players started and ended on the same team and also played for over a decade?
>Sample Output "Thomas Michael"/"ATL"/1987/"ATL"/	2008
Objective 4 : Players Comparison Analysis
a) Which players have the same birthday?
>Sample Output 1980/	"Bradley Keith, DaRond Tyrone"
b) Create a summary table that shows for each team, what percent of players bat right, left and both.
> Sample Output ANA/61.1/31.6/7.3
c) How have average height and weight at debut game changed over the years, and what's the decade-over-decade difference?
> Sample Output 1870/0.7423/5.8693
Please check out my Sample SQL code for more info.
Lesson Learnt:
It gave in-depth knowledge of how schools can impact player career
Through this is Project I learnt about new features in SQL like STRING_AGG(nameGiven, ', ' ORDER BY nameGiven) which is used for String Concatenation
