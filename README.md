# Landslide Detection and Prediction

**Configuration File**

Designed JSON configuration file which separates the crawler engine into general and focused crawling modes and helps to optimize different API calls for landslide events.

**Crawler Engine**

Built crawler engine to crowdsource landslide related events in india from youtube and twitter. Further divided crawler engine to do general and focused crawling.

**Filtering and Pre-Processing**

Preprocessed data using NLP techniques and filtered out irrelevant events.

**Data Analysis**

Implemented Word Embedding using huggingface Sentence Transformer model and then used unsupervised approach to cluster similar events together.

**Ranking Important Keywords**

Ranked Important Keywords using YAKE library which helped us to do more focused research on bigger landslide events.

**Location Extraction**

Improved time complexity of Location Extraction by implementing advanced and scalable trie data structure using APIs from Pygtrie library.

**Prediction Model**

Applied CNN to predict landslide events.


Note : Daily automatic collection and filtering was there with the help of scheduling in deepnote.com .

