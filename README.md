# Bachelor_Thesis_Gaming
**Reddit Users’ Perception of AI in the Gaming Industry**

# Project Overview
This repository contains the codebase and data analysis for my Bachelor's thesis, which investigates how the gaming community perceives the rapid integration of Artificial Intelligence. Using a dataset of Reddit posts, this research deconstructs public opinion into a tripartite taxonomy: Generative AI (Image Generation), Gameplay AI, and Moderation AI.


The study applies advanced Natural Language Processing (NLP) techniques to bridge the gap between technical AI development and player-centric sentiment.

# Research Objectives
- This project addresses five key research questions:

- Dominance: Identifying which AI use cases lead community discussions.
- Engagement: Analyzing how interaction intensity (upvotes/comments) varies across AI topics.
- Thematic Trends: Extracting core themes using transformer-based topic modeling.
- Sentiment: Measuring the emotional polarity of discussions using lexicon-based analysis.
- Genre Influence: Evaluating how perceptions shift across different game genres (e.g., Shooters vs. RPGs).



# Methodology & Tools
The analytical pipeline is built using Python and consists of the following stages:
- Data Collection: Automated extraction of Reddit data via the PRAW API.
- Sentiment Analysis: Utilizing VADER to interpret social media-specific language and slang.
- Topic Modeling: Implementing BERTopic (SBERT, UMAP, HDBSCAN) for semantic clustering of unstructured text.
- Statistical Analysis: Logarithmic normalization of engagement metrics and OLS regression to model community response.

# Repository File Guide

- **Collect_Post_Reddit_Gaming.ipynb:** Data retrieval and initial labeling.
- **Cleaning_Reddit_Gaming_Thesis1.ipynb:** Text preprocessing, noise removal, and metadata refinement.
- **Final_Reddit_Gaming_(9).ipynb:** Main analysis, including sentiment distributions and BERTopic modeling.

