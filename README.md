# Kaggle Submission - Amazon Review

This repository contains the coursework for the **Amazon Company Review** project for **Kaggle Compesition Submission**, conducted by the following contributors:

- **Hariharakumar Rathinar**
- **Yadubanshi Pratibha**
- **Onafeso Fiyifoluwa**
- **Sattar Shaikh Eherar**

---

F21AA_TEXTANALYSTICS/
├── data/
│   ├── raw/                # Raw data collected from Reddit
│   └── processed/          # Processed data ready for analysis
├── notebooks/              # Jupyter notebooks for exploratory analysis and experiments
├── src/                    # Source code for data collection, preprocessing, analytics, and modeling
│   ├── Python Code         # Script 
├── reports/                # Generated reports and visualizations
├── docs/                   # Documentation, including the research summary on the history of NLP
├── README.md               # Project overview and instructions
└── requirements.txt        # List of Python dependencies


## Table of Contents

1. [Objectives and Problem Formulation](#objectives-and-problem-formulation)
2. [Learning Outcomes](#learning-outcomes)
3. [Implementation and Requirements](#implementation-and-requirements)
    - [A. Data Collection](#a-data-collection)
    - [B. Data Analysis, Selection, and Labeling](#b-data-analysis-selection-and-labeling)
    - [C. Text Analytics Pipeline](#c-text-analytics-pipeline)
    - [D. Visualization and Insights](#d-visualization-and-insights)
    - [E. Discussion and Conclusion from Experiments](#e-discussion-and-conclusion-from-experiments)
    - [F. Research Question: History of NLP](#f-research-question-history-of-nlp)
4. [Usage](#usage)
5. [License](#license)
6. [References](#references)

---

## Objectives and Problem Formulation

Studies have shown that sentiments from social media can provide valuable insights for businesses and government entities. In this coursework, our objective is to perform a detailed **Company Reputation Analysis** on Amazon Company by examining customer and employee opinions expressed on Reddit. This analysis will help:

- Understand overall brand perception and reputation.
- Gain insights into customer satisfaction and internal work culture.
- Inform potential customers and job seekers regarding the company's products and work environment.


---

## Learning Outcomes

By completing this coursework, participants will gain hands-on experience in:

- **Data Extraction:** Automatically extracting reviews and discussions from social media platforms like Reddit.
- **Text Analysis:** Using tools such as TextBlob and Vader to preprocess and analyze social media comments.
- **Dataset Preparation:** Collecting data and creating train-test splits for model building.
- **Pipeline Development:** Designing a text analytics pipeline covering text processing, feature extraction, classification, and evaluation.
- **Visualization:** Using techniques like word clouds and topic modeling to visualize and interpret insights.
- **Research:** Understanding the evolution of NLP through landmark breakthroughs and research literature.

---




---

## Usage

- **Data Extraction:** Run the provided Python scripts to authenticate with Reddit and extract comments using Async PRAW.
- **Data Preparation:** Follow guidelines for filtering, labeling, and splitting the dataset.
- **Model Development:** Execute the text analytics pipeline to preprocess text, extract features, build classification models, and evaluate performance.
- **Visualization:** Generate visualizations to explore sentiment distributions and topic modeling outputs.
- **Research Documentation:** Prepare the research summary on the history of NLP as per the provided specifications.

---

## License

This coursework and its accompanying scripts are provided for educational purposes only. Please refer to your institution’s licensing policies for further details.

---

## References

- **Reddit API Documentation:** [https://www.reddit.com/dev/api/](https://www.reddit.com/dev/api/)
- **TextBlob Documentation:** [https://textblob.readthedocs.io/](https://textblob.readthedocs.io/)
- **Vader Sentiment Analysis:** [https://github.com/cjhutto/vaderSentiment](https://github.com/cjhutto/vaderSentiment)
- **Chris Manning's Article on Human Language Understanding:** [https://www.amacad.org/publication/human-language-understanding-reasoning](https://www.amacad.org/publication/human-language-understanding-reasoning)
- **Stanford Course CS324H:** [https://web.stanford.edu/class/cs324h/](https://web.stanford.edu/class/cs324h/)

---



*Contributors:*  
Hariharakumar Rathinar, Yadubanshi Pratibha, Onafeso Fiyifoluwa, and Sattar Shaikh Eherar.
