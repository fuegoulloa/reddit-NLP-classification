# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 3: TBD

### Problem Statement

How smart can a classification algorithm be?<br>
The human mind can understand and process written language quite efficiently.  If given a random blurb with enough words and context, a person can easily guess what the topic is about with a high degree of accuracy.  Can a classification model mimic such prowess?  This project aims to answer that question.<br>
In order to do so, different classification models will be built and trained to read randomized text from two different subreddits and then predict what topic is being discussed.  Easy for a person, can the machine beat the person?<br>
Various metrics will be used to evaluate each model's performance, with a key focus on misclassification.  The winning model shall be the one with the lowest misclassification rate.


-----

### Datasets

There are four datasets available in the data folder, two for each subreddit. You may consider one dataset as the old version of the data that was collected and the other dataset as the newer version. The initial data scrapes for both subreddits are missing time stamps(`reddit_realestate.csv` and `reddit_travel.csv`), but the textual data contained in them is valuable for this analysis. The newer versions do have timestamps(`reddit--RealEstate.csv` and `reddit--travel.csv`). During the data cleaning process they were combined to preserve the text data. The clean data file is `reddit.csv`, and the features below belong to the dataset's clean version.

|Feature|Type|Description|
|---|---|---|
|**post_title**|_object_|The title of the subreddit post. String format, no units.|
|**post_text**|_object_|The text of the subreddit post. String format, no units.|
|**post_title_length**|_object_|The length of the title. Integer format, unit in characters.|
|**post_title_wc**|_object_|The number of words in the title. Integer format, unit in words.|
|**post_text_length**|_object_|The length of the text. Integer format, unit in characters.|
|**post_text_wc**|_object_|The number of words in the text. Integer format, unit in words.|
|**topic**|_object_|Binary designation to denote whether a post is from the real estate subreddit (0), or the travel subreddit (1). Integer format, no units.|

---

### Summary

Lorem ipsum, dolor sit amet, Latin gave birth to romance languages...


---

### Recommendation

Travel and Real Estate...

---

### Technical Report

Complete and thorough analysis in various Jupyter notebooks are located below:<br> 
[00_reddit_api.ipynb](./code/00_reddit_api.ipynb).<br>
[01_Intro_and_Cleaning.ipynb](./code/01_Intro_and_Cleaning.ipynb).<br>
[02_EDA_and_Visualizations.ipynb](./code/02_EDA_and_Visualizations.ipynb).<br>
[03_Pre-processing_and_Modeling.ipynb](./code/03_Pre-processing_and_Modeling.ipynb).<br>

---


### Presentation

Accompanying presentation in PDF format is located [here](./presentation/).

