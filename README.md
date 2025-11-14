# Impact-of-Social-Media-on-Digital-Asset-Markets-Sentiment-Analaysis


<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![NLTK](https://img.shields.io/badge/NLTK-Natural%20Language%20Toolkit-green?style=for-the-badge)
![VADER](https://img.shields.io/badge/VADER-Sentiment%20Analysis-blue?style=for-the-badge)
![Twitter API](https://img.shields.io/badge/Twitter%20API-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)

**A comprehensive sentiment analysis study examining public perception of NFT markets through social media data**

[View Full Report](#) • [Research Paper]**Link to Paper:** [Impact of Social Media on Digital Asset Markets Report](https://raw.githubusercontent.com/pooja-singh702/Impact-of-Social-Media-on-Digital-Asset-Markets-Sentiment-Analaysis/main/Impact%20of%20Social%20Media%20on%20Digital%20Asset%20Markets%20(1).docx)


</div>

---

## Table of Contents

- [Abstract](#abstract)
- [Research Questions](#research-questions)
- [Methodology](#methodology)
  - [Data Collection](#data-collection)
  - [Analysis Approach](#analysis-approach)
- [Key Findings](#key-findings)
- [Technologies & Tools](#technologies--tools)
- [Results & Discussion](#results--discussion)
- [Future Work](#future-work)
- [Citation](#citation)
- [Author](#author)

---

## Abstract

Public interest in digital assets (e.g., Non-Fungible Tokens) have exploded in the past year and have gained acceptance among investors as an investment vehicle and among the creative community as an innovative way of creating and monetizing artwork. Despite its popularity, very little scholarly research has been done to understand these digital asset markets.

**This research study has two primary objectives:**

1. **Understanding user perception** of Non-Fungible Token (NFT) markets as evidenced by social media posts
2. **Analyzing temporal trends** in how this user perception has changed over time

> **Key Insight**: Users maintain an overall positive perception of digital asset markets despite recent market turmoil. Positive sentiment shows an upward trend over the past five months while negative sentiment remains largely low and constant.

---

## Research Questions

This study addresses the following research questions:

1. **What is the overall public sentiment about NFTs** as evidenced by social media posts?
2. **How does this sentiment change over time?**

---

## Methodology

### Data Collection

- **Platform**: Twitter (via Twitter API)
- **Keywords**: "NFT"
- **Time Period**: February 2022 - June 2022 (5 months)
- **Dataset Size**: 3,445 cleaned tweets after removing duplicates and retweets

### Analysis Approach

**Natural Language Processing Technique**: Sentiment Analysis

**Tools & Libraries**:
- **NLTK (Natural Language Toolkit)**: Text tokenization and preprocessing
- **VADER (Valence Aware Dictionary and sEntiment Reasoner)**: Social media-specific sentiment lexicon
- **Python**: Primary programming language for data processing and analysis

**Data Preprocessing Steps**:
1. Tokenization using NLTK
2. Removal of punctuation, numbers, and stop words
3. Filtering of emojis, hyperlinks, and non-sentiment words
4. Application of VADER sentiment scoring

**Why Lexicon-Based Approach?**
- Eliminates researcher subjectivity once dictionary is selected
- Scales efficiently to large samples
- Publicly available dictionaries ensure reproducibility
- VADER specifically tuned for social media language

---

## Key Findings

### Overall Sentiment Distribution

- **Positive sentiment** tweets significantly outnumber negative sentiment tweets
- Overall positive perception of NFT markets among Twitter users

### Temporal Trends 

- **Negative sentiment**: Remained small and relatively constant (Feb-May), with a spike in June
- **Positive sentiment**: Shows consistent upward trend from February, with sharp increase in June
- **Notable observation**: Despite negative news coverage and market turmoil, overall sentiment remained positive

### June Spike Analysis

The simultaneous spikes in both positive and negative sentiment in June correspond to:
- Increased activity in NFT and cryptocurrency markets
- Greater media coverage of digital assets
- **Positive sentiment spike exceeded negative**, maintaining overall positive perception

---

## Technologies & Tools

| Technology | Purpose | Details |
|------------|---------|---------|
| **Python** | Primary Language | Data processing, analysis, and visualization |
| **NLTK** | NLP Toolkit | Text tokenization, preprocessing, linguistic analysis |
| **VADER** | Sentiment Analysis | Social media-specific sentiment scoring |
| **Twitter API** | Data Collection | Fetching tweets with NFT-related keywords |
| **Pandas** | Data Management | Data cleaning, manipulation, and analysis |
| **Tableau/Matplotlib/Seaborn** | Visualization | Creating trend charts and sentiment distributions |

### Core Competencies Demonstrated

- Advanced Python programming
- Natural Language Processing (NLP)
- Data preprocessing and cleaning
- Statistical analysis and trend identification
- Sentiment analysis using lexicon-based approaches
- API integration (Twitter API)
- Data visualization and insight communication

---

## Results & Discussion

### Positive Insights

Despite recent market turmoil and negative media coverage, **Twitter users interested in NFT markets maintain a predominantly positive sentiment**. This suggests:

- Resilient community belief in digital assets
- Distinction between media narrative and user perception
- Strong foundation of engaged, optimistic participants

### Market Context

The analysis captured a critical period (February-June 2022) that included:
- Market volatility in cryptocurrency sector
- Various NFT project launches and high-profile sales
- Evolving regulatory discussions
- Mainstream media attention to digital assets

---

## Future Work & Limitations

### Current Limitations

- **Dataset Size**: 5-month window (expanding to 18 months in progress)

- **Platform Scope**: Limited to Twitter (future: multi-platform analysis)

### Ongoing Extensions

1. **Influencer Impact Analysis**: Examining how celebrities and social media influencers affect NFT markets
2. **Network Analysis**: Understanding growth and spread patterns using social network analysis
3. **Predictive Modeling**: Correlating sentiment with digital asset prices to build prediction models
4. **Cross-Platform Studies**: Expanding to Reddit, Discord, and other social platforms
5. **Real-Time Monitoring**: Developing live sentiment tracking dashboard

---


```


