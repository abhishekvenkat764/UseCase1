# Call Transcript Analysis with Sentiment and Call Outcome Prediction

## Overview
This project aims to analyze call transcripts by extracting insights from customer interactions. The main objective is to identify the sentiment of the calls (positive, negative, neutral) and determine the outcome of each call (issue resolved, follow-up action needed). 

The dataset contains examples of call transcripts, and the analysis is performed using a Large Language Model (LLM) to interpret the transcripts accurately.

## Use Case
The accompanying file titled `transcripts_v3.zip` contains examples of call transcripts with both the agent and customer transcripts.

## Key Questions Addressed
1. **Sentiment Analysis**: What is the sentiment of the customer side of the transcript?
2. **Call Outcome Determination**: Was the issue resolved or is a follow-up action needed?

## Solution Approach
1. **Library Installation**: Identify and install necessary libraries.
2. **API Setup**: Set up API calls to the LLM (OpenAI - GPT-3.5-Turbo).
3. **Prompt Optimization**: Optimize the prompt used for the LLM.
4. **Processing Transcripts**: Loop through the transcripts and make calls to the LLM.
5. **Output Storage**: Store the output in a DataFrame and export it to an Excel file.

