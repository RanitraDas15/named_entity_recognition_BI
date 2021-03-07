## Performing NER using text corpus from Wikipedia

### 1. Data Collection
The Data has been collected from Wikipedia using the "wikipedia" module available in python. This extracted data has been used as the text corpus for performing the task.

### 2. Data Cleaning
The text corpus is pre-processed using the regular expression (re) module in python to remove noice and unwanted characters from the corpus.

### 3. Performing NER using spaCy
Performed named entity recognition (NER) using spaCy's inbuilt 'ner' pipeline. Since, the extracted text corpus is not so large the scope of training spaCy with a custom model is limited. Hence, after using the inbuilt 'ner' pipeline to recognize the named entities, I plotted those entities in different bar graphs.
