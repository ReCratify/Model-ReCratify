<h1 align="center">**ReCratify Machine Learning Model**</h1>
This is the documentation for the ReCratify Machine Learning Model. It is a part of the Capstone Project "ReCratify" by C241-PS077 Bangkit Academy 2024 Batch 1.

### Tech We Use

`markdown

- Numpy (Scientific computing library)
- TensorFlow (Machine learning library)
- Matplotlib (Plotting library)
- Pandas (Data manipulation and analysis library)
- Seaborn (Statistical data visualization library)
  `

## Getting Started

1. Clone this repository
   ```bash
   git clone https://github.com/ReCratify/Model-ReCratify.git
   ```
2. Install the required dependencies
   ```bash
    pip install -r requirements.txt
   ```

#### Steps to create a ReCratify model:

`markdown

1. **Import Required Libraries:**
   Import the necessary libraries for the machine learning model.
2. **Define Dataset the Main Path:**
   Specify the dataset path.
3. **Split Dataset (Training, Validation, and Test):**
   By Spliting the dataset to get the training set 80%, validation set 10%, and test set 10%.
4. **Determine the Number of Data for Each Directory:**
   Identify the total number of data for each directory (train, valid, test).
5. **Display Labels in Each Directory:**
   Show the labels present in each directory.
6. **Augment the Dataset:**
   Before classifying using a machine learning model, augment the dataset, especially for training and validation data.
7. **Build a Classification Model:**
   Define the architecture of the model. In this case, use a Convolutional Neural Network (CNN) algorithm and using Transfer Learning (DenseNet121).
8. **Display Model Summary:**
   Show the summary of the model architecture.
9. **Compile the Model:**
   Compile the model, specify the optimizer, loss function, and required metrics.
10. **Train the Model:**
    Train the model by defining the steps per epoch and validation according to requirements for optimal results.
11. **Plot Accuracy Results:**
    Map the accuracy results from the training and validation data to assess the classification model's performance.
12. **Test the Model:**
    Test the model using the test data and observe the accuracy results.
13. **Save Trained Model:**
    Save the trained model in an h5 file for deployment purposes.
14. **Validation using Pictures files on test set:**
    To validate the model by using pictures on test set to make predictions and check if the image file has been predicted correctly.
    `
