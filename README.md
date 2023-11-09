# data-analytics-projects 📊
You may find here some of my data analysis projects where I answer different questions through data analysis and statistics. I also publish business intelligence dashboards.

Common tools uses: 
  - Jupyter notebook, VS Code
  - PowerBI, Python, R, SQL
  - Selenium, BeautifulSoup

# Projects outline: 

## 1- [Trends in AI YouTube Videos](https://github.com/AsmaaMHadir/data-analytics-projects/tree/main/Youtube%20Channels%20Analysis/notebooks): How did the content trends for AI, Data Science, and Machine Learning Youtube channels change within the last 6 years? 

### 1. [Introduction](#introduction)
### 2. [Analysis Topics](#analysis-topic)
### 3. [Method](#method)
### 4. [Dataset](#dataset)
### 5. [Visualizations](#visualization)
### 6. [Text Mining](#text-mining)
### 7. [Conclusions](#conclusions)



## Trends in AI/ML YouTube Videos
### Introduction
The last couple of years had been marked by an anwavering advancement in the field of Machine Learning, especially in Natural Language Processing with LLMs and generative AI dominating the public discussion. With the topic's popularity came a rush into "open-sourcing" the knowledge needed to be a practitioned in the Data Science and ML industries to the public. From tutorials and crash courses in Deep Learning frameworks and introducing data pre-processing concepts to research paper readings, Youtube became the biggest learning hub for anyone who wants to learn about building and using AI models for their own purposes or develop practical skills to become a data and AI professional. 
These Youtube channels would typically provide tutorials or guided projects sharing knowledge about frameworks, tools, languages, architectures etc. as well as advice and insights about the applied Machine Leatrning and Data Scientist profession. The dataset excludes specialized channels that provide content in a specific area such as data analysis.

### Analysis Topic?
In this project, I collect data about some of the biggest and active Youtube channels that provide educational content about Machine Learning and Data Science in order to extract insights about which topics had been popular within the last 6 years from 2018 arriving to 2023. The channels in question are:

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


### Method

Using Python and the Youtube API, I built a dataset of YouTube videos composed of over 6000 rows and 6 columns. 
Link for your own analysis: [Dataset](https://www.kaggle.com/datasets/asmaahadir/aiml-youtube-channels-content-2018-2019/data)

## Dataset 

<img width="585" alt="dataset" src="https://github.com/AsmaaMHadir/data-analytics-projects/assets/46932156/e4b37db7-2140-4f3d-bf03-8cab465492da">

Top 10 most viewed videos in the dataset

<img width="625" alt="top" src="https://github.com/AsmaaMHadir/data-analytics-projects/assets/46932156/3a343600-ed2a-42c7-b700-f304935c2128">

## Visualizations

- Number of views per channel: 
![ChannelsViewCount](https://github.com/AsmaaMHadir/data-analytics-projects/assets/46932156/1478fac2-ddec-4040-adb5-1ec3a6c40c11)

- Number of subscribers per channel: 
![ChannelSubsCount](https://github.com/AsmaaMHadir/data-analytics-projects/assets/46932156/550a3ee9-5e23-450e-90d7-8f6f8b33c1aa)

- Number of uploaded videos per channel: 
![ChannelsVideosCount](https://github.com/AsmaaMHadir/data-analytics-projects/assets/46932156/67defc5e-71b6-4343-b199-b9c84d12b306)

## Text Mining

### Most popular topics among the videos using BERTopic transformer

![topics](https://github.com/AsmaaMHadir/data-analytics-projects/assets/46932156/c5fa3665-f4b9-4f45-85e2-e987e0c7df4e)


### Videos' titles word cloud plot

![wordCloud](https://github.com/AsmaaMHadir/data-analytics-projects/assets/46932156/b81b2d0e-fb19-490c-b96b-79c70778e021)


### Terms frequency in videos' titles

![newplot](https://github.com/AsmaaMHadir/data-analytics-projects/assets/46932156/b3769156-5678-4ca2-8780-903bed6ed0f9)

### Year by year word cloud plot

![WC_years_grid](https://github.com/AsmaaMHadir/data-analytics-projects/assets/46932156/4553b4c3-8f66-4571-ab8a-faf40fe2d142)

### Conclusions

- The grid showcasing topics as well as th word cloud visuals shows that YouTube content in the educational AI sphere focuses on machine learning algirithms, Python learning, hardware awareness ( GPUs), popular frameworks such as Tensorflow and Kera and recently content about MLOps and machine learning models in production became prevalent. This could be explained by the surge to building customized and ready to use products reliant on machine learning models, and public's access to resources to train new models or fine-tune pre-trained ones.
  
- 2018: learners are being introduced to neural networks and deep learning overall as well as the potential of Python language in this area.
- 2019: Data science gains momentum among the AI learners community. IBM Watson is also among the most discussed topics.
- 2020 - 2021: content focused on being job ready for data science and machine learning engineering positions increases in popularity through interview prep and portfolio building video content.
- 2022: MLOps enters the scene as the last couple of years lead to an amassed enormous rich knowledge about building models and incorporating them in production software became a widely discussed topic ( AI is more accessible and open source than ever!).
- 2023: Most content is around ChatGPT and LLMs overall, stable diffusion, and the PyTorch framework. 
