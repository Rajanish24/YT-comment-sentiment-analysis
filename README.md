Business Context:
We are "Influence Boost Inc.," an influencer management company seeking to expand our
network by attracting more influencers to join our platform. Due to a limited marketing
budget, traditional advertising channels are not viable for us. To overcome this, we aim to
offer a solution that addresses a significant pain point for influencers, thereby encouraging
them to engage with our company.

Business Problem:

1. Need to Attract More Influencers:
 * Objective: Increase our influencer clientele to enhance our service offerings to brands and stay competitive.

* Challenge: Limited marketing budget restricts our ability to reach and engage potential influencer clients through conventional means.

2. Identifying the Influencer Pain Point:
* Understanding Influencer Challenges: To effectively attract influencers, we need to
understand and address the key challenges they face.

* Research Insight: Influencers, especially those with large followings, struggle with
managing and interpreting the vast amount of feedback they receive via comments
on their content.

3. Big Influencers Face Issues with Comment Analysis:
* Volume of Comments: High-profile influencers receive thousands of comments on
their videos, making manual analysis impractical.

* Time Constraints: Influencers often lack the time to sift through comments to extract
meaningful insights.

* Impact on Content Strategy: Without efficient comment analysis, influencers miss
opportunities to understand audience sentiment, address concerns, and tailor their
content effectively.

# Our Solution
To directly address the significant pain point faced by big influencers—managing and
interpreting vast amounts of comment data—we present the "Influencer Insights" Chrome
plugin. This tool is designed to empower influencers by providing in-depth analysis of their
YouTube video comments, helping them make data-driven decisions to enhance their content
and engagement strategies.

Key Features of the Plugin:
1. Sentiment Analysis of Comments
* Real-Time Sentiment Classification:
• The plugin performs real-time analysis of all comments on a YouTube video,
classifying each as positive, neutral, or negative.

* Sentiment Distribution Visualization:
• Displays the overall sentiment distribution with intuitive graphs or charts (e.g., pie
charts or bar graphs showing percentages like 70% positive, 20% neutral, 10%
negative).

* Detailed Sentiment Insights:
• Allows users to drill down into each sentiment category to read specific comments
classified under it.

2. Additional Comment Analysis Features
* Word Cloud Visualization:
• Generates a word cloud showcasing the most frequently used words and phrases in
the comments.

• Helps quickly identify trending topics, keywords, or recurring themes.

* Average Comment Length:
• Calculates and displays the average length of comments, indicating the depth of
audience engagement.

* Export Data Functionality:•
• Enables users to export analysis reports and visualizations in various formats (e.g.,
PDF, CSV) for further use or sharing with team members.

# Challenges 

1. Data
    - Availability
    - Lack of general kind of dataset
    - Multi-language comments

    - Spam and bot comments
    - Slang emoji and informal comments
    - Sarcastic comments
    - Evolving language usage (e.g. sick) -> drift
    - Privacy and data compliance

2. Building a efficient model
    - Data noise, variability, class imbalance
3. Latency
4. User Experience

# Workflow
1. Data Preprocessing
2. EDA
3. Model building, Hyperparameter Tuning & Evaluation alongside Experiment Tracking
4. Building a DVC pipeline
5. Registering the model
6. Building the API using Flask
7. Development of Chrome Plugin
8. Setting up CI/CD pipeline
9. Testing
10. Building the Docker image and pushing to hub
11. Deployment using AWS