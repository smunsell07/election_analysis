
# Election Analysis

## Overview of Election Audit
The Colorado Board of Elections requests an election audit of the tabulated results for a U.S. Congressional precinct.

### Audit Tasks

* Calculate the total number of votes.
* Compile the list of counties where citzens voted.
* Compile the list of candidates who recieved votes.
* Calculate the total number and percentage of votes per county.
* Determine the county with largest turnout.
* Calculate the total number and percentage of vote per candidate.
* Determine the winner of the election based on the popular vote.

## Election Audit Results:
* 369,711 votes were cast in this congressional election.
* Each county in the precinct is described below:
    * Jefferson County had 38,855 votes, 10.5% of the votes cast
    * Denver County had 306,055 votes, 82.8% of the votes cast
    * Arapahoe County had 24,801 votes, 6.7% of the votes cast
* Denver County cast the largest number of votes and had the largest county turnout.
* Each candidate in the election is described below:
    * Charles Casper Stockham received 85,213 votes and 23.0% of the votes cast.
    * Diana DeGette received 272,892 votes and 73.8% of the votes cast.
    * Raymon Anthony Doane received 11,606 votes and 3.1% of the votes cast.
* Diana DeGette won the congressional election with 73.8% of the votes cast and 272,892 votes cast for her.
[!PyPoll_challenge_terminal_output](analysis/PyPoll_challenge_terminal_output.png)

## Election Audit Summary

This script can be easily modified to fit many types of elections. In a city election, wards can be exchanged for counties and the rest of the script can be used. For a statewide election, this script could used very closely as-is. However, there will be more counties than a congressional district. In a federal congressional or senate election, the counties would be changed to states. Depending on how the data is provided, some of the parameters may change but the formatting will be very similar. If a local initiative is being analyzed, the script can be modified, changing the candidates to in favor or against.  