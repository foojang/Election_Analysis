**Overview of Election Audit**

Tom and Seth asked me to work with them to process the congressional election results for three counties Jefferson, Denver, and Arapahoe. We were asked to tally all of the votes and identify the winning candidate and what percentage of the vote each candidate received. After delivering the intimal results the election board also asked that we count he votes for each county and what percentage of the votes came from each county. They also asked to identify the county with the largest voter turnout.

**Election-Audit Results**

•	369,711 votes were cast in this election 

•	Votes cast and percentage for each county
o	Jefferson: 38,855, 10.5 % 
o	Denver: 306,055, 82.8%
o	Arapahoe: 24,801, 6.7%

•	Denver had the largest voter turnout

•	Votes cast and percentage for each candidate
o	Charles Casper Stockholm: 85,213, 23%
o	Diana DeGette: 272,892, 73.8%
o	Raymon Anthony Doane: 11,606, 3.1%

•	Diana DeGette won with 272,892 votes and 73.8% of the vote

**Election-Audit Summary**

The proved script can be used to tally the votes of any up coming elections to make vote results quicker and easier to report. Currently the script can be used to tally county and candidate. With minor code added the script can be used to tally points of data. Below is the current code to track the county and candidate. 

Track the winning candidate, vote count and percentage
  winning_candidate = ""
  winning_count = 0
  winning_percentage = 0

Track the largest county and county voter turnout.
  county_candidate = ""
  county_count = 0
  county_percentage = 0
  
This could be expanded to track Types of votes either mail in in person or absentee if the data was added to the csv file 
Track vote type count and percentage 

  Type_vote = ""
  type_count = 0
  type_percentage = 0
