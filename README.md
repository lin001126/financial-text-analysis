# ***Financial Text Analysis*** 

This project is centered on data preprocessing and analysis, aimed at refining a dataset with over a million news articles by removing non-relevant content. The goal is to identify and exclude articles that do not mention China A-share listed companies, employing both rule-based and similarity-based methods for enhanced precision. It incorporates text vectorization techniques and the use of pre-trained BERT models for increased accuracy. Structured into three main tasks, it starts with filtering out irrelevant news, followed by sentiment analysis to determine news impact on stock market prices, and culminates in using knowledge graphs to explore various company relationships.



**Data Preprocessing - Noise Removal**  
 Removed irrelevant news from the dataset and employed both rule-based and similarity-based methods for effective filtering, achieving a 47.24% filtering efficiency. 



**Sentiment Polarity Analysis**  
Selected and tested model to analyze the sentiment polarity of each news.



**Knowledge-Driven Financial Analysis**  
Constructed a knowledge graph using  Neo4j database to analyze various company relationships, identifying the implicit positive or negative impact of each news on the companies。



