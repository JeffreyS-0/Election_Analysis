# Election_Analysis

## Project Overview
Two employees from the Colorado Board of Elections, named Seth and Tom have given me the following tasks to complete the election audit of a recent local congressional election.

1. Calculate the total number of votes cast.
2. List the counties that votes were casted in.
3. Calculate the total votes each county had casted.
4. Calculate the percentage of votes in each county.
5. Determine the largest county based on number of votes casted.
6. Get a complete list of candidates who received votes.
7. Calculate the total number of votes each candidate receieved.
8. Calculate the percentage of votes each candidate won.
9. Determine the winner of the election based on popular vote.

## Resources
- Data Source: election_results.csv
- Software: Python 3.9.6, Visual Studio Code: 1.60.0

## Summary
The analysis of the election show that:
- There were 369,711 votes casted in the election within 3 counties.
    - Jefferson County: 10.5% of total votes with 38,855 ballots casted.
    - Denver County: 82.8% of the total votes with 306,055 ballots casted.
    - Arapahoe County: 6.7% of the total votes with 24,801 ballots casted.

- Largest County Turnout: Denver - 82.8% of the total votes with 306,055 ballots casted.

- The candidates were:
    - Charles Casper Stockham
    - Diana DeGette
    - Raymon Anthony Doane
- The candidate results were:
    - Charles Casper Stockham received 23% of the vote with 85,213 votes.
    - Diana DeGette received 73.8% of the vote with 272,892 votes.
    - Raymon Anthony Doane received 3.1% of the vote with 11,606 votes.
- The winner of the election was:
    - Diana DeGette, who received 73.8% of the vote with 272,892 votes.

## Election-Audit-Summary
The script that was written for this analysis is also used to audit the count of votes that were casted within 3 counties. With some modifications, this script can be used in the same manner for other elections. We could easily modify our code to be used for local city or even the presidential elections. Most of the code would stay the same; the way we count votes and decide who won will be the same. However, we can modify our code related to 'Counties' and change it to 'Zip Codes' for local city elections and 'State' for Presidential elections.
