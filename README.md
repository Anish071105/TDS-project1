# TDS-project1
**An explanation of how I scraped the data** 

Data scrapping done using Python in Google Colab tool. GitHub API is called to fetch requisite data set of Melbourne users with their public repositories. To avoid hitting rate limitation, pagination techniques are handled within the code by dividing API responses and restricting the request to avoid API rate limits.    

**The most interesting and surprising fact you found after analyzing the the data**

After 2020,python is widely used (23.87%) than JavaScript(20.64%) for writing repositories.The "stargazers_count" and "watchers_count" columns have same values, which is not possible since all watchers won't give same star. Having one more repository yields an average of 2.243 additional followers.(upto 400 repos).

**An actionable recommendation for developers based on your analysis**

Focus on learning and using Python, as its a rapidly growing, popular language.Positive correlation between number of followers and repository implies that as repositories increase, users follower count might increase.Developers seeking a license should choose MIT or Apache, as they are the most popular
