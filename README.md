# Call Center Data - README

## Overview
This dataset contains information about customer interactions with call centers through various communication channels. The data includes timestamps, locations, customer details, issues raised, response times, sentiment analysis, and satisfaction scores.

## Data Fields
- **Call Timestamp**: Date of the customer interaction.
- **Call-Centres City**: The city where the call center handling the request is located.
- **Channel**: The communication method used (Call-Center, Chatbot, Email, Web).
- **City**: The customer's city.
- **Customer Name**: The name of the customer.
- **Id**: A unique identifier for each customer interaction.
- **Reason**: The purpose of the customer's call (e.g., Billing Question, Service Outage, Payments).
- **Response Time**: Indicates whether the response was within SLA (Service Level Agreement) or not (Within SLA, Above SLA, Below SLA).
- **Sentiment**: The sentiment analysis of the customer's response (Very Positive, Positive, Neutral, Negative, Very Negative).
- **State**: The state in which the customer is located.
- **Call Duration In Minutes**: The duration of the customer interaction in minutes.
- **Csat Score**: The Customer Satisfaction Score (if available) on a scale of 1 to 10.

## Usage
This dataset can be used for:
- Analyzing customer satisfaction trends.
- Evaluating the efficiency of different communication channels.
- Understanding the impact of response time on customer sentiment.
- Identifying common customer issues and their resolution times.

## Notes
- Missing values may exist in the dataset, especially in the "Csat Score" field.
- The dataset includes multiple channels, so comparisons should consider the differences in interaction methods.
- Further analysis can be performed using data visualization tools or statistical methods to gain deeper insights into customer service performance.

