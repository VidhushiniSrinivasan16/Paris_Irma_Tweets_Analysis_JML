

This repository contains the dataset for JML research work along with our analysis scripts

**Two large datasets made available**
```
Due to Twitter's restrictions, we are only able to share the tweet ID's and User ID's

The Datasets are available in the dataset folder

1. **Paris Novemer Attack** - Id's(Tweet Id), Profile Id's(user_id) from tweets of Paris Terrorist attacks.
2. **Irma Hurricane Dataset** - Id's(Tweet Id), User Id's(user_id) of the all tweets of hurricane irma collected between Sept 6th 2017 to Sept 12 2017.
```

This repository contains a mixture of codebase written in R (predominantly) and Python.

Please download the tweets with the help of the tweet IDs using this [repository](https://github.com/VidhushiniSrinivasan16/tweets_extraction) in Python or use the rtweet library for R.

**Parsing JSON dataset**
```
parsing_json.Rmd -> Extracting tweets and necessrary fields from JSON.
```

**Scripts**

Initial_analysis_Paris_Tweets.Rmd - Initial Analysis of Paris Tweets ( Total Tweets, Tweets/language, Tweets with/without emojis etc) 

Initial_analysis_Irma_Tweets.Rmd - Initial Analysis of Irma Tweets ( Total Tweets, Tweets/language, Tweets with/without emojis etc) 

ANOVA_Paris.Rmd - ANOVA analysis on Information Theoretic Measures like lexical diversity, perplexity etc on Paris tweets.

ANOVA_Irma.Rmd - ANOVA analysis on Information Theoretic Measures like lexical diversity, perplexity etc on Irma tweets

Paris_Irma_All_Tweets_Combined_Analysis.Rmd - pre-processing tweets and computing various information theoretic measures across different experimentation scenarios (with/without emoji's across different languages, Monolinguals, Bilinguals etc).

Verb_Prep_Mono_Bilinguals.Rmd	, verb_prep_dist_Paris.ipynb, verb_prep_dist_Irma.ipynb	- Verb/preposition distribution analysis on Paris and Irma datasets.

Please contact vsriniv6@uncc.edu if you have any further questions with regards to this project. 
