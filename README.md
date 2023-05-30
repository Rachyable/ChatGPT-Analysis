# ChatGPT-Analysis
Exploring AI's impact, Chat GPT consistently rises above the rest. Unveiling public opinion and Chat GPT's benefits, this project sheds light on Chat GPT's role in shaping the future of AI-powered conversational technologies, and from conversations on twitter from Jan - March 2023
![flashcloud-intelligence-21](https://github.com/Rachyable/ChatGPT-Analysis/assets/29276051/aa7cd36a-9e8f-45d2-8be2-fd2b4951fa84)

##DataSet And Data Collection.
This dataset was gotten from Kaggle. It consists of tweets from 4th January to 29th March 2023 of ChatGPT on Twitter. The columns Consist of Date, Id, content, username, like_count, retweet_count

#Importing the data
The dataset was imported into Power query on Microsoft Power Bi, I created a copy of the data in case I need to refer back to the original copy.  Here is an overview of what the dataset looks like
 ![Columns](https://github.com/Rachyable/ChatGPT-Analysis/assets/29276051/32bee128-59d2-41c2-838a-54a0a856d80f)


##Data Processing
I Check for missing values and removed the null values from each column. 
The datetime column was separated using a delimiter, while the time column was removed from the dataset since we will not be needing the time in the analysis. So, the date column was transformed into a usable form
A conditional Column was added from the content column to define topics that contain AI, ChatGPT, Elon Musk, Open Ai, Google, Where Sama, Microsoft, Youtube, Bill Gates, LinkedIn, Bing, and Mid Journey are grouped as others. 
        ![Date column](https://github.com/Rachyable/ChatGPT-Analysis/assets/29276051/7c2c3bfa-d212-403c-b4ad-966cf5141086)
 To this ![Date and Time](https://github.com/Rachyable/ChatGPT-Analysis/assets/29276051/5202e05b-9c6a-499e-986c-316df85851f1)
  
#Data Cleaning
This step involves removing inconsistencies in the dataset, such as duplicates, corrupted, and incorrectly formatted data within the dataset. Here I worked more on the Content column where I used the Find and Replace to replace wrongly spelt words. I replaced words such as chatGpT, chatgpt, ChaT gpt, chat Gpt, with ChatGPT. Also ai, Ai, and aI was replaced with AI, elonMusk, Elonmusk, Elon musk was replaced with Elon Musk, and google was replaced with Google. This was done using Ctrl H.
Also, Multiple spaced data was removed, and all irrelevant information, punctuations and stop word was removed from the Content column to ensure I work with a clean dataset. Duplicates were removed as well this is necessary because there’s a need to focus on unique insights and reduce the impact of noise or repeated content.
      ![Content](https://github.com/Rachyable/ChatGPT-Analysis/assets/29276051/371c8b44-0701-4fd2-a6f0-b0856fd883cd)
And This  ![Stopwords](https://github.com/Rachyable/ChatGPT-Analysis/assets/29276051/1fe8619f-a6e2-4493-9ce3-2eaa443020e6)

##Exploratory Data Analysis

The cleaned dataset was analyzed creating visuals for each question asked.
Trend analysis was also performed using a Line chart to see the trend of tweets over time. From this analysis, it was discovered that tweets on AI increasing each passing month. The Counts of tweets in February increased continuously in regards to this topic, this shows that more people keep talking and getting awareness on the Topic of OpenAI daily.
![Trend of tweet](https://github.com/Rachyable/ChatGPT-Analysis/assets/29276051/60db48f3-a3bb-4be3-9077-4daa12042a99)
 

In this analysis, the Top 10 most influential users were also seen by the counts of likes and retweets. Users who tweeted most about Open AI include DataChaz with 122714 likes, MostCr1Tikal with 64094 likes, Johnvianny with 63876 likes, rgay with 44940 likes, aaronsiim with 42934 likes, Lexfridman with 40289 likes, writtingtoriches with 39425 likes, kevinschawinski with 38320 likes, FirstWeekHQ with 33114 likes, ProudFede with 28049 likes.
![Top 10 Influencers](https://github.com/Rachyable/ChatGPT-Analysis/assets/29276051/4b20e321-3058-4a2e-a935-b6a26652f5be)

                                                  
Top 5 Topics that were mostly discussed are ChatGpt, OpenAi, Elon Musk, Google, and Others (This includes LinkedIn, Microsoft, Youtube, Bing, Mid Journey, and Bill Gates). The insights gotten from here is that topics on ChatGPT were mostly discussed with people asking questions on ChatGPT and getting prompt answers. This shows how ChatGPT was able to help people with complex questions by providing intelligent answers.
![Topics discussed](https://github.com/Rachyable/ChatGPT-Analysis/assets/29276051/218e116e-4d56-4050-a244-a20d2308e7af)

In this analysis, We can also see the percentage increase in the content tweeted for various months, this was completed using a doughnut chat.
![Percentage of Content](https://github.com/Rachyable/ChatGPT-Analysis/assets/29276051/e349a623-d5a1-4cdd-a78a-e3938d13f326)

In this analysis, we also got the total tweets, Likes, and retweets, and a slicer was added to interact with the dashboard to see what happens each month.
![Cards](https://github.com/Rachyable/ChatGPT-Analysis/assets/29276051/ad179506-85d4-4967-b648-61fd2e036633)
 

Lastly, we are able to tell the most frequent word that was used in the tweet using Word Cloud. A word cloud image was generated and it was discovered that ChatGPT and AI were mostly mentioned in the overall tweet.  
![Frequent Words used](https://github.com/Rachyable/ChatGPT-Analysis/assets/29276051/e4b057b8-125b-4aad-b67f-54a0dedf7e8b)

 
Here is a single glance at the data visualized on this dashboard
![Dashboard](https://github.com/Rachyable/ChatGPT-Analysis/assets/29276051/eaa388e3-7dd3-4c1d-8c70-11717d22a1f4)

Thank You.


 

