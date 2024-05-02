# NLP-Based Sentiment Dissection of Apple Vision Pro Reception on Marques Brownlee’s YouTube Channel.
![image](https://github.com/ashleySimiyu/Capstone-Project/assets/141912273/8c100e2d-e343-4f56-99b8-9c1c247f0fec)

## Business Understanding
### Project Overview
The Apple Vision Pro, a cutting-edge product in the realm of augmented reality, has garnered significant attention since its release. As a prominent influencer in the tech community, Marques Brownlee's reviews on YouTube significantly impact consumer perceptions and purchasing decisions. Given this influence, there's a substantial interest from Apple’s product development and marketing teams to understand public sentiment as expressed in the comments on these review videos.

### Business Problem
The project aims to analyze viewer comments on Marques Brownlee's YouTube channel related to the Apple Vision Pro. By using Natural Language Processing (NLP) techniques, the project seeks to understand the sentiments expressed in the comments and identify whether viewers are inclined towards purchasing the product. The insights gained from this analysis will help the Product Development Team at Apple assess the reception of the Apple Vision Pro among Marques Brownlee's audience

### Objectives
Our main objective of this study is to analyze viewer sentiments in comments on Marques Brownlee’s YouTube videos reviewing the Apple Vision Pro product.
  * Other Objectives are:
1. Purchase Intent Analysis: Determine the likelihood of viewers purchasing the Apple Vision Pro based on their comments.
2. Insights Generation: Provide actionable insights to the Product Development Team at Apple regarding the reception of the Apple Vision Pro among Marques Brownlee's viewers.
3. Report Preparation: Create a detailed report summarizing the findings and recommendations for further action.
   
**The primary stakeholders are the product development team, marketing team, and strategic decision-makers at Apple.**

### Research Questions
1. What are the top 10 viewed videos on Marques Brownlee's Channel?
2. Can sentiments expressed in comments predict a viewer’s likelihood to purchase the Apple Vision Pro? (based on positive, negative sentiments).
3. How are sentiments distributed across comments on Marques Brownlee's YouTube videos reviewing the Apple Vision Pro?
4. Leveraging on the historical data gathered can Apple Vision Pro Production team improve their marketing strategy?
5. What are the predominant themes?key words and sentiments expressed in viewer comments on Marques Brownlee’s YouTube videos?
   
## Data Understanding
The data for this project consists of comments from Marques Brownlee's YouTube channel related to the Apple Vision Pro review videos. The comments are collected using the **YouTube Data API**, which allows access to public comments on YouTube videos. Each comment is associated with metadata such as the commenter's username, comment timestamp, comment text, and number of likes. The comments provide insights into viewers' opinions, feedback, and preferences regarding the Apple Vision Pro product. The comments will be preprocessed to remove special characters, stopwords, tokenize the text, lemmatize and perform sentiment analysis using NLP techniques.
* We first install the Python packages using pip
> %pip install --upgrade google-api-python-client
> %!pip install textblob
* We then Set up our YouTube Data API
![Screenshot (43)](https://github.com/ashleySimiyu/Capstone-Project/assets/141912273/b5a0c23f-8ffb-4a80-bf1f-0a62a1182f5c)
### Data Structure
  * Data Format: CSV
  * Number of rows = 59,274
  * Number ofcolumns = 4
###  Data Features 
  * Comment Text
  * Likes (Number of likes on the comment)
  * Author (The username of the author that made a comment)
  * Timestamp (Time the comment was posted)
### Data Types
  * Comment text: String
  * Likes: Integer
  * Author: String
  * Timestamp: DateTime

## Modelling 
We are using Natural Language Processing (NLP) techniques to analyze the sentiments expressed in the comments.
These are the results:
### Textblob Model

## Conclusion


### Key Findings

### Recommendations
