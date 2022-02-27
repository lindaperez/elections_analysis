# Overview of Election Audit:
This analysis is intended to display election results automated from a CSV file that contained a list of votes
per city made to a set of candidates.
 
## Election-Audit Results:
 
- How many votes were cast in this congressional election?
 
![image](https://github.com/lindaperez/elections_analysis/blob/master/Resources/total_votes.png)
 
- Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
 
![image](https://github.com/lindaperez/elections_analysis/blob/master/Resources/county_votes.png)
 
- Which county had the largest number of votes?
 
![image](https://github.com/lindaperez/elections_analysis/blob/master/Resources/largest.png)
 
- Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
 
![image](https://github.com/lindaperez/elections_analysis/blob/master/Resources/candidate_votes.png)
 
- Which candidate won the election, what was their vote count, and what was their percentage of the total votes?
 
![image](https://github.com/lindaperez/elections_analysis/blob/master/Resources/winners.png)
 
## Election-Audit Summary:
 
 
This solution can be used in infinite situations, we would change the CSV file for a different file with the same
type of data (int, string, string) and do the same calculation with different valid results. We can add more rows
and transform the CSV to a bigger file, making the results even more required.
 
 
![image](https://github.com/lindaperez/elections_analysis/blob/master/Resources/totals.png)
 
 
Next, there are two examples of possible uses of this project to generate different insights
 
## Business Proposal: Presidential Elections
 
We can even calculate the presidential election of any country. First, we need that the machines that generate the
results return CSV files. We can generate the Elections Results using any number of candidates, cities, and votes.
 
### Problem: Presidential Elections
 
Result of Business Elections: How to calculate the presidential elections in the US having  19,502 cities,
a population of 329.5M (Reference for the number of rows in the CSV file) and 5 candidates.
 
### Solution:
 
Create or receive a CSV file with the Ids, Cities, and candidates listed by column.
 
- Use this program if less than 1,048,576 people voted and just run it, otherwise make a refactor version.
- Refactor the code to read multiple csvs.
- Manage exceptions.
- Add a set of tests.
- Run the program and present the results.
 
With minimal changes, we can read several CSV and accumulate the results of:
   The President for the next period
   Cities with the highest percentage of participation
   Cities with the highest percentage of absence
   Other candidates results
 
### Cost: 
We need to refactor the code to manage exceptions and test if the file is greater than 1,048,576 rows.
 
## Business Proposal #2: Talent Audition
For this case Let's pretend that we need to identify the best artists and we have a list of skills.
The most skilled artist will have the highest amount of rows.
### Problem: Talent Audition
Generate the result of a talent audition having 11265 artists with 150 different types of skills.
### Solution:
The answer is easy.
- We need to fill the CSV file with the IDs of every row, the skill that the candidate has, and their name.
The list can look like this:
   432443,  Ability to take criticism, Linda Perez
   543543,  Time Managment, Zembra Carman
   324345,  Singer, Dorian Grace
   454354,  Critical Thinking, Linda Perez
   656878,  Self Confidence, Linda Perez
- Finally running the program we can have the most skilled artist and what are the skills most used between the artists.
 
 

