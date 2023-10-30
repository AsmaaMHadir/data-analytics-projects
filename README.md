# data-analytics-projects 📊
You may find here some of my data analysis projects where I answer different questions through data analysis and statistics. I also publish business intelligence dashboards.

Tools I use: 
  - Jupyter notebook, VS Code to write my code
  - PowerBI for visualization and data modelling.
  - SQL for data cleansing.
  - Python for multi-purpose data wrangling and analysis ( Matplotlib, seaborn, Pandas, Numpy )
  - Selenium, BeautifulSoup for data scraping and automation

# Projects outline: 

## 1- [Trends in AI Youtube Videos](https://github.com/AsmaaMHadir/data-analytics-projects/tree/main/Youtube%20Channels%20Analysis/notebooks): How did the content trends for AI, Data Science, and Machine Learning Youtube channels change within the last 5 years? 

### Introduction
The last couple of years had been marked by an anwavering advancement in the field of Machine Learning, especially in Natural Language Processing with LLMs and generative AI dominating the public discussion. With the topic's popularity came a rush into "open-sourcing" the knowledge needed to be a practitioned in the Data Science and ML industries to the public. From tutorials and crash courses in Deep Learning frameworks and introducing data pre-processing concepts to research paper readings, Youtube became the biggest learning hub for anyone who wants to learn about building and using AI models for their own purposes or develop practical skills to become a data and AI professional. 
These Youtube channels would typically provide tutorials or guided projects sharing knowledge about frameworks, tools, languages, architectures etc. as well as advice and insights about the applied Machine Leatrning and Data Scientist profession. The dataset excludes specialized channels that provide content in a specific area such as data analysis.

### What?
In this project, I collect data about some of the biggest and active Youtube channels that provide educational content about Machine Learning and Data Science in order to extract insights about which topics had been popular within the last 5 years from 2018 arriving to 2023. The channels in question are:

- Krish Naik
- Nicholas Renotte
- Sentdex
- DeepLearningAI
- Artificial Intelligence — All in One
- Siraj Raval
- Jeremy Howard
- Applied AI Course
- Daniel Bourke
- Jeff Heaton
- DeepLearning.TV
- Arxiv Insights

These channels are features in multiple `top AI channels to subscribe to` lists and have seen a big growth in the last couple of years on Youtube. They all have a creation date since or before 2018.

### How?
Using Python and the Youtube API, I built a dataset composed of over 6000 rows and 6 columns storing videos from the most popular 12 AI and Machine Learning channels on youtube (mentioned above). 

- Data Source: Youtube API.
- Data Analysis: Pandas, Numpy.
- Data Visualization: Seaborn, Matplotlib

## Resulting Dataset 

Link for your own analysis :) : [Dataset](https://github.com/AsmaaMHadir/data-analytics-projects/blob/main/Youtube%20Channels%20Analysis/notebooks/AI_ML_YT_Videos.csv)

<img width="585" alt="dataset" src="https://github.com/AsmaaMHadir/data-analytics-projects/assets/46932156/e4b37db7-2140-4f3d-bf03-8cab465492da">

Top 10 most viewed videos in the dataset

<img width="625" alt="top" src="https://github.com/AsmaaMHadir/data-analytics-projects/assets/46932156/3a343600-ed2a-42c7-b700-f304935c2128">

2. Step 2: Data cleansing
3. Step 3: Dataset statistics
  - Number of youtube channels
  - Number of collected videos
  - Average video views
  - Average channel subscription count
4. Step 4: Topic extraction from video titles
5. Step 5: Visualize
