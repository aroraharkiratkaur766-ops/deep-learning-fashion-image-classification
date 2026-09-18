# Deep Learning – Fashion Image Classification

## 📌 Project Overview

This project demonstrates how **Deep Learning and Artificial Neural Networks** can be used to classify fashion product images automatically.

The project uses the **Fashion MNIST dataset** and a simple neural network built using **TensorFlow/Keras**.

The business scenario is based on an **e-commerce company** that receives thousands of product images and needs to categorize them efficiently.

---

## 🎯 Objective

The main objectives of this project are to:

* Understand how images are used as input for Deep Learning.
* Build a simple Artificial Neural Network.
* Understand input, hidden, and output layers.
* Train a model using labelled product images.
* Evaluate model accuracy.
* Predict the category of new product images.
* Understand the business application of image classification.

---

## 📊 Dataset

The project uses the **Fashion MNIST dataset**.

It contains images of 10 different fashion product categories:

1. T-shirt/Top
2. Trouser
3. Pullover
4. Dress
5. Coat
6. Sandal
7. Shirt
8. Sneaker
9. Bag
10. Ankle Boot

Each image is a **28 × 28 grayscale image**.

---

## 🧠 Model Architecture

The project uses a simple Artificial Neural Network:

**Input Image → Flatten Layer → Hidden Layer → Output Layer**

### Layers Used

* **Flatten:** Converts the 28 × 28 image into a one-dimensional input.
* **Dense Layer:** Contains 64 neurons and uses the **ReLU** activation function.
* **Output Layer:** Contains 10 neurons, one for each product category.
* **Softmax:** Produces probabilities for the 10 possible categories.

---

## ⚙️ Data Preprocessing

The original pixel values range from **0 to 255**.

They are normalized to values between **0 and 1** to make the image data easier for the neural network to process.

---

## 🏋️ Model Training

The model is compiled using:

* **Optimizer:** Adam
* **Loss Function:** Sparse Categorical Crossentropy
* **Evaluation Metric:** Accuracy
* **Epochs:** 3
* **Validation Split:** 10%

The model is then evaluated using test images that were not used during training.

---

## 📈 Model Evaluation

The model calculates **test accuracy** to measure how many unseen images were classified correctly.

For example, if the model achieves 87% accuracy, approximately 87 out of 100 test images were classified correctly.

> The exact accuracy may vary slightly when the notebook is executed.

---

## 🔮 Prediction

After training, the model can predict the category of unseen fashion images.

The notebook displays:

* Product image
* Predicted category
* Actual category

Users can also change the image number to test different products.

---

## 💼 Business Application

### Traditional Process

Product Image
↓
Employee manually identifies category
↓
Product is added to website

### AI-Assisted Process

Product Image
↓
Deep Learning Model
↓
Predicted Product Category
↓
Human Review if Required
↓
Product added to website

### Possible Business Benefits

* Faster product listing
* Reduced repetitive manual work
* More consistent product categorization
* Improved product-search experience
* Ability to process a large number of images

---

## ⚠️ Limitations

The model may not classify every image correctly.

Before using such a system in a real business environment, companies should consider:

* Cost of incorrect classifications
* Customer experience
* Quality of training data
* Model accuracy
* Human review and oversight

---

## 🛠️ Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* Matplotlib
* Fashion MNIST
* Google Colab

---

## 📂 Project Structure

```text
deep-learning-fashion-image-classification/
│
├── Deep_Learning_Fashion_Image_Classification_BBA.ipynb
└── README.md
```

---

## 🚀 How to Run

1. Open the `.ipynb` notebook in **Google Colab** or Jupyter Notebook.
2. Run the required library imports.
3. Load the Fashion MNIST dataset.
4. Execute the cells in sequence.
5. Train the neural network.
6. Check the test accuracy.
7. Test different images and compare predicted and actual categories.

No manual dataset upload is required because Fashion MNIST is downloaded automatically through TensorFlow/Keras.

---

## 📚 Key Learning Outcomes

Through this project, we understand that:

* Deep Learning can identify patterns in images.
* Neural networks use input, hidden, and output stages.
* Training allows the model to learn from historical examples.
* Testing measures performance on unseen data.
* AI predictions are not always correct.
* Human oversight can remain important in business applications.

---

## 👩‍🎓 Academic Project

**Course:** Introduction to AI and ML
**Project:** Deep Learning – Fashion Image Classification
**Program:** BBA
**Platform:** Google Colab
