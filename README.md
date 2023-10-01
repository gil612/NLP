# NLP

## Basic Definitions

### Named Entity Recognition

NE's are definite noun phrases that refer to specific types of individuals, such as organizations, persons, dates, and so on.
The Goal of NER system is to identify all textual mentions of the named entities. This can be broken down into two suctask: Identifying the boundarie of the NE, and identifying its type.
It can attrubute to Question Answering.

### Embeddings

Embeddings measure the relatedness of text strings. Embeddings are commonly used for search, clustering, recommendations, animaly detection, diversity measurement and classification.
An embedding is a vector (list) of floating point numbers. The distance between two vectors measures their relatednedd. Small distances suggest high relatedness ad large distances suggest low relatedness.

### BERT

Bidirectional Encoder Representations from Transformers


* It uses only encoders (12 transformer encoder layers)
* Bidirectional links connecting the “lanes” between layers
* Trained on ≈ 3.3 Billion words (Wikipedia & Google Books corpus)
* Created with transfer learning in mind:
  * Trained on 2 simple unsupervised tasks (for which lots of data is available)
  * Can be fine-tuned for numerous complex tasks (for which few labeled data are available)
* Due to the transformer’s attention mechanism, we get contextualization “for free


### Sentinemt Analysis

The process of analyzing digita; text to determine if the emotional tine of the messasge os positive, negative, or neutral.
Sentiment analysis tools can scan this text to autimitacally determine the author's attitude woeards a topic. Companies use the insights from sentiment analysis improve cutomer service and increase brand reputation.

https://aws.amazon.com/what-is/sentiment-analysis
- - - -
<p align="center">
  <a href="https://projector.tensorflow.org/?config=https://gist.githubusercontent.com/gil612/2b13c36e6f87b057cfe535ba4235701c/raw/aaf6650066351a75319a47a6ce389a4591113d82/gist.json" target="_blank" />
  <img src="https://github.com/gil612/NLP/blob/37f454239f9bb7e2808c098cc14df35f3db78a2d/Screenshot%202023-10-01%20211434.png" width="1280"/>
</p>
