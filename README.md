# Reddit - Finance Posts

## Collaborators
Carolina Gonzalez\\
Ryan Reuther\\
Clifton Harris\\
Melody Masis

## Background
This project explores the intersection of behavioral science and social media analytics, specifically utilizing data scraped from Reddit. Our primary objective is to assess what makes a post more engaging.

Main metric: Engagement 

We define engagement as upvotes + downvotes (calculated from difference between upvote and score) + Num comments + Num Crossposts

Goal is to create build models that help find highly engagement posts, that can be used by advertisers who are looking to be featured in high engagement reddit posts. 

## Data source: Reddit
There are over 50million logged-in users on reddit (Statista)
Reddit users are predominantly male, young, white, and well-educated: demographics 

## Reddit Dataset metrics:
To understand how popular a post is on Reddit, we focus on the following metrics:
1.	Upvote Ratio: This is a measure of the percentage of upvotes versus downvotes a post receives. A higher upvote ratio indicates that the post is well-received by the community.
2.	Score: The number of upvotes for the submission.
3.	Total Awards Received: This indicates how many awards the post has received from other users. Awards are typically given for posts that users find particularly valuable or noteworthy.
4.	Num Comments: The number of comments can indicate the level of engagement and discussion the post has generated.
5.	Num Crossposts: The number of times the post has been crossposted to other subreddits can indicate its relevance and popularity across different communities.
Secondary metrics kept in dataset as they might also be valuable:
1.	Gilded: Indicates how many times the post has received Reddit Gold, a premium award.
2.	Is Video: Indicates if the post contains a video, which can be more engaging and thus popular.
3.	Is Original Content: Indicates if the post is original content, which can sometimes lead to higher engagement if the community values original posts.
Less valuable for measuring popularity:
1.	Pinned: Indicates if the post is pinned by moderators, which doesn't necessarily reflect popularity but rather importance or relevance as determined by the moderators.
2.	Archived: Indicates if the post is archived and no longer open for new comments, which is more about the post's status than its popularity.
3.	Locked: Indicates if the post is locked, preventing further comments. This can happen for various reasons, not necessarily related to popularity.
4.	Removed: Indicates if the post has been removed by moderators or the user, which means it’s not visible anymore and cannot be assessed for popularity.
5.	Deleted: Similar to removed, indicates the post has been deleted.
6.	selftext (string): The submission selftext on text posts.

By focusing on the primary metrics such as upvote ratio, score, total awards received, number of comments, and number of cross posts, we can get a good sense of how popular a post is on Reddit, which we believe would indicate how relevant it is on the subject and how much it could be influential in market psychology.

## Effective social media posts:

# How To Make It To The Front Page Of Reddit: 
https://everyonesocial.com/blog/how-i-made-it-onto-the-front-page-of-reddit/#:~:text=The%20point%20is%2C%20you%20need,true%20cream%20of%20the%20crop.

Step 1: you need (and this is in very rough terms) ~4,000 upvotes in a period of less than 6hrs to make it to the front page.\\
Step 2: Make sure it’s legit/check your sources\\
Step 3 – Share your post in an appropriate Reddit community\\
Step 3.5 - Think about the size of the community and the time you’re posting

# What makes a social media post effective?
https://www.linkedin.com/pulse/what-makes-social-media-post-effective-/

* Relevance
* Clarity
* Visual Appeal
* Engagement: posts should invite and encourage interaction, feedback and sharing from the audience. Make sure you’re asking questions, offering incentives, creating polls or contests and sharing user-generated content. 
Create a dialogue between you and your audience by responding to comments, acknowledging contributions, thanking followers and building a sense of community.
* timing

# Relevant Research Questions (Next level)

Further fine tuning of Bag of Words model.