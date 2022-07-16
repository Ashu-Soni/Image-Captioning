# IMAGE CAPTIONING

## Description
--------------
Generating a caption for a given image is a challenging problem in the deep learning domain. In this project, we will use different techniques of computer vision and NLP to recognize the context  of  an  image  and  describe  them  in  a  natural  language  like  English.  we  will  build  a working  model  of  the  image  caption  generator  by  using  CNN  (Convolutional  Neural Networks) and LSTM(Longshort-termmemory) units.

We implemented basic Image captioning model in `image_caption_normal.ipynb` file which uses CNN+LSTM based model. The LSTM based image captioning can "blindly" learn the structure of the language and predict meaningful sentences even without learning much insight to the content of the image. This is termed as "language bias" of the system. So, we tried to remove the language bias in `image_caption_language_bias.ipynb`


## Dataset Information
----------------------

For training, our model will be  using Flickr8K dataset. It consists of 8000 unique images and each image will be mapped to five different sentence. Flickr8k contains 8000 images that are each paired with five different captions which provide clear descriptions of the salient entities and events. The images were chosen from six different Flickr groups, and tend not to contain any well-known people or locations, but were manually selected to depict a variety of scenes andsituations.

## Technical Requirements
-------------------------
- Python: version 3.x.x
- PyTorch
- Jupyter Notebook/Google Colaboratory
- Basic Machine Learning Libraries: Numpy, Pandas, Sklearn



