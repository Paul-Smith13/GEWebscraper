Takes item URLs for the OSRS (2007scape) GE website: https://secure.runescape.com/m=itemdb_oldschool/
Checks that the URL is valid, following the expected prefix and suffix.
If true, then establishes a connection with website, gets the raw HTML as text.
Then uses Regex to look for specific datapoints (e.g. item name, dates, daily prices, etc).
Extracts these datapoints to .txt files.
Extracted data contains daily price (& if available daily volume) data for item in given URL.
Only using individual GE Webpage means reliance on their limited UI.
Extracting data allows user to input this data into a program of their choice for their own use, e.g. analysis, visualisation, etc.
