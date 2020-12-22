# Next-Word-Suggestion

## Works like a smart suggestion feature as in google keyboard, suggests words on previous knowledge of text data trained on.

## Demo
![demo](NWP.gif)

## How it Works
1. This is a sequential model built with LSTMs.
2. The model is fed with previous data.
3. During writing it predicts possible words by prediction previous words in the sentence and prefix matching.

## Tips to run
1. Download the [blog csv dataset](https://www.kaggle.com/rtatman/blog-authorship-corpus) as blogtext.csv and run the pretrained [model](NWP.h5), training not needed.

2. To train change the configuration variables in NWP.ipynb. Detailed guide [here](https://youtu.be/UDm-s3Wr9rk).