# Election_Analysis

## Overview of Election Audit
A Colorado Board of Elections employee has identified the below tasks that need to be completed to assist with auditing a recent local election. The employee 
delivered a CSV file for me to perform the analysis.  My analysis followed the data analysis principles of (1) Determine the number of rows and columns; 
(2) Data types used; and (3) Is the data readable?

Colorado Board Task List for each candidate:
1. Calculate the total number of votes cast.
2. Generate a complete list of candidates who received votes.
3. Calculate the percentage of votes each candidate won.
4. Calculate the total number of votes each candidate won.
5. Determine the winner of the election based on popular vote.

Colorado Board Task List for each county:
1. Generate a list of all counties that participated in the voting.
2. Calculate the total votes for each county.
3. Calculate the percentage of votes for each county.
4. Calculate the county with the largest number of votes.
5. Determine the county with the largest turnout.

## Resources
Data source: [Election Results Data](https://github.com/SheaButta/Election_Analysis/blob/main/Resources/election_results.csv)

- Software Used: Python 3.10 (64-bit), Visual Studio Code 1.62

## Election-Audit Results
The below bullets will describe the results of election.

  - Number of votes cast in this congressional election:
      - 369,711
      - Related code Blocks:  While the source file, election_results.csv, the code counted each vote and assigned that number to a variable named "total_votes".
        
        Code Example:
        
                #Read the csv and convert it into a list of dictionaries
                with open(file_to_load) as election_data:
                    reader = csv.reader(election_data)

                        #Add to the total vote count
                        total_votes = total_votes + 1

  - Number of votes and the percentage of the total votes for each county:
  
      - County Votes:
          Jefferson: Jefferson county received 10.5% of the vote and 38,855 number of votes.
          Denver: Denver county received 82.8% of the vote and 306,055 number of votes.
          Arapahoe: Arapahoe county received 6.7% of the vote and 24,801 number of votes.
  
  - County with the largest number of votes:
      - Denver: Denver county received 306,055 total votes which was 82.8% of the total votes.
      
  - Number of votes and the percentage of the total votes for each candidate:
      - Candidate Votes:
        Charles Casper Stockham: Charles Casper Stockham received 23.0% of the vote and 85,213 number of votes.
        Diana DeGette: Diane DeGette received 73.8% of the vote and 272,892 number of votes.
        Raymon Anthony Doane: Raymon Anthony Doane received 3.1% of the votes and 11,606 number of votes.

  - Winner of the election:
    Diana DeGette: Diane DeGette received 73.8% of the vote and 272,892 number of votes.
    
    All the final results were illustrated in the final analysis report: [Election Analysis](https://github.com/SheaButta/Election_Analysis/blob/main/analysis/election_analysis.txt)

## Summary
The analysis of the election illustrate the following:
- There were 369,711 votes cast in this election and three (3) counties that participated.
- The candidates include:
  - Charles Casper Stockham
  - Diane DeGette
  - Raymon Anthony Doane
- The tally of total candidates was three (3).  The candidates included:
  - Charles Casper Stockham received 23.0% of the vote and 85,213 number of votes.
  - Diane DeGette received 73.8% of the vote and 272,892 number of votes.
  - Raymon Anthony Doane received 3.1%" of the vote and 11,606 number of votes.
  
- The winner of the election was:
  - Diane DeGette
  - Diane DeGette received 73.8% of the vote and 272,892 number of votes.




