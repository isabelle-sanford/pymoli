# pymoli

This takes in a csv with purchase data about the (fictional) game "pymoli" and analyzes it using pandas. The output it returns is given below. 

A few notable trends from that data: 
1. As is the case with a great many computer games, the overwhelming majority (84%) of the player base is male. Interestingly, the average single purchase by a woman will be slightly higher than a man's, but if you look at the total money spent the men will outspend the women. (Essentially, women tend to purchase fewer, more expensive items and vice versa.)
2. A significant majority (62%) of the player base is between 15 and 25 years of age, and likely indicates most players are in some form of upper education (high school or college). 
3. Even the most profligate spenders still don't buy much: no one bought more than five items, and only three people (of 576) bought more than three. 


### Player Count

* Total Number of Players

### Purchasing Analysis (Total)

* Number of Unique Items
* Average Purchase Price
* Total Number of Purchases
* Total Revenue

### Gender Demographics

* Percentage and Count of Male Players
* Percentage and Count of Female Players
* Percentage and Count of Other / Non-Disclosed

### Purchasing Analysis (Gender)

* The below each broken by gender
  * Purchase Count
  * Average Purchase Price
  * Total Purchase Value
  * Average Purchase Total per Person by Gender

### Age Demographics

* The below each broken into bins of 4 years (i.e. &lt;10, 10-14, 15-19, etc.)
  * Purchase Count
  * Average Purchase Price
  * Total Purchase Value
  * Average Purchase Total per Person by Age Group

### Top Spenders

* Identify the the top 5 spenders in the game by total purchase value, then list (in a table):
  * SN
  * Purchase Count
  * Average Purchase Price
  * Total Purchase Value

### Most Popular Items

* Identify the 5 most popular items by purchase count, then list (in a table):
  * Item ID
  * Item Name
  * Purchase Count
  * Item Price
  * Total Purchase Value

### Most Profitable Items

* Identify the 5 most profitable items by total purchase value, then list (in a table):
  * Item ID
  * Item Name
  * Purchase Count
  * Item Price
  * Total Purchase Value

This was completed as the week 4 (pandas) homework for USC Viterbi Boot Camp. 
