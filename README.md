# 🌸 Iris Flower Clustering Project

## 📌 Project Overview

This project applies **Unsupervised Machine Learning** techniques to the famous **Iris Flower Dataset**.

The main objective is to group Iris flowers into three clusters using the **K-Means Clustering algorithm** without using the actual flower species during clustering.

**PCA (Principal Component Analysis)** is also applied to reduce the dataset from 4 dimensions to 2 dimensions, making it easier to visualize the clusters.

---

## 🎯 Objectives

* Load and explore the Iris dataset
* Standardize the dataset features
* Apply **K-Means Clustering** with `k = 3`
* Visualize the generated clusters
* Apply **PCA** for dimensionality reduction
* Visualize the PCA-transformed dataset
* Compare predicted clusters with the actual Iris labels

---

## 📊 Dataset

The project uses the **Iris Dataset** containing 150 flower samples.

Each sample has four features:

| Feature      | Description         |
| ------------ | ------------------- |
| Sepal Length | Length of the sepal |
| Sepal Width  | Width of the sepal  |
| Petal Length | Length of the petal |
| Petal Width  | Width of the petal  |

There are three actual Iris species:

* Iris Setosa
* Iris Versicolor
* Iris Virginica

The dataset contains:

* **150 samples**
* **4 features**
* **3 classes**

---

## 🧠 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Google Colab
* Jupyter Notebook

---

## 🔬 Machine Learning Techniques

### 1. K-Means Clustering

K-Means is an **unsupervised learning algorithm** that divides the data into a specified number of clusters.

In this project:

```text
Number of clusters (k) = 3
```

The algorithm groups the Iris samples based on the similarity of their feature values.

### 2. PCA

**Principal Component Analysis (PCA)** is used to reduce the dimensionality of the dataset.

The original dataset contains:

```text
4 features
```

After applying PCA:

```text
4 dimensions → 2 principal components
```

This allows the data to be visualized using a 2D scatter plot.

---

## ⚙️ Project Workflow

```text
Iris Dataset
      ↓
Data Loading
      ↓
Data Standardization
      ↓
K-Means Clustering
      ↓
Generate 3 Clusters
      ↓
Apply PCA
      ↓
Reduce 4 Dimensions → 2 Dimensions
      ↓
Visualize Clusters
      ↓
Compare with True Labels
```

---

## 📈 Results

K-Means successfully divides the Iris dataset into **three clusters**.

PCA reduces the original four-dimensional feature space to two principal components while retaining a large portion of the information in the dataset.

The cluster visualization helps show the natural grouping of Iris samples and allows comparison with their actual species labels.

> **Note:** K-Means cluster numbers are arbitrary. For example, cluster `0` does not necessarily correspond to Iris Setosa. Therefore, cluster numbers should not be directly interpreted as species labels without mapping them.

---

## 📁 Project Structure

```text
Iris-Flower-Clustering/
│
├── Iris_Flower_Clustering.ipynb
├── README.md
└── requirements.txt
```

---

## ▶️ How to Run

### Using Google Colab

1. Open Google Colab.
2. Upload `Iris_Flower_Clustering.ipynb`.
3. Run the notebook cells sequentially.
4. View the K-Means and PCA visualizations.

### Using Jupyter Notebook

Clone the repository:

```bash
git clone <your-github-repository-link>
```

Open the project folder:

```bash
cd Iris-Flower-Clustering
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

Run the notebook:

```bash
jupyter notebook
```

---

## 📦 Requirements

Create a `requirements.txt` file containing:

```text
numpy
pandas
matplotlib
scikit-learn
```

---

## 💡 Key Learning Outcomes

Through this project, I learned:

* Basics of **Unsupervised Machine Learning**
* K-Means clustering
* Choosing the number of clusters
* Data standardization
* Principal Component Analysis (PCA)
* Dimensionality reduction
* Data visualization using Matplotlib
* Comparing unsupervised clusters with known labels

---

## 🚀 Future Improvements

* Experiment with different values of `k`
* Use the Elbow Method to determine an appropriate number of clusters
* Calculate silhouette score
* Compare K-Means with other clustering algorithms such as DBSCAN and Hierarchical Clustering
* Build an interactive visualization

---

## 👩‍💻 Author

**Anuradha Dollin**

ECE Student | AI/ML Enthusiast

---

## 📜 License

This project is created for educational and learning purposes.
