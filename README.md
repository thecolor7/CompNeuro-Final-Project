# CompNeuro-Final-Project



Data Description and Visualization:

TUNIZI V2: The largest TUNIZI dataset with 100,000 sentences, with 52% annotated as positive (1), 43%   as negative (-1), and 5% as neutral (0).
Arabizi is a romanization of Arabic text, used frequently in social media posts and comments from Middle Eastern countries. This dataset specifically sourced and labeled the Arabizi romanization of the Tunisian Arabic dialect.


Objective:

Compare the performance of AraBERT (Arabic sentiment analysis model) versus mBERT (multilingual sentiment analysis model) when fine-tuned to process Tunisian Arabizi tweets.


Model Description:

AraBERT: Transformer-based model pre-trained on massive corpora of Arabic text. As Tunisian Arabic is an Arabic dialect, AraBERT may perform better than mBERT, but this model was pre-trained on the Arabic script, not the latin script.
mBERT: Transformer-based model pre-trained on large multilingual corpora in a self-supervised fashion. As this model was pre-trained on a wide variety of languages and scripts, it may perform better for sentiment analysis.


Metrics:

Weighted F1 Score as the TUNIZI dataset is not balanced.
Precision and Recall 
Accuracy
Confusion matrix


Interpretation/Discussion:

Results and interpretation would be included here in the final submission.
Limitations: Neither model is pre-trained on tweets, Tunisian Arabic, or Arabizi specifically.
Another dataset for Tunisian Arabizi would be hard to find for further training or analysis.
	•		⁃	The usage for a fine-tined Tunisian Arabizi model based off of this dataset is quite particular as it would only be only useful to analyze sentiment in Tunisian Arabizi tweets.
