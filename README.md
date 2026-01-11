# Eva Rasa Chatbot

## Setup
- install arrow, fuzzywuzzy, numpy, openpyxl and SpaCy
```
python -m pip install arrow
python -m pip install fuzzywuzzy
python -m pip install numpy
python -m pip install openpyxl
python -m pip install spacy
```
- install SpaCy model
```
python -m spacy install es_core_news_md
```


##  Running the chatbot
- Run rasa action server on separate terminal
```
rasa run actions
```
- Test bot on shell
```
rasa shell
```