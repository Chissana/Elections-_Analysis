# Elections_Analysis
## Project Overview 
The purpose of the election audit is to help the Colorado Board of Elections detvote ermine the winner of a recent congressional election based on popular vote, the percentage of votes each candidate won, and the total number of votes cast.
 
## Election-Audit Results
* There were 369,711 votes cast in this congressional election.
* Number of Votes and Percentage of each County:
  * Jefferson: 38,855 votes 10.5%
  * Denver: 306,055 votes 82.8%
  * Arapahoe: 24,801 votes 6.7%
* Denver county had the largest number of votes: 306,055
* Number of votes and Percentage of each Candidate:
  * Charles Casper Stockham: 85,213 votes 23%
  * Diana DeGette: 272,892 votes 73.8%
  * Raymon Anthony Doane: 11,606 votes 3.1%
* Diana DeGette won the election with 272,892 votes 73.8% of votes.

<img width="574" alt="Screen Shot 2022-10-16 at 7 57 35 PM" src="https://user-images.githubusercontent.com/113744353/196065226-b9e4976a-8bd0-4688-bcc2-19cace320a9f.png">

## Election-Audit Summary 
To the Election Commissions: This script can be used for any election going forward if you make minor changes.
  * The first change would be for another local election: you would need an entirely new csv file with new Ballot Ids, counties, and candidates then you would edit the part in the code that would read from this specific .csv file to your new .csv file.
 * The second change would be depending on how large the election is: you would not only change the .csv file with updated information you would have to change some varaiable names, if it is a country wide election, to state names.
