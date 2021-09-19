# Election_Analysis

## Project Overview
A Colorado Board of Elections employee has given you the following tasks to complete the election audit of a recent local congressional election.

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.

## Resources
- Data Source: election_results.csv
- Software: Pyton 3.8.8, Visual Studio Code, 1.60.1

## Summary
The analysis of the election shows that:
- There were "369,711" votes cast in the election
- The candidates were
    - Charles Casper Stockham
    - Diana DeGette
    - Raymon Anthony Doane
- The candidate results were:
    - Charles Casper Stockham received 23.0% of the vote and 85,213 number of votes.
    - Diana DeGette received 73.8% of the vote and 272,892 number of votes.
    - Raymon Anthony Doane received 3.1% of the vote and 11,606 number of votes.
- The winner of the election was:
    - Diana DeGette, who received 73.8% of the vote and 272,892 number of votes.

## Challenge Overview
The election commission has requested some additional data to complete the audit:

1. The voter turnout for each county
2. The percentage of votes from each county out of the total count
3. The county with the highest turnout

## Challenge Summary
The analysis of the election shows that:
- The county results were:
    - Jefferson County made up 10.5% of the votes with 38855 number of votes.
    - Denver County made up 82.8% of the votes with 306055 number of votes.
    - Arapahoe County made up 6.7% of the votes with 24801 number of votes
- The county with the largest turnout was Denver

## Election Audit Summary
- The election comminsion may use this script to analysis the results of any election in the future. The following are two examples that may be used to modify the script:
    1. The file path of where to pull the csv data must be updated based on the file location: 
    file_to_load = os.path.join("Resources", "election_results.csv")
    2. The file path of where to write the output text file must be updated to reflect where the results are to be stored for the new analysis
    file_to_save = os.path.join("analysis", "election_analysis.txt")


