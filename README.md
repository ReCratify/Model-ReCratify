<h1 align="center"><b>ReCratify Machine Learning Model</b></h1>
<p align="center">
This is the documentation for the ReCratify Machine Learning Model. It is a part of the Capstone Project "ReCratify" by C241-PS077 Bangkit Academy 2024 Batch 1.
</p>
## Tech We Use

- **Numpy**: Scientific computing library
- **TensorFlow**: Machine learning library
- **Matplotlib**: Plotting library
- **Pandas**: Data manipulation and analysis library
- **Seaborn**: Statistical data visualization library

## Getting Started

1. **Clone this repository:**

   ```bash
   git clone https://github.com/ReCratify/Model-ReCratify.git
   ```

2. **Install the required dependencies**
   ```bash
    pip install -r requirements.txt
   ```

#### Steps to create a ReCratify model:

<div style="background-color: black; color: white; padding: 10px; border-radius: 5px; font-family: Arial, sans-serif;">
1. <b>Import Required Libraries:</b><br>
   Import the necessary libraries for the machine learning model.<br><br>
2. <b>Define Dataset Main Path:</b><br>
   Specify the dataset path.<br><br>
3. <b>Split Dataset (Training, Validation, and Test):</b><br>
   Split the dataset to get the training set (80%), validation set (10%), and test set (10%).<br><br>
4. <b>Determine the Number of Data for Each Directory:</b><br>
   Identify the total number of data for each directory (train, valid, test).<br><br>
5. <b>Display Labels in Each Directory:</b><br>
   Show the labels present in each directory.<br><br>
6. <b>Augment the Dataset:</b><br>
   Before classifying using a machine learning model, augment the dataset, especially for training and validation data.<br><br>
7. <b>Build a Classification Model:</b><br>
   Define the architecture of the model. In this case, use a Convolutional Neural Network (CNN) algorithm and Transfer Learning (DenseNet121).<br><br>
8. <b>Display Model Summary:</b><br>
   Show the summary of the model architecture.<br><br>
9. <b>Compile the Model:</b><br>
   Compile the model, specify the optimizer, loss function, and required metrics.<br><br>
10. <b>Train the Model:</b><br>
    Train the model by defining the steps per epoch and validation according to requirements for optimal results.<br><br>
11. <b>Plot Accuracy Results:</b><br>
    Map the accuracy results from the training and validation data to assess the classification model's performance.<br><br>
12. <b>Test the Model:</b><br>
    Test the model using the test data and observe the accuracy results.<br><br>
13. <b>Save Trained Model:</b><br>
    Save the trained model in an h5 file for deployment purposes.<br><br>
14. <b>Validation Using Picture Files on Test Set:</b><br>
    Validate the model by using pictures from the test set to make predictions and check if the image file has been predicted correctly.<br>
</div>
