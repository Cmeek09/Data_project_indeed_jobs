As a recent college grad I think my student not already landing a role look to see where the best opporunities for jobs are, the going pay rate if given and base their decisions from here.  This may even be some many do prior to graduating I recommend if you're interested taking a look and see if a certain 

The goal of this data project is to get the general feel for software jobs and their respective locationa and pay.  The intention is to see if the job postings from Indeed.com, colect the data and analzye the results.

Initially, the idea was to try and get this to work with APIs provided from RapidAPIs, and while there is a free tier, you need to have paid access to make enough calls to collect say a meaningful amount of data.  However, there were a few hundred jobs I could pull from starting at this point.

This lead to using selenium as a means to scrape data from the site, I found a source I accredited for the code, but modified it to fit my needs.

The main challenges in the project were getting the data, finding features or observations consistent enough to be able to further analzye and hopefully pull out some interesting information from.  This includes cleaning the data up as the text from indeed is all over the place, generating new columns to categorize the job types into more meaningful metrics to analyze as well as stripping the pay estimates from strings to numbers and averaging the pay out to then fill in the data from after that.


## working dashboard from Tableau

https://public.tableau.com/app/profile/connor.meek/viz/jobsonindeed/Dashboard1?publish=yes

