📂 Part 1 – Data Analysis
Dataset Exploration

Count the number of classes and the number of images per class.

Import the images along with their labels (you can choose to use the original 28×28 arrays or flatten them into 784-dimensional vectors).

Visualizations

Display the first 10 images with their class names as titles.

Project the images (treated as 784-dimensional vectors) onto:

A scatter plot using the first 2 principal components (PCA).

A scatter plot using the first 2 discriminant axes (LDA).

A pairplot based on the 3 first PCA components and the 3 first LDA axes.

🛠 Part 2 – Classification Using a Dense Neural Network
Modeling

Build a dense neural network model with 2 hidden layers to prevent overfitting.

Training & Evaluation

Plot the evolution curves of the Loss function and Accuracy during training.

Display or plot the confusion matrix on the test set.

Visualize (if more than 10 cases, select a subset) the misclassified cases, including both the predicted and the true class labels.

🛠 Part 3 – Classification Using a Convolutional Neural Network (CNN)
CNN Modeling

Build a convolutional neural network inspired by LeNet-5, taking care to avoid overfitting.

Training & Evaluation

Plot the evolution curves of the Loss function and Accuracy during training.

Display or plot the confusion matrix on the test set.

Visualize (if more than 10 cases, select a subset) the misclassified examples, showing both the predicted and the true labels.

📊 Part 4 – Analysis and Conclusion
Model Comparison

Compare the performance of the dense network and the CNN.

Discuss the strengths and weaknesses of each approach, and propose potential improvements (e.g., hyperparameter tuning, regularization, data augmentation).

🛠 Technologies Used
Programming & Libraries:

Python, Keras/TensorFlow

Pandas, NumPy (data preprocessing)

Matplotlib, Seaborn (data visualization)

Scikit-learn (PCA, LDA, metrics, confusion matrix)

Dataset: Fashion MNIST

