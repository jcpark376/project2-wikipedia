# Predicting Wikipedia Language Counts per English Article
Wikipedia is one of the most visited websites in the world, ranking at #13 in 2020. Since its launch in 2001, it has drastically changed the landscape of encyclopedias and referencing. It is available in almost 300 languages, with the English Wikipedia being the most prominent, with over 6 million articles and counting.

Many articles have counterparts/translations in other languages. For example, the English Wikipedia [article of the late Steve Jobs](https://en.wikipedia.org/wiki/Steve_Jobs) is available in 153 other languages. In this project, I sought to predict the number of non-English language Wikipedias that has counterparts to a given English language article through linear regression modeling and natural language processing. One may be able to collect a number of info through such effors. For example, one may be able to narrow down list of articles that may be in need of additional translation efforts.

# Organization
This repository is organized into four parts.
1. The [WebScraper folder](https://github.com/jcpark376/project2-wikipedia/tree/master/WebScraper), which contains the [code](https://github.com/jcpark376/project2-wikipedia/blob/master/WebScraper/webscraper.ipynb) used to scrape Wikipedia html documents using the Random Article feature on Wikipedia. There is also [code](https://github.com/jcpark376/project2-wikipedia/blob/master/WebScraper/articledateget.ipynb) to collect the date of a given article's first creation.

2. The [Models folder](https://github.com/jcpark376/project2-wikipedia/tree/master/Models). There are three interrelated (but meant to be run sequentially) approaches and their corresponding code.
    * Modeling using 10 select features.
        * [code](https://github.com/jcpark376/project2-wikipedia/blob/master/Models/TenFeatures/features2.ipynb)
    * Modeling using Natural Language Processing (NLP).
        * [code for data_extracting](https://github.com/jcpark376/project2-wikipedia/blob/master/Models/NLP/nlp_dataextract.ipynb)
        * [code for modeling](https://github.com/jcpark376/project2-wikipedia/blob/master/Models/NLP/nlp_model.ipynb)
    * A combination of the two approaches.
        * [code](https://github.com/jcpark376/project2-wikipedia/blob/master/Models/FinalModel/final_model.ipynb)

3. The [Conclusions folder](https://github.com/jcpark376/project2-wikipedia/tree/master/Conclusions). This contains the [presentation](https://github.com/jcpark376/project2-wikipedia/blob/master/Conclusions/Presentation-Revised.pdf) that summarizes the findings as well as [select figures](https://github.com/jcpark376/project2-wikipedia/tree/master/Conclusions/FIgures). 

4. The [wikiarticles folder](https://github.com/jcpark376/project2-wikipedia/tree/master/wikiarticles), which has the html files that the WebScraper module scraped.