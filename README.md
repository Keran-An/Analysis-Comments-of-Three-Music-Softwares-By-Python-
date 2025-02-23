# Analysis-Comments-of-Three-Music-Softwares-By-Python
The topic of my final project is “Sentiment Analysis of Consumer Behavior Based on Social Media Data".
This is the Research Proposal for this topic.

Listening to the music has become one of the main entertainments for the people. The listeners can enjoy different styles of music or podcast from all over the world by the music software. Spotify, Apple Music (only for Apple users) and YouTube Music are the most popular music software in the world, especially in the U.S. So this project chooses these three software as objects, collects their reviews in the App Store by web scraping. Based on these reviews and rating, this project tries to analysis the sentiment of consumers and gives the conclusion by using word cloud.
There are two parts of the project, one is Web Scraping and the other is Sentiment Analysis. The specific flow chart is as follows:
<img width="1290" alt="截屏2023-09-06 21 10 34" src="https://github.com/iame-uni-bonn/final-project-Keran-An/assets/139079336/26c92243-e555-448a-8cf9-41995278fbf6">
First part is Web Scraping. By installing “app_store_scraper”, 2,000 reviews for each of the software in the App Store are collected, and are saved as files in csv format.(They have been uploaded)
<img width="736" alt="Spotify Web scraping" src="https://github.com/iame-uni-bonn/final-project-Keran-An/assets/139079336/6cebec43-e980-4548-adf5-8189c77fc93f">
Spotify Web scraping
<img width="727" alt="AppleMusic Web scraping" src="https://github.com/iame-uni-bonn/final-project-Keran-An/assets/139079336/3832a88f-0193-4a69-903a-4a2940b5311c">
AppleMusic Web scraping
<img width="737" alt="YouTubeMusic Web scraping" src="https://github.com/iame-uni-bonn/final-project-Keran-An/assets/139079336/5a8e61e9-fca0-4ffb-9f21-87570e4dc7d0">
YouTubeMusic Web scraping

Second part is Sentiment Analysis. Because Take Spotify as an example here, there are also two parts, “Data Visualization based on rating” and “Word Cloud based on reviews”. In the Data Visualization, project gets the number of rating, bar chart of the rating and the total number of positive and negative ratings. In the Word Cloud part, a new function is used to clean the row data, including remove special character, punctuations and stopwords and so on. Then this program classifies the reviews by the rating, uses the WordCloud to generate picture of word cloud by categories.
From the outcome of Data Visualization, it is clearly that Spotify is more popular than other two Apps, while Apple Music receives more negative ratings.
![Rating_Visualization](https://github.com/iame-uni-bonn/final-project-Keran-An/assets/139079336/60ade86e-5754-4856-93b5-11202157d2f6)Rating_Visualization
![Rating_Bar_Chart](https://github.com/iame-uni-bonn/final-project-Keran-An/assets/139079336/b07de132-8f38-4465-b978-cc4052bd128f)Rating_Bar_Chart
![Total_number_of_sentimental_categorie](https://github.com/iame-uni-bonn/final-project-Keran-An/assets/139079336/274f108b-4607-4524-b226-8e7c1c023c56)Total_number_of_sentimental_categorie

For Spotify consumers, “playlist”and “podcast”should be their favorite feature, but for the consumer who don’t buy the premium, they will complain about the “ad”. The YouTube Music users who are satisfied also praise its playlist, they also talk about “download”and “shuffle”. But the unsatisfied reviews mentioned “google music” many times, which was its previous name. However, compared with the previous two software, the keywords of Apple Music are less characteristic. The users more often just mentioned the name of “Apple” and “subscription”. By vertically comparing the three software’s wordcloud, the feature of different software can be found. Spotify has an advantage in playlist, while YouTube Music does better at personalized recommendations. 
![Word_Cloud_for Spotify](https://github.com/iame-uni-bonn/final-project-Keran-An/assets/139079336/efd32a9d-1f9d-4148-8d12-d1b1004f9173)
Word_Cloud_for Spotify
![Word_Cloud_for_AppleMusic](https://github.com/iame-uni-bonn/final-project-Keran-An/assets/139079336/1465dba0-0d33-497c-9b2a-1ad7f4811a2d)
Word_Cloud_for_AppleMusic
![Word_Cloud_for_YouTubeMusic](https://github.com/iame-uni-bonn/final-project-Keran-An/assets/139079336/66576c20-9333-44f5-b439-a6383fc2fdc0)
Word_Cloud_for_YouTubeMusic

As the main music software on the mobile terminal, Spotify, YouTube Music and Apple Music provide users with unique music experience. However, since Apple Music seldom publicly discloses the number of its subscribers, it is difficult to conduct sentiment analysis on consumers to the three software from specific market data. This is a blank for this analysis. Besides, this dataset only focuses on the reviews of Apple users and ignores users of other mobile phone systems, which is a shortcoming for some software. For example, YouTube Music, as the successor of Google Music, will be the choice of more users who use the Google Play. These can be improved by further improvement.
This project is just a small start point for the sentiment analysis of these three music software, which can give a preliminary data analysis result and provide directions for the next business goals of the three software.


References

1. zenUnicorn. App-rating-scraper-with-python. https://github.com/zenUnicorn/App-rating-scraper-with-python

2. Alex. 评论抓取：Python爬取AppStore上的评论内容及星级,突破500条限制. https://blog.csdn.net/sinat_29718177/article/details/119360333 

3. Bilguun Batbold. Python Web Scraping Tutorial. https://medium.com/quick-code/python-web-scraping-tutorial-74ace70e01 

4. Shaumik Daityari. How To Perform Sentiment Analysis in Python 3 Using the Natural Language Toolkit (NLTK). https://www.digitalocean.com/community/tutorials/how-to-perform-sentiment-analysis-in-python-3-using-the-natural-language-toolkit-nltk#step-7-building-and-testing-the-model

5. Federico Pascual. Getting Started with Sentiment Analysis using Python. https://huggingface.co/blog/sentiment-analysis-python

6. Natassha Selvaraj. A Beginner’s Guide to Sentiment Analysis with Python. https://towardsdatascience.com/a-beginners-guide-to-sentiment-analysis-in-python-95e354ea84f6

7. Alvin3411. 数据清洗 -- 4 基于英文的自然语言处理. https://blog.csdn.net/Alvin3411/article/details/113917922

8. DonngZH. 【深度学习、工程实践】深度学习进行情感分析（1）--数据预处理. https://blog.csdn.net/weixin_44750512/article/details/120545477

9. 唐传林. Python生成英文词云图. https://blog.csdn.net/tang_chuanlin/article/details/79794350

10. duoergun0729. 预测yelp美食评分.https://github.com/duoergun0729/nlp/blob/master/%E9%A2%84%E6%B5%8BYelp%E7%BE%8E%E9%A3%9F%E8%AF%84%E5%88%86.md

11. Asia-Lee. NLTK使用方法总结. https://blog.csdn.net/asialee_bird/article/details/85936784

12. Avasla. 【python 报错】NLTK stopword找不到. https://blog.csdn.net/WHYbeHERE/article/details/109115937

13. Kolya Hnatyuk. 2023 年 300 多个基本 Spotify 统计数据. https://marketsplash.com/zh/spotify-stats/








