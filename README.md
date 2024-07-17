# Reddit - Finance Posts

## Background
This project explores the intersection of behavioral science and social media analytics, specifically utilizing data scraped from Reddit. Our primary objective is to assess whether sentiment and other data gathered from Reddit posts can serve as a temperature gauge for financial markets. By selecting and analyzing relevant forums, we aim to evaluate their potential as indicators of market psychology and their effectiveness as predictors for stock market trends in the US.

## Behavioral science:
1)	Market psychology - https://www.investopedia.com/terms/m/marketpsychology.asp#:~:text=Understanding%20Market%20Psychology,-Market%20psychology%20is&text=The%20prices%20of%20individual%20stocks,to%20markets'%20overall%20market%20psychology.

The Impact of Human Behavior and Psychology on Stock Market: https://ijrpr.com/uploads/V3ISSUE6/IJRPR4875.pdf

2) Behavioral Finance

-	cognitive biases such as confirmation bias
-	data driven insights: 
o	historical patterns: patterns, event impact
o	sentiment analysis: gauge mood of investors through social media, news and surveys
o	Behavioral metrics

## Data source: Reddit
There are over 50million logged-in users on reddit (Statista)
Reddit users are predominantly male, young, white, and well-educated: demographics 

## Reddit Dataset metrics:
To understand how popular a post is on Reddit, we focus on the following metrics:
1.	Upvote Ratio: This is a measure of the percentage of upvotes versus downvotes a post receives. A higher upvote ratio indicates that the post is well-received by the community.
2.	Score: This is the net score of the post, calculated as the number of upvotes minus the number of downvotes. It provides a direct measure of how popular the post is.
3.	Total Awards Received: This indicates how many awards the post has received from other users. Awards are typically given for posts that users find particularly valuable or noteworthy.
4.	Num Comments: The number of comments can indicate the level of engagement and discussion the post has generated.
5.	Num Crossposts: The number of times the post has been crossposted to other subreddits can indicate its relevance and popularity across different communities.

Secondary metrics kept in dataset as they might also be valuable:
5.	Gilded: Indicates how many times the post has received Reddit Gold, a premium award.
6.	Is Video: Indicates if the post contains a video, which can be more engaging and thus popular.
7.	Is Original Content: Indicates if the post is original content, which can sometimes lead to higher engagement if the community values original posts.

Less valuable for measuring popularity:
8.	Pinned: Indicates if the post is pinned by moderators, which doesn't necessarily reflect popularity but rather importance or relevance as determined by the moderators.
9.	Archived: Indicates if the post is archived and no longer open for new comments, which is more about the post's status than its popularity.
10.	Locked: Indicates if the post is locked, preventing further comments. This can happen for various reasons, not necessarily related to popularity.
11.	Removed: Indicates if the post has been removed by moderators or the user, which means it’s not visible anymore and cannot be assessed for popularity.
12.	Deleted: Similar to removed, indicates the post has been deleted.
13.	Is Self: Indicates if the post is a self-post (text post) rather than a link post. This is more about the type of content rather than its popularity.

By focusing on the primary metrics (upvote ratio, score, total awards received, number of comments, and number of cross posts), we can get a good sense of how popular a post is on Reddit, which we believe would indicate how relevant it is on the subject and how much it could be influential in market psychology.


