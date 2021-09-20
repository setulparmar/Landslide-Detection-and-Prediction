# Landslide Detection and Prediction

**Configuration File**

Developed JSON configuration file which separates the crawler engine into general and focused crawling modes and helps to optimize different API calls for different landslide events.

**Crawler Engine**

Build crawler engine to crowdsource landslide related events in india from youtube and twitter. Further divided crawler engine to do general and focused crawling.

**Filtering and Pre-Processing**

Preprocessed data using NLP techniques and filtered out irrelevant events using hard-coding.

**Data Analysis**

Implemented Word Embedding using huggingface Sentence Transformer model and then used unsupervised approach to visualise cluster similar events together.

**Ranking Important Keywords**

Ranked Important Keywords using YAKE library which helped us to do more focused research on bigger landslide events.

**Location Extraction**

Improved time complexity of Location Extraction by implementing advanced and scalable trie data structure using APIs from Pygtrie library.

**Prediction Model**
Built a Binary Time Series Forecasting model achieving training and testing accuracy of 99% and 91% respectively.


Note : Daily automatic collection and filtering was there with the help of scheduling in deepnote.com .

