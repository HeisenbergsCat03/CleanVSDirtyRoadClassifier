# Clean vs Dirty Road Classifier
This project is a TensorFlow-based Convolutional Neural Network (CNN) designed to classify images of roads as either "clean" or "dirty". The model has been trained on a dataset of road images and has achieved a training set accuracy of 96.3% and a test set accuracy of 95.83%. F1 score obtained was 0.95

To use the model, simply provide an image of a road and run it through the trained model to obtain its classification. You can also use the pre-trained weights to fine-tune the model for your specific use case.

Data augmentation - Each image has been both horizontally flipped and rotated by an angle -> effectively for 1 image we get 2 extra images hence the dataset has been tripled.
I had first made this model in Feb 2023, but I changed some accuracy metrics recently in Jul 2023.
