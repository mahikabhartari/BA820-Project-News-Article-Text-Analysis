# BA820-Project-News-Article-Text-Analysis

**Motivation** 

In the contemporary world, news articles serve as the source of information constantly shaping our understanding of global events, trends, and perspectives. With the ever-expanding volume of news content, navigating through this vast ocean of information can often be confusing. 
This is where our models allow us to conduct several text analysis techniques. The project would allow us to develop personalized recommendation systems for readers. It’s also necessary to distill and prioritize relevant news nowadays.  

**Problem Statement**

The purpose of this project is to segregate various news headlines into specific categories. Newspapers contain a wide variety of topics and understanding these patterns would help both media and readers. Media can now provide better-tailored recommendations, while readers can efficiently browse through their topics of interest. 

**Dataset** 

The dataset comprises 2,688,878 news articles from 27 American publications. It has 10 columns including information on date, year, month, day, author, title, article, URL, section, and publication. The dataset covers the period from Jan 2016 to April 2020.  Various sampling methods like random, random-stratified, year-based, and publication-based can be used for sampling our data and we intend to do stratified-random sampling of our dataset to get a comprehensive view for the initial level of exploration. 

**Datasource** [News Articles Dataset](https://components.one/datasets/all-the-news-2-news-articles-dataset/)

**Proposed Methodology**

**Phase 1: Data Prep**

Explore and handle missing values in 'author' and 'section'.
Tokenize 'article' and 'title'.
Perform RegEx cleaning to remove publisher and author names.
Conduct stemming and clean common words.

**Phase 2: Model Development**

Reduce dimensionality considering word stems.
Apply clustering algorithms like KMeans.
Tune hyperparameters for optimal clusters.

**Phase 3: Validation**

Analyze 'section' proportions.
Evaluate word frequencies in columns.

**Business Relevance**

The project aims to provide categorized news sections. Through this, we improve navigation, increase platform usage, and drive revenue in the evolving media landscape. It also addresses the demand for personalized news experiences in the digital era. Using text analysis, we categorize articles to enhance user satisfaction and engagement. This approach offers curated content aligned with individual preferences, enabling targeted advertising and revenue strategies. 
