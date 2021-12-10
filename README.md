# Poster2Plot: Generate movie/t.v show plot from a poster.

## ➡️ Try it out on any movie poster [here](https://huggingface.co/spaces/deepklarity/poster2plot)

## Pre-trained model is available [here](https://huggingface.co/deepklarity/poster2plot)

### Blog post with more details:
#### [How to train a model to generate Movie/T.V show plot from a poster](https://medium.com/@dsr.ai/how-to-train-a-model-to-generate-movie-t-v-show-plot-from-a-poster-eec6aea454ca)

# Train new model

- Download and extract the following datasets in a new folder called datasets:

  1. [IMDb movies extensive dataset](https://www.kaggle.com/stefanoleone992/imdb-extensive-dataset)
  2. [48K IMDB Movies With Posters](https://www.kaggle.com/rezaunderfit/48k-imdb-movies-with-posters)

- Run `create_dataset.ipynb` to create train.csv and valid.csv
- Run `train.ipynb` to train the model

#### Created By:

- [Kartik Godawat](https://twitter.com/kartik_godawat)
- [Deepak Rawat](https://twitter.com/dsr_ai)