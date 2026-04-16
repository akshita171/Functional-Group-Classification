
# Functional Group Classification from IR Spectra

##  Overview

This project focuses on classifying organic molecules into functional groups using their Infrared (IR) spectra. The goal is to build machine learning models that can automatically identify functional groups based on spectral patterns.

---

##  Motivation

Manual interpretation of IR spectra requires domain expertise and can be time-consuming. This project explores how machine learning can assist in automating functional group identification.

---

##  Dataset

* Source: NIST IR Spectral Database
* Spectra interpolated to a uniform wavenumber range (400–4000 cm⁻¹)
* Labels correspond to functional groups such as:

  * Alkane
  * Aromatic
  * Ketone
  * Amine
  * Ether

---

##  Methodology

### 1. Data Preprocessing

* Interpolation to fixed grid
* Normalization of spectra
* Label encoding of functional groups

### 2. Feature Engineering

* Spectral intensity values used as input features
* Focus on characteristic absorption regions

### 3. Models Used

*  Random Forest Classifier
*  Convolutional Neural Network (CNN) *(in progress)*

---

##  Results

* Strong performance for:

  * Alkane
  * Aromatic
* Confusion observed between:

  * Ketone vs Ester (due to similar C=O peaks)

---


##  Tech Stack

* Python
* NumPy, Pandas
* Scikit-learn
* TensorFlow / PyTorch (for CNN)
* Matplotlib

---


