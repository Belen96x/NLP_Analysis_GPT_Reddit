# What People Say about ChatGPT: An Analysis of Reddit Comments

**Authors:**  
- (Juliana Planas)[https://github.com/julianaplanas]
- (Belén Saavedra)[https://github.com/Belen96x]

**Affiliation:**  
University of the Basque Country – Faculty of Informatics

## Overview

This project explores how Reddit users talk about ChatGPT in the r/ChatGPT subreddit. We apply natural language processing techniques to answer:

1. **What are the main topics of discussion** in comments about ChatGPT?  
2. **Which named entities** (model names, companies, regions) appear most frequently in each topic?  
3. **How do users express sentiment** (positive, negative, neutral) around different topics?

## Installation

1. **Clone the repo**  
   ```bash
   git clone https://github.com/Belen96x/NLP_Analysis_GPT_Reddit.git
   cd NLP_Analysis_GPT_Reddit

## Usage

Run the cells in order:

1. Topic Modeling (topic_modelling.ipynb)
Fit an LDA model to discover clusters of discussion topics.

2. Named Entity Recognition (NER_detection.ipynb)
Extract and tally entities within each topic cluster.

3. Sentiment Analysis (Sentiment_analysis.ipynb)
Score sentiment per topic using a rule-based classifier.

Inspect the outputs:
- Topic keywords and example comments
- Entity frequency tables and barplots
- Sentiment distribution charts