# political-affiliation-prediction

## Setup

Install [virualenv(-wrapper)](https://virtualenvwrapper.readthedocs.org/en/latest/).

    mkvirtualenv political-affiliation-prediction
    # or
    workon political-affiliation-prediction
    pip install -r requirements.txt
    DEBUG=1 python api.py

## Test

    curl --data "text=angriffskrieg" 1:5000/predict
