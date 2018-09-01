

Expression Recognition

Used Convolutional neural networks (CNN) for facial expression recognition . The goal is to classify each facial image into one of the seven facial emotion categories considered .
Data :
trained and tested our models on the data set from the [Kaggle Facial Expression Recognition Challenge](https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge), which comprises 48-by-48-pixel grayscale images of human faces,each labeled with one of 7 emotion categories:<strong> anger, disgust, fear, happiness, sadness, surprise, and neutral </strong>.
<br><br>
 Image set of 35,887 examples, with training-set : dev-set: test-set as <strong> 80 : 10 : 10 </strong>.

Dependencies
 Python 2.7, sklearn, numpy, Keras.

Getting started

  To run the code -

  1. Download FER2013 dataset from [Kaggle Facial Expression Recognition Challenge](https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge) and extract in the main folder.

  2. To run deep CNN model. Open terminal and navigate to the project folder and run cnn_major.py file
    
    python cnn_major.py
    
  3. Want to train model yourself ?<br>
      Just change the statement

        is_model_saved = True
        // to
        is_model_saved = False

