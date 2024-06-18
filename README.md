# Bilingual-sentiment-analysis

Multi-class sentiment analysis problem to classify texts into five emotion categories: joy, sadness, anger, fear, neutral. If you are interested in sentiment analysis in deep learning, try this project. This includes dataset preparation, machine translation using the Seq2Seq model, and sentiment analysis based on LSTM.

## Datasets

### Machine Translation

en-ch.txt: A collection of Chinese-English translation texts.

### Sentiment Analysis

##### Summary Table

|     Dataset    | Year |  Content  |     Size     | Emotion categories | Balanced |
| :--------------: | :--: | :-------: | ------------ | ------------------ | :-------: |
|dailydialog| 2017 | dialogues |102k sentences|neutral, joy, surprise, sadness, anger, disgust, fear| No |
|emotion-stimulus|2015|dialogues|2.5k sentences|sadness, joy, anger, fear, surprise, disgust| No |
|isear|1990|emotional situations|7.5k sentences|joy, fear, anger, sadness, disgust, shame, guilt| Yes |

links: [dailydialog](http://yanran.li/dailydialog.html), [emotion-stimulus](http://www.site.uottawa.ca/~diana/resources/emotion_stimulus_data), [isear](http://www.affective-sciences.org/index.php/download_file/view/395/296/)


##### Combined dataset

Dataset was combined from dailydialog, isear, and emotion-stimulus to create a balanced dataset with 5 labels: joy, sad, anger, fear, and neutral. The texts mainly consist of short messages and dialog utterances.
