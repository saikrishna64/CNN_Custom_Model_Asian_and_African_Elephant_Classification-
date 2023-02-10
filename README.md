<!DOCTYPE html>
<html>
  <head>
    <title>CNN Custom Model: Asian and African Elephant Classification</title>
  </head>
  <body>
    <h1>CNN Custom Model: Asian and African Elephant Classification</h1>
    <p>
      This project is a custom Convolutional Neural Network (CNN) model for classifying images of Asian Elephants and African Elephants. The model is implemented in TensorFlow and uses the Keras API. The model architecture includes multiple Conv2D layers, MaxPooling2D layers, a Flatten layer, a Dense layer, and a Dropout layer. The final activation function is a sigmoid function, and the loss function used is binary crossentropy.
    </p>
    <h2>Data Preparation</h2>
    <p>
      The training and validation data should be prepared and loaded into the code before training the model. The data should consist of images of Asian Elephants and African Elephants, with labels indicating the class (Asian Elephant or African Elephant). The images should be resized to 64x64 pixels and have 3 color channels (RGB). 
    </p>
    <h2>Training the Model</h2>
    <p>
      The model is trained using the `fit` method, which takes in the training data and labels and trains the model for a specified number of epochs. The validation data and labels are also passed in to monitor the model's performance during training. The model is compiled using the `compile` method, which specifies the loss function and optimizer to use.
    </p>
    <h2>Evaluating the Model</h2>
    <p>
      The performance of the trained model can be evaluated on test data. The test data should consist of images that were not seen during training and validation, and should be labeled with the correct class (Asian Elephant or African Elephant). The model's accuracy can be obtained using the `evaluate` method, which takes in the test data and labels and returns the loss and accuracy.
    </p>
    <h2>Saving and Loading the Model</h2>
    <p>
      The trained model can be saved using the `save` method, and loaded using the `tf.keras.models.load_model` method. This allows the model to be used for prediction at a later time, without having to retrain the model.
    </p>
  </body>
</html>
