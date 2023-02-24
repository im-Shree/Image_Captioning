## Image_Captioning
Predict and display an appropriate caption for the identified image.

  This is a machine learning project to generate captions for images using a combination of ResNet50V2 model for feature extraction,
  word embeddings for natural language processing, and a Keras model for training and prediction. 
  The NLTK library is also used to remove stop words and improve the quality of the captions. 
  Additionally, the VGG16 model from Keras Applications is used to compare the performance of different feature extraction models.

## Dataset

  The dataset used for this project is the Flickr8k dataset, which contains 8,000 images along with 5 captions each. 
  The dataset is preprocessed to extract image features using the ResNet50V2 and VGG16 models.

  ExpertAnnotations.txt is the expert judgments. The first two columns are the image and caption IDs. Caption IDs are #<0-4>. 
  The next three columns are the expert judgments for that image-caption pair. 
  Scores range from 1 to 4, with a 1 indicating that the caption does not describe the image at all, a 2 indicating the caption describes minor aspects of the image but does not describe the image, a 3 indicating that the caption almost describes the image with minor mistakes, 
  and a 4 indicating that the caption describes the image.

## Requirements

  This project requires Python 3.x and the following libraries:

  numpy
  pandas
  matplotlib
  seaborn
  scikit-learn
  keras
  tensorflow
  nltk

## You can install the required libraries using pip:

  pip install numpy pandas matplotlib seaborn scikit-learn keras tensorflow nltk

## Data collection:
 
  understanding of data
  data cleaning
  loading of training set
  data preprocessing -- images
  data preprocessing -- captions
  word embeddings
  model architecture
  evaluation
  
## Files

  The project consists of the following files:

  Image_Captioning.ipynb: Jupyter notebook containing the implementation of the ResNet50V2, VGG16 model for image captioning
  flickr8k_dataset: folder containing the preprocessed dataset
  flickr8k_text: folder containing the captions for the images

## Usage

    To run the project, first, download the Flickr8k dataset and save it in the project folder as flickr8k_dataset. 
    Then open the Jupyter notebooks and run the cells. The notebooks contain explanations and code for data preprocessing, feature extraction, model  building, and evaluation

## Prediction outputs:

![image-1](https://user-images.githubusercontent.com/90651908/217174823-efee0b4f-e5ed-4163-ae16-90a357f21008.jpg)
    
    Caption: man and girl and two horses are near contained fire
    
![image-2](https://user-images.githubusercontent.com/90651908/217174869-d5144d6f-19ce-4969-b327-0f4e71ecb4a0.jpg)
    
    Caption: dog sticking its face into the shower from garden hose
    
![image-3](https://user-images.githubusercontent.com/90651908/217174690-e28f87a1-e9b6-4f46-a10d-4e390fd6baa8.jpg)
    
    Caption: man in blue shirt and jeans is standing in front of some people

## Results

  The performance of the ResNet50V2 and VGG16 models is compared using the BLEU score, which is a metric for evaluating the quality of generated text. 
  The ResNet50V2 model achieves a BLEU-1 score of 0.591, BLEU-2 score of 0.400, BLEU-3 score of 0.285, and BLEU-4 score of 0.201. 
  The VGG16 model achieves a slightly lower BLEU-1 score of 0.573, BLEU-2 score of 0.387, BLEU-3 score of 0.271, and BLEU-4 score of 0.190.

## Conclusion

  In this project, we have seen how to use deep learning models to generate captions for images. We have also seen how to preprocess the dataset, extract image features, and evaluate the performance of the models. 
  The ResNet50V2 model has shown slightly better results than the VGG16 model, but other models can also be used depending on the specific requirements of the problem.

## Acknowledgements: 

  http://www.jair.org/papers/paper3994.html
  
  https://www.kaggle.com/datasets/sayanf/flickr8k
