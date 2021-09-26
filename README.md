# Election _ Analysis

## Project Overview
A Colorado Board of Elections employee has given the following task to complete the election audit of a recent local congressional election.

1. Calculate the total number of votes cast.
2. Get a complete list of the candidates who received votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.

The above information was provided to the election commission.  The election commission has now requested some additional data so that they can complete the audit. Below is the additional data they are requesting.

1. Calculate the voter turnout for each county.
2. Calculate the percentage of votes from each county out of the total vote count.
3. Determine the county with the highest turnout.

An updated analysis has been generated to include the new requested information. 

## Resources
- Data Source: election_results.csv
- Software: Python 3.7.6, Sublime text editor

## Election-Audit Results:

The analysis of the election show that:
- There were 369,711 votes cast in the election.
- County Vote breakdown:
	- Jefferson: 10.5% (38,855)
	- Denver: 82.8% (306,055)
	- Arapahoe: 6.7% (24,801)
- Largest County Turnout: 
	- Denver county had the largest number of votes
- The candidates were:
	- Charles Casper Stockham
	- Diana DeGette
	- Raymon Anthony Doane
- The candidate results were:
	- Charles Casper Stockham 23.0% of the vote and 85,213 votes.
	- Diana DeGette 73.8% of the vote and 272,892 votes.
	- Raymon Anthony Doane 3.1% of the vote and 11,606 votes.
- The winner of the election was:
	- Diana DeGette, who received 73.8% of the vote and 272,892 votes

The election analysis is written to the election_results.txt file.  

## Election-Audit Summary
With the addition of code to ask the user to input their specific election results file would make the script more scalable to other elections that may have different file names or file locations.  Also, additional code could be added to check the election results file to determine if the data is in the correct columns and reformat if needed.  The addition of county population data to the election results csv file or coded to be an input provided by the user would allow for additoinal analysis.  One case would be to determine the counties with the lowest percentage voter turnout to determine where to focus efforts to determine possible causes (low voter registration, issues with voter accessibility, etc.) so that recomendations can be made on improving voter turnout.
