# PyPoll with Python

## Overview of Election Audit
The purpose of our analysis is to assist a Colorado Board of Elections employee on his audit of a congressional district. We will create a phyton script to provide the desired tabulation and calculations based on the given dataset. 

## Election-Audit Results
* How many votes were cast in this congressional election?

    ![Total Votes Casts](/total_votes.png)

* Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.

    ![County Breakdown](/county_data.png)

* Which county had the largest number of votes?

    ![County with Most Votes](/largest_county.png)

* Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.

    ![Candidate Breakdown](/candidate_data.png)

* Which candidate won the election, what was their vote count, and what was their percentage of the total votes?

    ![Winning Candidate](/winner_data.png)


## Election-Audit Summary

This phyton script could easily be applied "as-is" for other congressional districts if their datasets are formatted in the same format. The format required is a CSV file where each row has 2 columns of information. That information would be in the following order: Ballot ID,County,Candidate. 

With a dataset formatted in the same fashion, the python script would give you the required results without changing any code. 

To take it a step further. If all datasets are known to be in the same format, then you can make this script interactive. The section that includes the filepathways can be rebuilt to accept user input for the file or file location. This could make the script useable for anyone in the state with properly formatted data. 


## Author
> Chris Newell 12/12/2021
