# XML/JSON Data Processing Project

**Course**: ITC5202 - XML/JSON Data Processing  
**Group**: Group 14  
**Members**: Kartik Nain, Dhruvi Rajput  
**Submission Date**: 8/8/2022  

## Table of Contents

1. [Step 1: Explore Reddit API - Search Functionality](#step-1-explore-reddit-api---search-functionality)
2. [Step 2: Explore Pushshift API for Comments and Subreddits](#step-2-explore-pushshift-api-for-comments-and-subreddits)
3. [Step 3: Develop Subreddit Search and Display App](#step-3-develop-subreddit-search-and-display-app)
4. [Step 4: Design Reddit Search App with User Options](#step-4-design-reddit-search-app-with-user-options)
5. [Step 5: Display XML Reddit Data](#step-5-display-xml-reddit-data)

## Step 1: Explore Reddit API - Search Functionality

The difference between the following Reddit API URLs is as follows:
- `https://www.reddit.com/search?q=ajax`: Searches recent comments for the word "ajax" in the comment body (case-insensitive). API sorts by most recent comments by default.
- `https://www.reddit.com/search.json?q=ajax`: Similar to the first link, but returns data in JSON format.

**Web Application Details**:
- Develop a web app to search Reddit articles based on user input.
- Display article title, author, subreddit, URL, score, and flair in a proper format.
- Implement sorting based on title and display 100 records.

## Step 2: Explore Pushshift API for Comments and Subreddits

**API URL**: `https://api.pushshift.io/reddit/search/comment/?q=science`

**Web Application Details**:
- Develop a web app to search Reddit articles using Pushshift API.
- Display article body, author, subreddit, URL, score, and flair in a proper format.
- Implement sorting based on title and display 100 records.

## Step 3: Develop Subreddit Search and Display App

**Web Application Details**:
- Get user input for a subreddit.
- Display top 3 matching subreddits.
- For each subreddit, display top 3 posts with authors, scores, related images, and flair.
- Display top 3 comments for each post, ordered by score or date.

## Step 4: Design Reddit Search App with User Options

**Web Application Details**:
- Allow users to search on Reddit, choose the number of records, and the Reddit-sort attribute.
- Display article title or summary, picture, score, subreddit, and a "Read More" link.
- Utilize JavaScript Interpolation/Variable substitution for API call URLs.
- Apply proper data validation and error handling on user inputs and API calls.

## Step 5: Display XML Reddit Data

**Web Application Details**:
- Use the attached XML file containing subreddit data in RSS/XML format.
- Develop a JavaScript program to display records in a proper format.

---

This documentation outlines the steps and details of our XML/JSON Data Processing project. Each step involves exploring, developing, and implementing features to interact with Reddit API data. From searching and sorting to displaying results and handling user inputs, our project covers a range of functionalities related to data processing and presentation.
