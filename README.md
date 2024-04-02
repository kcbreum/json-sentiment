# Web Mining & Applied NLP Project 4 - Requests, JSON, and basic NLP with spaCy

## Project Description
This project is meant to practice accessing web-hosted APIs, get back a response in JSON format, and extract information needed from the JSON.

## Project Setup
### Create a virtual environment
``` shell
py -m venv .venv
py -m .\.venv\Scripts\activate
```

### Install dependencies and upgrade pip
``` shell
import requests
import json
import pickle
import spacy
from spacytextblob.spacytextblob import SpacyTextBlob
py -m pip install --upgrade pip
py -m pip install -r requirements.txt
```

### Freeze requirements
``` shell
py -m pip freeze > requirements.txt
```

### Add to .gitignore
``` shell
.venv/
.vscode/
*~
.ipynb_checkpoints/
*.ipynb_meta/
```


## Imported Dependencies
``` shell
import requests
import json
import pickle
import spacy
from spacytextblob.spacytextblob import SpacyTextBlob
```

### Git Add and Commit
``` shell
git add .
git commit -m "update message goes here"
git push origin master
```

### Credentials
This was a required project to be completed for the MS in Data Analytics degree at Northwest Missouri State University. Assisted instructions were given by Denise Case. Additionally AI was utilized to complete this project. Deitel, P. (2021). INTRO TO PYTHON FOR COMPUTER SCIENCE AND DATA SCIENCE : learning to program with ai, big data, and the cloud, global edition. Pearson Education Limited.