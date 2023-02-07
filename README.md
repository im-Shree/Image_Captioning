# Image_Captioning
## Predict and display an appropriate caption for the identified image.


## Captions, Dataset Splits, and Human Annotations :

  ### Image Data set: https://www.kaggle.com/code/adityagupta235/image-captioning/data
  ### Flickr8k.token.txt - the raw captions of the Flickr8k Dataset . The first column is the ID of the caption which is "image address # caption number"
  ### Flickr8k.lemma.txt - the lemmatized version of the above captions 
  ### Flickr_8k.trainImages.txt - The training images used in our experiments
  ### Flickr_8k.devImages.txt - The development/validation images used in our experiments
  ### Flickr_8k.testImages.txt - The test images used in our experiments

ExpertAnnotations.txt is the expert judgments. The first two columns are the image and caption IDs. Caption IDs are #<0-4>. The next three columns are    the expert judgments for that image-caption pair. Scores range from 1 to 4, with a 1 indicating that the caption does not describe the image at all, a 2 indicating the caption describes minor aspects of the image but does not describe the image, a 3 indicating that the caption almost describes the image with minor mistakes, and a 4 indicating that the caption describes the image.

## Data collection:
 
  ### understanding of data
  ### data cleaning
  ### loading of training set
  ### data preprocessing -- images
  ### data preprocessing -- captions
  ### word embeddings
  ### model architecture
  ### evaluation


## Prediction outputs:

![image-1](https://user-images.githubusercontent.com/90651908/217174823-efee0b4f-e5ed-4163-ae16-90a357f21008.jpg)
### Caption: man and girl and two horses are near contained fire
![image-2](https://user-images.githubusercontent.com/90651908/217174869-d5144d6f-19ce-4969-b327-0f4e71ecb4a0.jpg)
### Caption: dog sticking its face into the shower from garden hose
![image-3](https://user-images.githubusercontent.com/90651908/217174690-e28f87a1-e9b6-4f46-a10d-4e390fd6baa8.jpg)
### Caption: man in blue shirt and jeans is standing in front of some people

## Acknowledgements: 

  ### http://www.jair.org/papers/paper3994.html
  ###  https://www.kaggle.com/datasets/sayanf/flickr8k
