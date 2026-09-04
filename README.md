# Generative AI Lab

A structured collection of **Generative AI laboratory assignments** implemented using Python, PyTorch, Pandas, Matplotlib, and Seaborn. The repository covers data analysis, exploratory data analysis, Generative Adversarial Networks (GANs), model architecture inspection, and forward-pass testing.

---

## 📌 Overview

This repository contains practical implementations developed as part of the **Generative AI** laboratory course for the B.Tech. Artificial Intelligence & Machine Learning program.

The work progresses from foundational dataset analysis to implementing and inspecting GAN architectures using the **MNIST handwritten digit dataset**.

### Course Information

| Field             | Details            |
| ----------------- | ------------------ |
| **Course**        | Generative AI      |
| **Course Code**   | R1UD702B           |
| **Program**       | B.Tech. (AIML)     |
| **Semester**      | 7th                |
| **Academic Year** | 2026–27            |
| **Student**       | Rudra Pratap Singh |
| **Roll No.**      | 23SCSE1180423      |

---

## 📂 Repository Structure

```text
Generative-AI-Lab/
│
├── 23SCSE1180423_RudraPratapSingh_Lab01A.ipynb
├── 23SCSE1180423_RudraPratapSingh_Lab01B.ipynb
├── 23SCSE1180423_RudraPratapSingh_Lab01_Iris.ipynb
├── 23SCSE1180423_RudraPratapSingh_Lab04.ipynb
├── 23SCSE1180423_RudraPratapSingh_Lab05.ipynb
│
├── iris.csv
├── titanic.csv
└── README.md
```

---

## 🧪 Laboratory Assignments

### Lab 01A — Data Wrangling & Exploratory Data Analysis

Focuses on working with structured datasets using Pandas and performing fundamental data-analysis operations.

**Key concepts:**

* Dataset loading
* Data inspection
* Data types and dimensions
* Missing-value analysis
* Duplicate detection
* Data cleaning
* Basic exploratory analysis

---

### Lab 01B — Titanic Dataset Analysis

Performs exploratory analysis on the **Titanic passenger dataset**.

**Key concepts:**

* Passenger data exploration
* Missing-value handling
* Duplicate removal
* Statistical calculations
* Survival analysis
* Gender-based survival comparison
* Histograms and bar charts
* Data-driven observations

---

### Lab 01 — Iris Dataset Analysis

Explores the classic **Iris flower dataset** using Pandas and visualization libraries.

**Key concepts:**

* Statistical summary
* Mean, median, minimum and maximum
* Species-wise grouping
* Feature comparison
* Petal-length analysis
* Histograms
* Boxplots
* Scatter plots
* Exploratory data analysis

---

### Lab 04 — Basic GAN Implementation

Implements and trains a basic **Generative Adversarial Network (GAN)** using the MNIST handwritten digit dataset.

**Key concepts:**

* Random latent noise
* Generator architecture
* Discriminator architecture
* Binary Cross Entropy loss
* Adam optimizer
* Adversarial training
* Synthetic image generation
* Generator and Discriminator loss visualization

The GAN is trained for at least 10 epochs and the generated images are visualized using a 4×4 grid.

---

### Lab 05 — GAN Architecture & Forward-Pass Testing

Focuses on understanding and inspecting the internal architecture of a GAN without performing adversarial training.

**Key concepts:**

* 100-dimensional latent vectors
* Generator architecture
* Discriminator architecture
* Trainable parameter calculation
* Tensor dimensions
* Forward-pass testing
* Real vs. generated image discrimination
* End-to-end GAN data flow
* Generated image visualization

The complete pipeline is tested as:

```text
Noise
   ↓
Generator
   ↓
Generated Image
   ↓
Discriminator
   ↓
Probability Output
```

---

## 🛠️ Technologies & Tools

* **Python**
* **Google Colab / Jupyter Notebook**
* **PyTorch**
* **Torchvision**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**

---

## 📊 Datasets

### Iris Dataset

Used for statistical analysis, feature comparison, grouping, and exploratory visualization.

Main features include:

```text
Sepal Length
Sepal Width
Petal Length
Petal Width
Species
```

### Titanic Dataset

Used for data cleaning, statistical analysis, and survival-based exploratory analysis.

Important attributes include:

```text
Survived
Pclass
Sex
Age
Fare
Embarked
```

### MNIST Dataset

Used for GAN implementation and architecture testing.

MNIST contains grayscale handwritten digit images representing digits **0–9**, with each image having a resolution of **28 × 28 pixels**.

---

## 🚀 Running the Notebooks

### Option 1 — Google Colab

1. Open Google Colab.
2. Upload the required `.ipynb` file.
3. Run the notebook from top to bottom.
4. Verify that all outputs and visualizations are generated.
5. Save/export the completed notebook.

### Option 2 — Local Jupyter Environment

Install the required dependencies:

```bash
pip install torch torchvision pandas numpy matplotlib seaborn jupyter
```

Then launch Jupyter:

```bash
jupyter notebook
```

Open the required notebook and execute the cells sequentially.

---

## 🎯 Learning Outcomes

Through these laboratory exercises, the following practical skills are demonstrated:

* Data preprocessing and cleaning
* Exploratory data analysis
* Statistical feature analysis
* Data visualization
* Working with real-world datasets
* Understanding neural-network architectures
* Implementing GAN components using PyTorch
* Understanding Generator–Discriminator interaction
* Tensor-shape analysis
* Forward-pass testing
* Synthetic image generation

---

## 📈 GAN Architecture

The basic GAN implemented in this repository consists of two competing neural networks:

### Generator

The Generator receives a random latent vector and attempts to create realistic-looking images.

```text
Random Noise (100)
        ↓
    Generator
        ↓
  28 × 28 Image
```

### Discriminator

The Discriminator receives an image and estimates whether it is real or generated.

```text
28 × 28 Image
      ↓
Discriminator
      ↓
Probability
```

Together, these networks form the fundamental adversarial architecture of a GAN.

---

## 📌 Submission Notes

Each notebook is designed to contain:

* Clearly labelled questions
* Executable Python code
* Visible outputs
* Properly labelled visualizations
* Observations
* Conclusions

The notebooks should be executed **end-to-end before submission** so that all outputs are stored correctly.

---

## 👨‍💻 Author

**Rudra Pratap Singh**
B.Tech. — Artificial Intelligence & Machine Learning
Galgotias University
Roll No. — `23SCSE1180423`

---

## ⭐ Repository Purpose

This repository serves as a practical record of Generative AI laboratory work, demonstrating the progression from **data analysis and visualization to Generative Adversarial Network implementation and architecture analysis**.
