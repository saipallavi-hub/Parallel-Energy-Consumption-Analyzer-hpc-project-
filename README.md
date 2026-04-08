# Parallel-Energy-Consumption-Analyzer-hpc-project-
AI Energy Intelligence Platform (HPC Project)

# Project Overview
This project presents a High Performance Computing (HPC)-based Parallel Energy Consumption Analyzer designed to efficiently process and analyze large-scale energy datasets. The system focuses on identifying energy usage patterns, detecting peak consumption periods, and predicting future energy trends using machine learning and deep learning techniques.
The platform integrates parallel processing, time-series forecasting, and interactive visualization to improve computational speed and scalability. By leveraging multiprocessing and GPU acceleration, the system significantly reduces execution time compared to traditional sequential approaches.
Full Project Report
Refer to the complete project documentation for detailed explanation of methodology, implementation, and results.

# Google Colab Notebook
Run the project directly in Google Colab:
https://colab.research.google.com/drive/1Geaw0FoYHnNrJTie4qAntxvt0R64YlnN?usp=sharing

# Dataset
The project supports Energy Consumption Dataset:
https://www.kaggle.com/datasets/robikscube/hourly-energy-consumption
Alternatively, users can upload their own dataset through the interface for real-time analysis.

# Technologies Used
* Python 3.x
* Pandas
* NumPy
* Scikit-learn
* TensorFlow (LSTM)
* Multiprocessing (HPC parallelism)
* Matplotlib
* Gradio (web interface)
* Google Colab

# Key Features
Parallel energy data processing using multiprocessing
Energy consumption prediction using Linear Regression
Time-series forecasting using LSTM
Peak load detection using statistical thresholds
Intelligent recommendation system for energy optimization
Interactive web-based dashboard using Gradio
Real-time visualization of energy trends
Downloadable CSV output

# System Architecture
The system follows a client–server architecture:
User uploads dataset via web interface
Gradio frontend sends data to backend
Data preprocessing and cleaning performed
Parallel processing applied for faster computation
Machine Learning and Deep Learning models executed
Peak detection and recommendation system applied
Results visualized and returned as downloadable output

# Installation and Setup
Clone Repository
git clone https://github.com/saipallavi-hub/Parallel-Energy-Consumption-Analyzer-hpc-project-
cd Parallel-Energy-Consumption-Analyzer-hpc-project

# Install Dependencies
pip install pandas numpy matplotlib seaborn scikit-learn tensorflow gradio

# How to Run
Option 1: Google Colab (Recommended)
Open the Colab notebook link
Upload dataset
Run all cells
Access the Gradio interface

# Option 2: Local Execution
python hpc.py
After execution, open the Gradio link displayed in the terminal.

# Output
The system produces:
Energy consumption analysis
Predicted energy values
Peak usage indicators
Recommendation suggestions
Visualization graphs
Downloadable CSV file

# Sample Output Fields
Consumption
Predicted Energy
Peak (True/False)
Recommendation
DateTime

# HPC Concepts Applied
Parallel processing using multiprocessing
Data chunking and distributed computation
Efficient handling of large-scale datasets
Time-series sliding window processing
GPU acceleration (via TensorFlow in Colab)

# Future Enhancements
Advanced deep learning models (GRU, Transformers)
Real-time streaming data integration
Cloud deployment (AWS / Azure)
Mobile-based energy monitoring app
Integration with smart grid and IoT systems

# Author
Madugula Sai Pallavi
B.Tech CSE (Data Science)
SR University

# References
Google Colab Documentation
Pandas Documentation
TensorFlow Documentation
Scikit-learn Documentation
Gradio Documentation
UCI Machine Learning Repository
HPC Research Papers
