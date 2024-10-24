# lmsfirewall-csca3
Cybersecurity Course CA - 3
# Network Firewall Comparison: Traditional vs LMS-based Approach

This project implements and compares two different firewall approaches:
1. A traditional threshold-based firewall
2. An adaptive firewall using the Least Mean Square (LMS) algorithm

# Overview
The project analyzes network traffic data using the KDD Cup 1999 dataset to detect network intrusions. It compares the performance of a traditional rule-based firewall against a machine learning-based approach using the LMS algorithm.

# Prerequisites
- Google Colab account
- Basic understanding of Python and machine learning concepts

# Quick Start
1. Open the project in Google Colab:
   https://colab.research.google.com/drive/17F_PeCxRlOVUtF_JCD8k216RHhfbPTwO
   
3. Run all cells sequentially using either:
   - Click "Runtime" → "Run all"
   - Use the keyboard shortcut Ctrl+F9

# Project Structure
The code implements:
- Data preprocessing and feature engineering
- Traditional firewall with threshold-based rules
- LMS-based adaptive firewall
- Real-time traffic simulation
- Performance comparison and visualization

# Key Components
1. *Data Loading and Preprocessing*
   - Loads the KDD Cup dataset
   - Encodes categorical features
   - Scales numerical features
   - Splits data into training and test sets

2. *Traditional Firewall*
   - Uses percentile-based thresholds
   - Monitors key network features
   - Makes binary decisions (normal/attack)

3. *LMS Firewall*
   - Implements adaptive learning
   - Updates weights in real-time
   - Uses sigmoid activation for classification

4. *Comparison Framework*
   - Simulates live traffic
   - Measures accuracy over time
   - Generates comparative visualizations

# Output
The program generates:
- Training error plots
- Confusion matrices
- Classification reports
- Real-time accuracy comparisons
- Final performance metrics

# Runtime Requirements
- Estimated runtime: 10-15 minutes
- Memory usage: ~2GB
- Internet connection (for dataset download)

# Dataset Information
Uses the KDD Cup 1999 dataset:
- 41 features per network connection
- Binary classification (normal vs. attack)
- Features include protocol type, service, duration, etc.

# Troubleshooting
If you encounter:
- Memory errors: Reduce `num_packets` in live_firewall_comparison
- Runtime errors: Ensure all required libraries are imported
- Data loading issues: Check internet connection

## Authors
Isha Singh/ SIT, Pune
Sarthak Tripathi/ SIT, Pune

# GitHub Repository
https://github.com/ishasinghy/lmsfirewall-csca3

## Acknowledgments

- KDD Cup 1999 dataset providers
- UCI Machine Learning Repository
