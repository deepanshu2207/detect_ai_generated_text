Hi,

In this project, I have tried using different approaches to detect/classify AI-generated content.

Approach 1:
Tried finetuning distilbert base model on the given data.

Approach 2:
Tried training the tokenizer on the given data and then used TFIDF to get the vectors/embeddings of the tokenized input. Finally, applied the combination of classification models (3 SGDs with different configurations and 1 Multinomial classification model).

Approach 3:
(To do) Using Gemini for the given task. 
