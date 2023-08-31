# FloodGAN
This is a MVP to predict realistic flooding in a given image using tensorflow 

**Problem**: Current solutions (such as maps) are not granular or nuanced enough to capture predicted flooding. With an increase in temperatures and an increase in sea levels - flooding becomes more prevalent and so realistic depictions of such floods are needed. 
**Solution**: Using Generative AI to develop realistic images of predicted flooding in an urban landscape of interest.


## Files
_cyclegan_tensorflow.ipynb_ - notebook to train CycleGAN model
_data_ - Folder with the input data (please refer to instructions below to recreate the data used)
_results_ - Folder containing some example

## Data
Multiple sources were used. For flood data Flood IMG Database https://www.kaggle.com/datasets/hhrclemson/flooding-image-dataset/code was used. For non flood data cityscapes https://www.kaggle.com/datasets/xiaose/cityscapes and City Street View Dataset
https://www.kaggle.com/datasets/stelath/city-street-view-dataset?select=street_view_10020.jpg were used. This provided a great source of input data. However, they dont contain many city flooding images. For which I scraped a few images of flooding in city. NYC has had multiple hurricanes in past and was the ideal way to find floding in a city.
To recreate the project please download the datasets in the appropriate folders under `data`. 

