# Image Captioning


## Requirements
```
pip install -r requirements.txt
```

## Datasets

We used this Flickr8k [dataset](https://academictorrents.com/details/9dea07ba660a722ae1008c4c8afdd303b6f6e53b) for training our model.  We preprocessed these datasets in this repository.

## Run the Code
### Preprocessing 
Use the same datasets as ours. First, create an empty folder "preprocessed" in preprocess folder.

```
python main.py -d
```
### Training
```
python main.py -t
```
## Acknowledgments

* Deep learning cơ bản [blog](https://nttuan8.com/bai-15-ung-dung-them-mo-ta-cho-anh-image-captioning/)
* Image Captioning with Keras [blog](https://towardsdatascience.com/image-captioning-with-keras-teaching-computers-to-describe-pictures-c88a46a311b8)
