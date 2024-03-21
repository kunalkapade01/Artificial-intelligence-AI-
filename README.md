 # **PC_Parts Classification Using Convolutional Neural Networks (CNN)**
-  **Objective**:
                  -   To develop a CNN-based model for classifying PC parts images into categories such as cables, case, CPU, GPU, RAM, etc.
   
  
- **Technologies and Tools** :
     - Python
     - TensorFlow
     - CNN (Convolutional Neural Networks)
     - ImageDataGenerator: For Data augmentation techniques (such as rescale, rotation_range, flipping, scaling and range)
     - Layers: such as Conv2D, MaxPool2D, Flatten, Dense
       -GitHub for version control and collaboration

- **Datasets**:
    - In pc_parts datasets there are the 14 classess for training the data, and in there 14 class there is multiple images.
    - Datasets URL:  https://www.kaggle.com/datasets/asaniczka/pc-parts-images-dataset-classification
 
 - **Data Generator** :
    - In data generato for the training and test sets from flow_from_directory
    - It can be generate data in train_generator and test_generator, then we found the images belonging to 14 class for train and test

- **CNN model** :
    - We can create the CNN sequential model, we can use the layes, Conv2D, MaxPool2D, Flatten and Dense layes
    -   And also the activation function.

- **In Summary** :
  		- The pc_parts Convolutional Neural Network (CNN) models in both graphs show good potential for classification, achieving accuracy/loss and also validation accuracy.
    -  Using graph it can show the Training, validation accuracy and Training, validation Loss
       -  While in train the model it can 50 epochs only, but the accuracy is definetly increases / and loss also decreses.
       -  So overall result is teh pc_parts CNN model is perfectly train/test.

- **And Finally**, :- Trained CNN model demonstrates promising performance on [dataset], achieving [accuracy/loss] of [value] on validation data with limited overfitting potential. Further evaluation on a larger dataset is recommended.

- **Outputs (Graph)** :
   - ![Training and  validation loss](https://github.com/kunalkapade01/Artificial-intelligence-AI-/assets/107420977/ee2ac5d9-a62c-4826-8a4d-954479b1211a)
