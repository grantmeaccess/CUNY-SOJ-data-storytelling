#Spreadsheet Skills

Google tracks searches for flu-related terms. Start at <http://www.google.org/flutrends/> -- it is worth reading up on how they produce this data so you have a sense of the limitations of it, but we're just going to play with it. 

## Using formulas
Pay attention to the screen. Look at what happens when you hover, etc. 

Review of Spreadsheeting skills with Flu data
-sorting to find max and min
-data types (text, number, location, date, etc.)
-what is a formula and a function, what’s the difference? choosing cells

-use a function to find the mean, median and range: look at how mean and median differ. 

-using functions, Max, Min, Average, Median, Unique, Countif, Match, If

## Walk Through

1. Download the world historical flu trends <http://www.google.org/flutrends/data.txt>
3. What is this data? (comma separated)
4. Paste into spreadsheet? Use `Data > Text to Columns` to separate data into columns according to a delimiter
5. In which week did which country had the most flu searches?  
	`=Max()`  
	`=Match(criterion, range, 0)`  
	`=Indirect(“A”&cell)` to get date or re-order columns
6. How much more did that country search for flu in that week than average?
7. Order the countries by most flu searches (SUM...choose arbitrary 2012-13 to capture searches from all countries, Transpose countries-values to make a quick bar chart)


