# ASSIGNMENT 3: CLEANING DATA 

* The link to the updated dataset can be found [here]().

* After learning that I read the data set *incorrectly* I started from scratch and attempted to clean the data more thoroughly. The dataset I download included data on registered voters and actual voter turnout from 1964 - 2022. I wanted to analyze the actual voter turnout for voters 18-24, so I created a new tab to only include the total number of 18-24 year olds who voted. The total number of voters was in the *thousands* which meant in order to see the actual number of 18-24 year olds who voted, I had to some Excel math. In a new column, I multiplied the #s in column B, row 8 (**total voting-age population**) with the #s in column C, row 8 (**total % of the population**) and divided that by 100. Because the numbers were in the thousands I then multiplied by 1000 to get a total number of 18-24 year olds who voted in each election that actually made sense. 

* The interesting question I am answering is: Was youth voter turnout the largest in 2008 and 2020? I am asking this question because in both the 2008 and 2020 presidential elections, the youth vote was heavily discussed by the media and identified as *the* determining factor in both elections' ultimate outcomes.

* The updated pivot table I created confirmed that 2020 and 2008 did in fact have the largest youth voter turnouts. 2020 saw the largest number of 18-24 year old voters with 13,756,320 voters. 2008 had the second largest number with 12,520,509 18-24 year olds voting in the presidential election. Unsuprisingly, presidential elections saw larger turnouts from 18-24 year olds than the midterm elections. 
