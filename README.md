# Election_Analysis
*Overview of Election Audit: Explain the purpose of this election audit analysis.*
>Our object for these project "Election-Audit" is to provide to our public the results of our compaigne and know who was the winning candidate.  :man_technologist:

*Election-Audit Results: Using a bulleted list, address the following election outcomes. Use images or examples of your code as support where necessary.*



With the explanation shared in these module, Visual Code was a very helpful tool for us, since it's a source code editor that makes our day to day more easier to work with. We achieve in these module:

- How to navigate to folders on our computer using the command line.
- Read and extract data from CSV files.
- Determine the difference between Python data types, like integers, floating-point decimal numbers, and strings.
- Perform mathematical operations using data types.
- Declare variables using different data types.
- Create and use data structures like lists, tuples, and dictionaries.
- Create and use decision and repetition statements.
- Create and use Boolean and logical operators.
- Write data to an output file and print the file.

We managed to obtain :

- Total of votes for our compaigne.
- Votes por Counties.
- Our County with more participation.
- Top 3 candidates.
- Total of votes won per candidate.
- Percentage of votes won per candidate.

Example of our formula we used to obtain our percentage was:

- **vote_percentage = float(votes) / float(total_votes) * 100**


The complete formula applied was:

![candidate vote](https://user-images.githubusercontent.com/114257085/197069009-d9d97269-5b91-4fdf-ab04-4da8396662fd.png)



*How many votes were cast in this congressional election?*

We received a positive participation of votes from society,where we had a ***total of votes for 369,711***.



*Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.*

We managed to compile a database of 36911 rows, were we needed to apply a _"for"_ formula to obtain our top 3 "counties", such as total of votes per county and percentage represented.

**County Votes:**

1. Denver: 82.8% (306,055)
2. Jefferson: 10.5% (38,855)
3. Arapahoe: 6.7% (24,801)



![COUNTY VOTES PER](https://user-images.githubusercontent.com/114257085/197062284-745e500b-2b05-47a0-b53b-602bb3b78731.png)

![COUNTY VOTES](https://user-images.githubusercontent.com/114257085/197062304-34281e6f-3eea-4297-b990-fff3fa559a11.png)


*Which county had the largest number of votes?*

###### The Largest County Turnout was: ***Denver***

![images](https://user-images.githubusercontent.com/114257085/197071403-d3da84ad-a361-44dc-9eb3-6cc0a0a2e015.jpg)


*Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.*

- **Charles Casper Stockham: _23.0%_ (85,213)**
- **Diana DeGette: _73.8%_ (272,892)**
- **Raymon Anthony Doane: _3.1%_ (11,606)**

*Which candidate won the election, what was their vote count, and what was their percentage of the total votes?*

As we can see our candidate Diana DeGette was the winner in these compaigne being on the front for more than 73% of total votes.

- **Winner: Diana DeGette**
- **Winning Vote Count: 272,892**
- **Winning Percentage: 73.8%**

## Election-Audit Summary: 
In this election, the winner had a supermajority, but the criteria was for a popular vote, greater than or equal to 73.8%. This script could be easily modified to run a check for a supermajority, greater than or equal to 66.7% of the votes as the election criteria. A second way to change the code, with the county data, weights could be assigned to the counties to represent the weights of the electoral college votes.Another option is for example if this were a federal election, we could use the same script and change the county to states. One of the best things of using these script is that we're able to edit and altered as many times as needed, until we get the desired results also as personalize for future compaignes or projects. Maybe the election commission would consider a business proposal to make these adjustments and apply it in the future.
