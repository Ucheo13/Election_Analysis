# Election_Analysis
## Overview of the Analysis
In this analysis Seth and Tom need help adding the county information to the election audit results. They have previously been able to acquire information on the candidates such as, their vote count and vote percentage. Now it is our job to get the vote count and vote percentage in each county and display it in the terminal and in a new text file.

## Election Audit Results
•	In this congressional election there were 369,711 total votes
•	Denver had 82.8% Jefferson having 10.5%, and Arapahoe having 6.7%. The exact vote numbers were 306,055 in Denver, 38,855 in Jefferson, and 24,801 in Arapahoe
•	Denver had the largest number of votes
•	Charles Casper Stockham has 23% of the votes, Diana DeGette 73.8%, and Raymon Anthony Doane had 3.1%. The exact vote count was 85,213 for Stockham, 272,892 for DeGette, 11,606 for Doane
•	Diana DeGette won the election with 272,892 votes and 73.8% of the votes  
![Election Audit](https://user-images.githubusercontent.com/96452277/150469010-9a2aa2f8-9b31-4b9d-b5a2-d2dcdde90a5b.png)

## Election-Audit Summary
This script was able to successfully sort through over 360 thousand lines and accurately count the number of votes through separate counties and candidates. I propose that this script can be an effective way to create election audit results for any election. There may need to be a couple modifications depending on how the data is presented, but these are easy fixes. You would need to know the index of the county and the candidate. In this script the county index is 1 and the candidate index is 2. If the information is presented in a different order in the csv this would need to be modified. And adding the result of a tie would need to be included. As it is very unlikely, it is still possible. With these modifications in mind this script is very useful for any election.
