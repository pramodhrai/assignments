# Coding challenge
This page consists of a coding challenge for Data Engineering roles.
You should be able to complete this in 5 hours, though overall deadline is 5 days to buffer life's other commitments :)

## You Should Use AI for This

Use AI to complete the task, while maintaining control / oversight into key technical considerations

# Goals
There are 3 aims for this test

- Learn how to think from a design perspective
- Assess your development ability i.e. code
- Understand your depth of technical experience


# Our assessment criteria
Here are what we look out for 

- Do you write clean code? 
- Do you consistently write unit tests?
- Do you clearly plan for tradeoffs in your solution design
- Do you use source control 

# What to do

- Use any database, data warehouse, datalake (hereby referring to these trio as “database”) of your choice based on your understanding of the problem statement
- Place your test results on a public code repository hosted on Github
- When done, share the Github repository URL to Point of Contact at Raena so he/she can review your work
- No UI is required, you can provide input using a configuration file or command line

# The Task - Get News, Store & Query Service

Create a solution that crawls for articles from any news website, sanitises the response, stores it in a database then makes it available to search via an API.

## Details

- Write an application to crawl 2 online news websites (in future, sources will grow to N where N can be 2 or more) of your choice, using a crawler framework of your choice and build the application.
- The application should sanitise the articles to obtain only specific information - Title, Author, DateTime, Lead Paragraph. You can use tools online to remove content such as advertising and html
- Store the data in a hosted database, including the original url.
- Write an API that provides access to the content.  
- User should be able to search for articles by keywords

# ++ Points
Deploy the solution as a public API using an Amazon EC2 instance
Documentation as a Knowledge Base for future work




