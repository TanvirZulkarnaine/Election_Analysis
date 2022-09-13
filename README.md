# Election_Analysis

# Overview of Election Audit
A Colorado Board of Elections employee, Tom and Seth, has given me the following tasks to complete the election audit of the recent local congressional election.

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of the votes each candidates won.
5. Determine the winner of the election based on popular vote.
6. Get a complete list of counties, number of votes, percentage of votes of each county and county with the highest votes.

## Resources
- Data Source: [Election results](/Resources/election_results.csv)
- Software: Python 3.6.7, Visual Studio Code 1.38.1

## [Election-Audit Results](/analysis/election_results.txt)
The analysis of the election show that:
- There were 369,711 votes cast in the election.

- County Votes:
    - Jefferson: 10.5% (38,855)
    - Denver: 82.8% (306,055)
    - Arapahoe: 6.7% (24,801)

- County with the largest number of votes: Denver

- The Candidate results were:
    - Charles Casper Stockham received 23.0% of the vote and 85,213 number of votes.
    - Diana DeGette received 73.8% of the vote and 272,892 number of votes.
    - Raymon Anthony Doane received 3.1% of the vote and 11,606 number of votes. 

- The winner of the election was:
    - Diana DeGette, who received 73.8% of the votes and 272,892 number of votes!
 
## Election-Audit Summary: 
This script is very powerful as it can run analysis on csv files with 369,711 rows of data in a very short amount of time! Furthermore, this script can be modefied to filter data according to the modifier's choice. For example, suppose there was another column for provinces and the script can be modefied to filter the province data such that it can show number of votes per provinces. Hence, this script is not limited to only the columns of data presented in the csv file and can work perfectly fine with additional columns of data (if added). Also, I should mention that the script is limited to running only one analysis, as it can run multiple analysis as demonstrated with the votes per candidates and counties. Thus, using the same/similar algorithm of the script, the modifier can run multiple analysis of their csv file and write out their analysis findings on a txt file if thet choose to do so!

[Link to the script](/PyPoll_Challenge.py)

