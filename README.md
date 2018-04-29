Building a convolutional neural network (CNN/ConvNet) using TensorFlow NN (tf.nn) module. The CNN model architecture is created and trained using the CIFAR10 dataset. The model is accessed using HTTP by creating a Web application using Python and Flask.
The following diagram summarizes the project.
![system_diagram](https://user-images.githubusercontent.com/16560492/39411182-56ae1492-4c05-11e8-99cd-3172698d97e3.png)

The project steps are as follows:

1) <h4>Preparing the Training Data</h4>
The training data should be read and prepared for use with the CNN.
2) <h4>Building the Computational Graph</h4>
The CNN architecture is created by stacking conv-relu-pool-dropout-fc layers.
![graph_large_attrs_key _too_large_attrs limit_attr_size 1024 run 1 - copy](https://user-images.githubusercontent.com/16560492/39411206-ae3add94-4c05-11e8-9444-a7c21d3fa254.png)
3) <h4>Training the CNN</h4>
Training the CNN based on the prepared training data.
4) <h4>Saving the Trained CNN Model</h4>
The trained CNN model is saved for later use for predicting unseen samples.
5) <h4>Restoring the Pre-Trained Model</h4>
Before predicting class label for unseen samples, the saved CNN model must be restored.
6) <h4>Testing the Trained CNN Model</h4>
New unseen test samples are fed to the model for predicting its labels.
7) <h4>Building Flask Web Application</h4>
A Flask Web application is created to enable the remote access of the trained CNN model for classifying images transferred using the HTTP protocol.
8) <h4>Upload an Image via HTML Form</h4>
A HTML page will allow the user to upload a CIFAR10 image to the server. 
![2018-04-29_22-28-43](https://user-images.githubusercontent.com/16560492/39411196-8b5ea3f0-4c05-11e8-8eae-f9006f8f9b63.png)
9) <h4>Using JavaScript and CSS</h4>
Some helper JS and CSS files are created to style the Web application.
10) <h4>Invoking the Trained Model for Prediction</h4>
The uploaded image will be classified using the restored pre-trained CNN model. The classification label will finally get rendered on a new HTML page.
![2018-04-29_22-30-57](https://user-images.githubusercontent.com/16560492/39411202-98faaedc-4c05-11e8-9f3b-785a06bec1cb.png)

<h3>References</h3>
tf.nn module:<br>
https://www.tensorflow.org/api_docs/python/tf/nn<br>
CIFAR10 dataset:<br>
https://www.cs.toronto.edu/~kriz/cifar.html<br>

<h3>For more info.</h3>
KDnuggets: https://www.kdnuggets.com/author/ahmed-gad<br>LinkedIn: https://www.linkedin.com/in/ahmedfgad<br>Facebook: https://www.facebook.com/ahmed.f.gadd<br>ahmed.f.gad@gmail.com<br>ahmed.fawzy@ci.menofia.edu.eg
