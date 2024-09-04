# Google-Search-Analysis
Let us do Google search analysis with the help of python based on search queries.

Pytrends is an unofficial Google trends API used in python. It helps to analyze and list out the most popular Google search results on a specific topic or a subject, based on different regions and languages.

To use this API, you first need to install it on your systems. You can easily install it using the command pip install pytrends.

# pip install pytrends

# Build Payload
Now, we will be creating a dataframe of the top 10 countries that search for the term “CLOUD COMPUTING“. For this, we will be using the method build_payload, which allows storing a list of keywords that you want to search. In this, you can also specify the timeframe and the category to query the data from. 

# Interest Over Time
The interest_over_time() method, returns the historical, indexed data for when the specified keyword was most searched according to the timeframe mentioned in the build payload method.

# Interest By Region
Next is the interest_by_region method, this will let you know the performance of the keyword per region. It will show results on a scale of 0-100, where 100 indicates the country with the most search and 0 indicates with least search or not enough data. 

# Top Charts
Using this method, we can get the top trending searches yearly. So, let us check what were the searches trending in the year 2020.

# Keyword Suggestions
The suggestions() method, will help you to explore what the world is searching for. It returns a list of additional suggested keywords that can be used to filter a trending search on Google.
