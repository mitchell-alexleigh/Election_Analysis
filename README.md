# Audit of Election Results  

## Overview of Election Audit

The purpose of this project was to use Python to find election results and voter location data. The Phyton code utilizes data from a CSV file, performs colocations and analysis, then prints the output in a user-friendly text file. To accomplish this, the python code utilizes the following
* Variables 
* Calculations
* List
* Dictionaries 
* decision statements and logical operators 
* Repetition statements 
* print using f-strings 
* reading files
* writing files

## Election Audit Results
* 369,711 votes were cast in the precinct
>> *corresponding Python Code*\
>> ![Total Votes img1](/resources/total_votes_1.png)\
>> ![Total Votes img2](/resources/total_votes_2.png)

* Votes per county: 
	* Jefferson County collected 38,555 votes, accounting for 10.5 % of all votes
	* Denver County collected 306,055 votes, accounting for 82.8% of all votes
	* Arapahoe County collected 24,801 votes, accounting for 6.7% of all votes
> *corresponding Python Code*\
> ![County Votes img1](/resources/county_votes_1.png)\
> ![County Votes img2](/resources/county_votes_2.png)\
> ![County Votes img3](/resources/county_votes_3.png)

* Denver County had the most voters 
> *corresponding Python Code*\
> ![Largest Turnout img1](/resources/turnout_1.png)\
> ![Largest Turnout img2](/resources/turnout_2.png)

* Votes per candidate:
	* Charles Casper Stockham received 85,213 votes, accounting for 23.0% of all votes
	* Diana DeGette received 272,892 votes, accounting for 73.8% of all votes
	* Raymon Anthony Doane received 11,606 votes, accounting for 3.1% of all votes 
	
> *corresponding Python Code*\
> ![Candidate Votes img1](/resources/candidate_votes_1.png)\
> ![Candidate Votes img2](/resources/candidate_votes_2.png)\
> ![Candidate Votes img3](/resources/candidate_votes_3.png)

* Diana DeGette Won the election with the majority of that votes at 73.8% or 272,892 votes
> *corresponding Python Code*\
> ![Winner img1](/resources/winner_1.png)\
> ![Winner img2](/resources/winner_2.png)

## Election Audit Summary 

The python code is designed to be reusable for any election with only minor adjustments. To reuse this code for another election you would need to update “election_data” from the following code to match the file that contained new election data. 
> reader = csv.reader(election_data)

The second aspect of the code I would change is the names for variables, dictionaries and lists related to county. If the user used this code on for a national election, it may be more appropriate to change the county to state. 
