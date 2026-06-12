# RetiNova - AI-Powered Retinal Disease Detection Platform

<div align="center">

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Frontend: HTML/CSS/JS](https://img.shields.io/badge/Frontend-HTML/CSS/JS-blue.svg)
[![Server: Node.js](https://img.shields.io/badge/Server-Node.js-green.svg)]
[![Framework: Express.js](https://img.shields.io/badge/Framework-Express.js-orange.svg)]

</div>

<div align="center">


### Your retina knows more than you think.

AI-assisted retinal image analysis for early ocular and systemic disease risk assessment.

</div>

---

# Overview

RetiNova is a computer vision and healthcare AI project that explores the use of retinal fundus images for disease screening and risk assessment.

The platform combines deep learning models with a browser-based clinical workflow to support:

* retinal image upload
* automated image preprocessing
* CNN-based disease prediction
* simulated polygenic risk integration
* clinician-oriented visualization
* structured patient risk reporting

The project aims to demonstrate how retinal imaging and machine learning can be integrated into accessible decision-support systems.

---

# System Architecture

```
Retinal Fundus Image

        │

        ▼

Image Validation

        │

        ▼

Image Preprocessing

        │

        ▼

CNN Feature Extraction

        │

        ▼

Disease Prediction

        │

        ▼

PRS-Based Risk Correlation

        │

        ▼

Risk Report Generation

        │

        ▼

Clinician Dashboard
```

---

# Features

* Retinal image upload and validation

* CNN-based disease prediction

* Multi-condition screening

* Simulated Polygenic Risk Score integration

* Clinician dashboard

* Structured patient risk reports

* Interactive browser interface

* Modular backend architecture

---

# AI Pipeline

The inference workflow consists of:

## 1. Image Acquisition

Retinal fundus images are uploaded through the web interface.

## 2. Image Processing

Input images undergo preprocessing and normalization.

## 3. Feature Extraction

Deep convolutional neural networks extract retinal features.

Architectures explored include:

* ResNet

* DenseNet

* EfficientNet

## 4. Disease Prediction

Extracted features are used for multi-condition prediction.

## 5. Genetic Correlation

Simulated Polygenic Risk Score information is incorporated for exploratory genotype-phenotype analysis.

## 6. Risk Reporting

Predictions are aggregated into clinician-friendly outputs.

---

# Diseases Covered

Current disease categories include:

| Condition                        |
| -------------------------------- |
| Age-related Macular Degeneration |
| Diabetic Retinopathy             |
| Glaucoma                         |
| Hypertensive Retinopathy         |
| Optical Neuropathy               |
| Retinal Vein Occlusion           |
| Retinal Tears / Detachments      |
| Normal Retina                    |

---

# Results

## Per-Class Accuracy

| Class                       | Accuracy |
| --------------------------- | -------- |
| AMD                         | 96.81%   |
| Diabetic Retinopathy        | 100.00%  |
| Glaucoma                    | 98.20%   |
| Hypertensive Retinopathy    | 97.39%   |
| Normal                      | 0.20%    |
| Optical Neuropathy          | 95.79%   |
| Retinal Vein Occlusion      | 91.46%   |
| Retinal Tears / Detachments | 99.17%   |

The above results were obtained during experimental evaluation of the classification pipeline and are intended for research purposes.

---

# Technology Stack

| Layer            | Technology                            |
| ---------------- | ------------------------------------- |
| Frontend         | HTML5, CSS3, Tailwind CSS, JavaScript |
| Backend          | Node.js, Express.js                   |
| Machine Learning | TensorFlow.js                         |
| Deep Learning    | ResNet, DenseNet, EfficientNet        |
| Risk Analysis    | Simulated PRS Integration             |
| Deployment       | Browser-based demonstration           |

---

# Web Application

The platform provides:

## Authentication

* Login

* Registration

* User workflow

## Dashboard

* Patient overview

* AI predictions

* Risk summaries

## Image Upload

* Retinal image submission

* Validation

* Processing

## Results

* Disease predictions

* Risk visualization

* Clinical recommendations

* Printable reports

---

# Backend Design

The backend is implemented using Node.js and Express.js.

Core responsibilities include:

* request handling

* image ingestion

* inference workflow coordination

* response generation

* dashboard integration

The architecture is modular to support future expansion of inference capabilities.

---

# Project Structure

```
retinova/

├── login/
├── dashboard/
├── upload/
├── analysis/
├── recommendations/
├── reports/

├── server.js

├── package.json

└── README.md
```

---

# Running Locally

## Requirements

* Node.js

* npm

## Installation

```
git clone <repository>

cd retinova

npm install

npm start
```

Open:

```
http://localhost:3000
```

---

# Current Status

Implemented:

* Frontend workflow

* Node.js backend

* CNN integration

* Simulated PRS integration

* Dashboard

* Reporting pipeline

* Browser-based demonstration

Under active development:

* Expanded live inference capabilities

* Larger datasets

* Additional retinal conditions

* Improved multimodal fusion

---

# Current Limitations

* Intended for research and educational use.

* Predictions are not clinical diagnoses.

* Performance depends on image quality and dataset diversity.

* Additional validation across larger datasets is required.

---

# Future Work

* Real-time inference improvements

* Explainable AI visualizations

* Expanded multimodal learning

* Enhanced PRS integration

* Larger validation datasets

* Mobile screening workflows

---

# Contributing

Contributions and suggestions are welcome.

Feel free to open issues or submit pull requests.

---

# License

This project is licensed under the MIT License.

---

<div align="center">

## RetiNova

### Advancing retinal imaging research through machine learning.

</div>
