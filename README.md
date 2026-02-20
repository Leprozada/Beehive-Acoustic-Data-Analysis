# Beehive-Acoustic-Data-Analysis

## Overview

This project presents an end-to-end data analysis pipeline integrating large-scale acoustic recordings with environmental sensor data (temperature and humidity). The objective was to explore behavioural patterns through structured preprocessing, feature extraction, statistical modelling, and temporal trend evaluation.

The project was completed as part of an MSc dissertation and has been refactored into a clean, porfolio ready case study.

## Problem Statement

Can acoustic features extracted from continuous beehive recordings reveal meaningful behavioural patterns, and how do these patterns relate to environmental conditions?

## Dataset

The project integrates two primary data sources:

• Acoustic recordings (continuous hive audio data)
• Environmental sensor log (temperature & humidity)

Audio recordings were processed into structured feature datasets to enable statistical analysis and correlation modelling. 

## Methodology

The analytical workflow consisted of:

1. Data Preprocessing

• Audio segmentation and cleaning
• Timestamp alignment
• Handling missing values

2. Feature extraction

• RMS (energy)
• Spectral Centroid
• Spectral Bandwidth
• Additional spectral descriptors

3. Data Integration

• Merging acoustic features with environmental data
• Time-based alignment

4. Exploratory & Statistical Analysis

• Correlation Analysis
• Temporal trend evaluation
• Visual pattern identification

## Key Findings

• Identified measurable relationships between environmental variation and acoustic energy patterns
• Temporal trend analysis revealed structured daily activity cycles.
• Automated preprocessing significantly improved dataset consistency and reproducibility.
• Data visualisation supported clearer interpretation of behavioural changes over time.

## Technology Used

• Python
• Pandas
• Numpy
• Matplotlib
• Scikit-learn
• Jupyter Notebook

## Project Structure

beehive-acoustic-data-analysis/
│
├── notebooks/
│   └── 01_beehive_case_study.ipynb
├── src/
│   └── (data processing modules)
├── data_sample/
│   └── (small sample dataset)
└── README.md

## Future improvements

• Real-time monitoring implementation
• Anomaly detection modelling
• Dashboard-based visual reporting



