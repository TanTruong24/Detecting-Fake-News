# Sarcasm detection using machine learning

Past studies in Sarcasm Detection mostly make use of Twitter datasets collected using hashtag based supervision but such datasets are noisy in terms of labels and language. Furthermore, many tweets are replies to other tweets and detecting sarcasm in these requires the availability of contextual tweets.

To overcome the limitations related to noise in Twitter datasets, the team's dataset was collected from a variety of websites. Mainstream pages include (News Week, The New York Time and The Sun Time), while satirical headlines are collected on the pages (The Beaverton, The Onion, The New Thump, The Civilian).

This new dataset has following advantages over the existing Twitter datasets:

- Since news headlines are written by professionals in a formal manner, there are no spelling mistakes and informal usage. This reduces the sparsity and also increases the chance of finding pre-trained embeddings.
- Furthermore, since the sole purpose of TheOnion is to publish sarcastic news, we get high-quality labels with much less noise as compared to Twitter datasets.
- Unlike tweets which are replies to other tweets, the news headlines we obtained are self-contained. This would help us in teasing apart the real sarcastic elements.

## Libraries used:

- matplotlib >= 3.4.2
- gensim==3.4.0 : https://radimrehurek.com/gensim/install.html
- spaCy==2.0.12 : https://spacy.io/usage/
- sklearn

<span style="border-width:1px; border-style:solid; border-color:#264653; background-color: #264653; padding: 4px;">Machine Learning</span>
<span style="border-width:1px; border-style:solid; border-color:#2a9d8f; background-color: #2a9d8f; padding: 4px;">Crawl Data</span>
<span style="border-width:1px; border-style:solid; border-color:#e9c46a; background-color: #e9c46a; padding: 4px;">Fake New</span>
<span style="border-width:1px; border-style:solid; border-color:#f4a261; background-color: #f4a261; padding: 4px;">NLP</span>
<span style="border-width:1px; border-style:solid; border-color:#e76f51; background-color: #e76f51; padding: 4px;">Sarcasm detection</span>
