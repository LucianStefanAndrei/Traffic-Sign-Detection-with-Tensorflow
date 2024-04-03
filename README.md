# This is a simple CNN model that I have used for my blog:

https://medium.com/@stefanandreilucian2/convolutional-neural-network-tutorial-with-traffic-sign-recognition-tensorflow-29c9a5edc29f

It contains both the model, and an additional more complex one.
Prerequisites: 
  1. Download the dataset from here: https://www.kaggle.com/datasets/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign/data
  2. Use the change_images notebook to create additional directories with augmented images for the overcomplicated model
  3. Name the directories accordingly, I extracted all the images in a directory named "gtrsb_traffic_sign"

The simple model presents good results, however, it is not trained on augmented data.
The overcomplicated model create a multi-model prediction mechanism that trains 4 models on different sets of data create using the change_images notebook.
It creates 3 directories with the same images but filters applied. The overcomplicated model, as I called it, holds worse results, however, it is more complex,
and uses data augmentation and multi-prediction.
