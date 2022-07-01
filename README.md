# Election_Analysis
## Overview of Election Audit
The Colorado Board of Elections tasked Tom and I to audit the results of a recent local election. This allowed the board to have technical data backing the results of the election. This audit also allowed the Colorado Board of elections to determine the representation of each county.

### Election Results
![My Remote Image](Election_Results.PNG)

After the audit of the total 369,711 votes was complete, the following was determined:
* Denver had the highest county turnout of 306,055 ballots, which was equal to 82.8% of the votes.
* Diana DeGette collected 73.8% of the votes. This made her the clear winner, as she far exceed the 50.1% required to win.

### Election Audit Summary
This election winner clearly met the requirement of greater than or equal to 50.1% of the vote, but this is only the popular vote.
In order to allow this code to run for additional types of elections, then the following would need to be changed.
1. The code would need to look at the weights that each county hold and determine the electoral college votes.
2. While this code ran for the popular vote, most elections call for the supermajority. This would maen that the code would need to be changed to select the canidate that had greater than or equal to 66.7% of the vote.



