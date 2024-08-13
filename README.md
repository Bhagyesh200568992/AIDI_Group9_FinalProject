# AIDI_Group9_FinalProject
Title : Sentiment Analysis on Financial Text Data Using BERT 
Group Member Names : Group 9 
Bhagyesh Parmar (200568992) 
Rahul Pandey (200576239)

The project aimed to perform sentiment analysis on financial text data, classifying the sentiment as either positive or negative using a fine-tuned BERT model.

Data Preprocessing:

The dataset consisted of financial texts labeled as positive (1) or negative (0).
The data was split into training (80%) and validation (20%) sets.
Model Selection:

A pre-trained BERT model was used for its effectiveness in natural language understanding.
Text data was tokenized using the BERT tokenizer.
Training Setup:

The model was trained for 3 epochs with a batch size of 8.
Additional techniques like weight decay and warmup steps were applied to enhance performance.
Evaluation Metrics:

Metrics used were accuracy and F1 score, important for understanding model performance, especially with imbalanced data.
Results:

The model showed improvement over the 3 epochs, with the best performance in the final epoch:
Accuracy: 80%
F1 Score: 0.7625
Conclusion:

The BERT model effectively classified financial sentiments, showing significant improvement by the third epoch. However, there is potential for further optimization.

[1]:  [BERT Research Paper](https://arxiv.org/pdf/1810.04805)

[2] : [Transformer Librabry GitHub Documentation](https://github.com/huggingface/transformers)

[3]: [Finance Dataset](https://www.kaggle.com/datasets/prishasawhney/sentiment-analysis-evaluation-dataset)
