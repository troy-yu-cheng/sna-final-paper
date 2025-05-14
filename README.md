# Structural Dynamics of Retweeter Amplification Backbone Networks

***Author: Troy (Yu) Cheng***

This repository contains the final paper project for **CCTP 5020 Social Network Analysis (Spring 2025, Georgetown University)**. 

## Project Website

You can view the rendered paper as a GitHub Page here:  
**[troy-yu-cheng.github.io/sna-final-paper](https://troy-yu-cheng.github.io/sna-final-paper/)**


## Overview

This project investigates how retweeters contribute to the amplification of misinformation on Twitter. It introduces and analyzes **Retweeter Amplification Backbone Networks** (RABNs)—networks composed of users connected by shared retweeting behaviors related to misinformation claims. The study focuses on the COVID-19 Wuhan lab origin theory and explores three co-dissemination network types:

- **Direct Co-Retweet**: Users who retweeted the same misinformation tweet.
- **Quote Path Co-Retweet**: Users who retweeted the original tweet or any quoting it.
- **Reply Path Co-Retweet**: Users who retweeted the original tweet or any reply to it.

A total of 18 backbone networks (3 network types × 6 stages) are constructed and compared using Social Network Analysis (SNA) methods.


## Research Focus

- How do different types of co-dissemination behaviors shape amplification backbone network structures?
- How do these structures evolve across different stages of the misinformation narrative?

Key structural metrics examined:
- Density  
- Local & Global Transitivity  
- Degree Centralization  
- Average Path Length  

Both **hypothesis testing** and **Conditional Uniform Graph (CUG) tests** were employed for comparative analysis.


## Repository Structure

```bash
.
├── index.qmd    # Source Quarto file for the paper
├── index.html   # Rendered HTML paper for GitHub Pages
├── plot/        # Network plots for all 18 backbone networks
├── assets/ 
├── sna-final-paper.Rproj
├── trycstyle.css # Custom CSS styling for html
└── README.md 
