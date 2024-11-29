# Phone Issues Identification and Interpretation
### Overview
iPhone Issues Identification and Interpretation is a project aimed at discovering and interpreting issues related to iPhones based on user-generated content from subreddit communities. By leveraging a combination of sentiment analysis, topic modeling, and large language models (LLMs), the project aims to identify negative sentiment posts, extract and analyze their topics, and provide meaningful interpretations and descriptions of the issues.

This project uses fine-tuned BERT, BERTopic, and Mistral AI to create a pipeline for data-driven insights into iPhone-related discussions.

## Project Workflow
### Sentiment Classification

- Fine-tuned BERT to classify the sentiment of subreddit posts.
- Posts with negative sentiment are extracted for further analysis.

### Topic Modeling

- Used BERTopic, a topic modeling library, to discover topics within the negative sentiment posts.
- Identified topics are associated with keywords and representative documents.

### Topic Interpretation

- Leveraged Mistral AI, an LLM, to interpret the discovered topics by:
- Renaming the topics based on their keywords.
- Generating detailed topic descriptions using the topic name, keywords, and representative documents.
