# Fake News Detection

In this repo I have developed a flask app utilising NLP to identify when an article might be fake news. Data source: [Kaggle](https://www.kaggle.com/c/fake-news/overview)

The webapp looks like this: ![Flask Api](/App/flask.png)


## Installation

Install all required packages with:

```
pip install -r requirements.txt
```

## Quick Start(Inference only)
- Run [flask app](/App/) `app.py` using the command `python app.py`
- `Dockerfile` available to dockerise fake-news-api. Command `docker build -f Dockerfile -t fake-news-app:api .` _**Do not forget the dot(.) it tells docker that the dockerfile to be used is in the current directory.**_
- If you do not wish to build the docker, you can pull my container from dockerhub instead `docker pull sg22/fake-news-app:api2`

## Training Notebook
- [Jupyter Notebook](/fakenews_AI.ipynb) for training from scratch.
- Use data from [Kaggle](https://www.kaggle.com/c/fake-news/overview) to run through the notebook
- You are welcome to improve the accuracy of my model.


## Contributing
Pull requests? Be my guest!

For major changes, please open an issue first to discuss what you would like to change.
