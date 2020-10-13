# Predicting Wikipedia Language Counts per English Article
Wikipedia is one of the most visited websites in the world, ranking at #13 in 2020. Since its launch in 2001, it has drastically changed the landscape of encyclopedias and referencing. It is available in almost 300 languages, with the English Wikipedia being the most prominent, with over 6 million articles and counting.

Many articles have counterparts/translations in other languages. For example, the [English Wikipedia article of the late Steve Jobs](https://en.wikipedia.org/wiki/Steve_Jobs) is available in 153 other languages. In this project, I sought to predict the number of non-English language Wikipedias that has counterparts to a given English language article through linear regression modeling and natural language processing. One may be able to collect a number of info through such effors. For example, one may be able to narrow down list of articles that may be in need of additional translation efforts.

# Organization
This repository is organized into four parts.
1. The WebScraper folder, which contains the code used to scrape Wikipedia html documents using the Random Article feature on Wikipedia. There is also code to collect the date of a given article's first creation.
2. The Models folder. There are three interrelated (but meant to be run sequentially) models and their corresponding code.
    * Modeling using 10 select features.
    * Modeling using Natural Language Processing (NLP).
    * A combination of the two approaches.
3. The Conclusions folder. This contains the presentation that summarizes the findings as well as select figures. 
4. The wikiarticles folder, which has the html files that the WebScraper module scraped.