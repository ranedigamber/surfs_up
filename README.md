# surfs_up
Overview of the challenge
In this module we are woowing an investor W.Avy to secure his capital in a Surf-n-Shake shop that we are proposing to be located in Oahu, Hawaii. In order to convice W.Avy that the chosen location is ideal for the Surf-n-Shake shop we have to provide him with detailed analysis of the weather pattern of this location. Our initial analysis had a positive feed back for the investor who now wants to invest in additional locations for similar shops.  For this we have used sqlite, sqlalchemy and flask to generate the necessary analysis. 

Voter turnout in each county.
Percentage of votes from each county out of the total count.
The county with the highest turnout. The output of this analysis will be included in a text file that should be easy to read for audience of any background.
Election-Audit Results:
Total number of votes casted in the congressional election
This election saw a good voter turnout and a total of 369,711 votes were casted across three counties.
Summary of number of votes and the percentage of total votes for each county in the precinct
The result of the number of votes cast and percentage of total votes are as follows:
Denver county: 82.8% (306,055)
Jefferson county: 10.5% (38,855)
Arapahoe county: 6.7% (24,801)
County with largest number of votes
Denver county had the largest voter turnout
Summary of number of votes and the percentage of total votes for each candidates overall
The following is the tabulated result for total votes and percentage of the total for the three candidates:
Diana DeGette: 73.8% (272,892)
Charles Casper Stockham: 23.0% (85,213)
Raymon Anthony Doane: 3.1% (11,606)
Election outcome
The winner for this election was:
Diana DeGette who received 272,892 votes which was 73.8% of the total votes casted.
Various features of the code
How to get candidate vote count
Code Candidate vote count

How to get county vote count
Code_countyvote count

How to get candidate votes percentage
Code_Candidate votes and their percentage

How to get county vote percentage
Code_percentage of county votes

How to get total votes casted
Code_total vote count

Election Audit Summary
The script could be modifed for a national level elections, for example in this audit we declared a dictionary with key=county and value=votes. In a similar fashion we could use a dictionary of list with key=states and values=[list of counties]
We could also use modify the script to iterate over results from past years or they type of ballots cast (mail in, hand counted or computer counted) which could provide more statistical information and reveal any underlying trends or preferences
