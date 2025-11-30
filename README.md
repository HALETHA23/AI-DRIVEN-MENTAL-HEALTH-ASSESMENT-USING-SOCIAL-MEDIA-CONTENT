AI-Based Mental Health Assessment Using Social Media Content

This project analyzes mental health patterns based on user-generated text data from social media platforms such as Reddit and Twitter. The system performs sentiment analysis, emotion detection, and MBTI personality type prediction to evaluate psychological state and provide early indicators of mental health concerns.

Data is processed using NLP and transformer-based models to extract key emotional and behavioral signals. Results are visualized with interactive charts, summaries, and downloadable PDF reports to support informed understanding of user well-being.

Project Scope

Sentiment Analysis
Identifies whether user expressions are positive or negative

Emotion Detection
Classifies emotions such as joy, fear, anger, surprise, and sadness

Personality Prediction
Predicts MBTI personality based on language patterns

Risk Assessment
Aggregates signals to classify user state as Stable, At-Risk, or Critical

Visualization and Reporting
Displays analysis results using charts, graphs, and word clouds
Allows users to download a detailed report

Architecture Overview

Text Data Input → NLP Preprocessing → AI Model Predictions
Sentiment + Emotion + Personality → Risk Evaluation → Visual Dashboard and PDF Summary

Models and Tools

Python 3.8+
Transformers (DistilBERT for sentiment and emotion, XLNet for personality typing)
Scikit-Learn, Pandas, NumPy
Plotly and WordCloud for visualization
Streamlit for interactive UI
WeasyPrint for PDF generation
APIs such as Twitter API and Reddit PRAW for data retrieval

Business and Social Impact

Provides early detection of mental health concerns through behavioral signals
Supports healthcare professionals and awareness initiatives
Encourages proactive wellness monitoring using AI-driven insights

Future Enhancements

Integration with additional social platforms
Time-based progression tracking
Personalized recommendations and mental health support links
Deployment as a browser extension or cloud-hosted application
