# Email-Response-Assistant
An Email Assistance that utilises NLP rank emails based on urgency and uses AI to generate response

This project assists you in the process of analysing the content of emails by dividing them into segments. It employs natural language processing to identify the sentiment and gives the mails an urgency score. Once the scores are given then the emails are ranked, for the most urgent one, a responec is generated using AI

## NLP Techniques used
Tokenization & Stopword Removal: The function tokenize_and_remove_stopwords() tokenizes the email body and removes stopwords to focus on relevant words.

Part-of-Speech (POS) Tagging: The function pos_tagging() performs POS tagging on the email content, identifying different parts of speech like nouns, verbs, etc.

Named Entity Recognition (NER): The function extract_relevant_entities() extracts important entities from the email text, such as dates, times, organizations, people, and more.

TF-IDF: For determining the most important words in the email.

Sentiment Analysis: The tool assesses the tone of the email (e.g., positive, negative, or neutral) to help gauge how urgent or critical the message is. 


