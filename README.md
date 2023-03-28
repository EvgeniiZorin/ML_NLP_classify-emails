# Description

Dataset - Apache SpamAssassin's public dataset https://spamassassin.apache.org/old/publiccorpus/

# ML model

Features:
- Character or word frequency, based on NLP of tokenized words or of specific tokens ("!", "$", "remove", "credit", "free")
- Number (or percentage) of capitalized words
- Number of words containing letters and numbers OR only letters;

Therefore, two approaches could be utilized:
- The word frequency approach used in NLP and word tokenization;
- The more classic ML approach based on feature engineering;

Features were taken from the following sources: 
- https://www.scirp.org/journal/paperinformation.aspx?paperid=56059.
- https://ieeexplore.ieee.org/document/5447486


