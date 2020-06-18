## Implementation of Interest Sustainability-aware Recommender System

## Requirements
- python 3.7.6
- pytorch 1.3.1
- numpy 1.16
- scikit-learn
- scipy

## Train a classifier for the intereset sustainability prediction

``` bash
python  train_interest.py --dataset tools
```


## Train CRIS for the recommendation task

``` bash
python  train_recommender.py --dataset tools --lamb 0.1 --gamma 0.8 --learning_rate 1e-3
```
##### Note: To reduce the memory usage, you can set the number of workers as 0 (```num_workers=0```) in dataloader_recommendation.py
