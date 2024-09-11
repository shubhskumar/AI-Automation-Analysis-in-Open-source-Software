# Analysis of AI Automation in Open-source Software

This project explores the role of **AI assistants** like **GitHub CoPilot X**, **Amazon Code Whisperer**, and **ChatGPT** in enhancing software development productivity. Using **1.36 TiB of GitHub Archive data**, the analysis investigates the potential of AI assistants to augment or replace human developers by focusing on trends in **programming languages**, **licenses**, **commit patterns**, and **repository growth**.

## Table of Contents
- [Project Overview](#project-overview)
- [Methodology](#methodology)
- [Data Overview](#data-overview)
- [Key Findings](#key-findings)
- [Conclusions](#conclusions)
- [Future Work](#future-work)

## Project Overview
In the era of AI-driven software development, there is growing interest in understanding the impact of AI assistants on **developer productivity**. This project focuses on the **GitHub Archive dataset** to examine AI’s influence on the most prolific open-source repositories. Key questions addressed include:
- How do AI tools affect commit rates?
- What are the most popular programming languages and licenses on GitHub?
- Can AI tools replace human developers, or are they better suited as assistants?

## Methodology
### 1. Exploratory Data Analysis (EDA)
- **Data Cleaning**: Discarded irrelevant or erroneous data.
- **Feature Selection**: Focused on relevant variables like **commit messages**, **programming languages**, and **licenses**.

### 2. Visualization & Analysis
- **Timeline Analysis**: Explored peaks and valleys in commit activities across time.
- **Programming Language & License Distribution**: Visualized language usage and the relationship between languages and licenses.
- **AI Assistants Impact**: Analyzed AI assistants’ effects on developer productivity.

## Data Overview
- **Dataset Size**: ~1.36 TiB stored in Google Cloud Storage.
- **Key Dataframes**:
  - **Commits**: Metadata on author, committer, date, and message.
  - **Contents**: Source code analysis and null value handling.
  - **Languages**: Distribution of code bytes for each programming language.
  - **Licenses**: Insights into the types of licenses used in repositories.

## Key Findings
### 1. Programming Language Trends
- **C** was found to be the most popular programming language, with nearly 6 trillion bytes of code.
- **JavaScript**, **C++**, **PHP**, and **HTML** followed as the top languages by code volume.

### 2. License Usage
- The **MIT license** was the most widely used, especially in popular languages like JavaScript, CSS, HTML, and Python.
- **Java** showed more prevalence with the **Apache 2.0** license compared to MIT.

### 3. Repository Growth
- **Coq-bench**, **Frohoff-dev-jdk**, and **Cosnics** were identified as the most popular repositories based on commit count.
- **Shenzhouzd**, **Duaneking**, and **Mycroft-core** were the most rapidly growing repositories by commit increment rate.

### 4. AI Assistants Impact
- **AI tools** like GitHub CoPilot and ChatGPT were found to assist in repetitive tasks but showed limitations in replacing human developers. Their role appears to be more complementary, enhancing productivity rather than replacing developers entirely.

### 5. Commit Message Uniqueness
- **60% of commit messages** were unique, suggesting that both commit **subject** and **message** fields contain distinct information across repositories.

## Conclusions
The analysis demonstrates that **AI assistants** like GitHub CoPilot and ChatGPT improve productivity by automating repetitive coding tasks. However, the findings indicate that human developers are still essential, particularly for creative problem-solving and decision-making. AI tools excel in supporting developers, but they do not yet possess the capability to fully replace human expertise.

**Key Takeaways**:
- **AI-human collaboration** is the optimal path forward, with AI handling repetitive tasks and humans focusing on high-level decisions.
- AI tools contribute to open-source repositories’ growth, but **human ingenuity** remains a critical component of software development.

## Future Work
- **Causality Study**: Further research on how AI assistants influence specific aspects of development (e.g., bug fixes vs. new feature implementations).
- **Deeper Language Analysis**: Investigating trends in **data science libraries** and their adoption across repositories.
- **Longer Timeline**: Expanding the timeline analysis to observe long-term trends in AI automation across GitHub repositories.
