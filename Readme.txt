**Instructions to run the code**

1 - Data collection:

      run the collect_imgs.py python file to use device's camera to capture 100 images for each letter 
      and storing them into folders.

2 - Data preprocessing

      run the create_dataset.py python file to iterate on each image get segmentation and extract 
      landmarks from each image and insert it into new folders.

3 - Model training and testing
 
      run the train_classifier.py python file to split the data into training and testing datasets to prepare
      the model.

4 - Deployment

      run the inference_classifier.py python file to finally use the application and get your answer.