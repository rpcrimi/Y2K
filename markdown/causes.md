# Causes

![](/images/cost_per_gig.png?raw=true "New Story")

Prior to the new millennium, computer storage was very expensive. The average price for a Gigabyte of storage from 1990 to 2000 was around 100 dollars. From 1980 to 1990, the average price per Gigabyte was around 100,000 dollars. Because of this, developers spent a lot of time finding ways to save space with on computers. While most techniques for saving space were problem free, the decision to truncate four-digit dates to two digits caused major problems. 

## Why Truncate?

As stated above, the main reason for truncating these dates was to save space due to the high cost of storage. Most code that developers wrote added "19" to the front of the two-digit date. For example, when the program saw the date 12/16/32, it would interpret the date as 12/16/1932. Developers eventually realized that dates such as 12/16/2032 would be interpreted as 12/16/1932, causing major problems in their software. 

Another reason for truncating these digits was that developers in the years prior to around 1980 had no idea that their code would still be running in the year 2000. Because the developers were naive of the rising impact of computers, they're legacy code continued to run on their systems and eventually caused pandemonium. Another reason for the truncation of dates was that many people were familiar with writing dates in the following format: MM/DD/YY. Because of this, developers thought it was alright to save dates in this format. 

## Calculating Age

To give an example of how the Y2K problem can cause problems, let's say we are trying to determine one's age. To do so, we would take today's date and subtract the person's birthday:

Today's date: 12/11/15
Person's birthday: 12/11/82

If we subtracted 82 from 15, we would conclude that the person was -67 years old...odd?

## World Reaction

![](/images/y2k_survival?raw=true "New Story")

The Y2K problem became apparent to developers in the early 1990's. Most problems that arose from the Y2K problem were related to large sectors (stock market, insurance). As this problem became more mainstream, people began to realize its serious implications. While most assumed that these problems would be fixed without any side-effects, some began to panic. Some believed that the Y2K problem would cause a global stock market crash and thought the "end of the world" was evident.