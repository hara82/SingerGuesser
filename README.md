In the coursework at university, I aimed to predict a singer from a song's lyrics.
Basically, I built a system that can classify a song into one of the ten chosen singers such as MJ, Dua Lipa.

Firstly, data, a combination of the singer and the lyrics of a song, were gathered using Genius API. It was done in fetch_lyrics.ipynb.

Next, those data are convereted into dataset by cleaning the data, spliting them into train/validation/test set.
Thirdly, data were clustered to have a simple idea of the data.
After these steps, several classifiers were used to conduct this classification task.

The techniques used were several tokenizer, vectorizer(TfIdf, one-hot encoding, BERT), and classifier(Logistic Regression, Deep Learning).
After constructing such systems, their performance was evaluated with Precision, Recall, F1, and confusion matrix.
The highest F1 score, Recall, Precision were around 0.6, and the reasons for that performance were discussed in a report(not included here).

This is one of the courseworks I have done, but only this one is public so far mainly because others include some codes by other people. For this project, I wrote the entire code by myself.

