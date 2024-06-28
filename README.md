# Obesity Classification Project

## Overview
This project aims to classify individuals into one of six obesity levels using advanced machine learning techniques. The project leverages binary encoding and neural networks to achieve high accuracy in predicting obesity levels based on various health and lifestyle factors.

## Table of Contents
- [Project Overview](#overview)
- [Dataset](#dataset)
- [Techniques and Tools](#techniques-and-tools)
- [Model Architecture](#model-architecture)
- [Results](#results)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Overview
The primary objective of this project is to classify obesity levels into:
- Insufficient Weight
- Normal Weight
- Overweight Level I
- Overweight Level II
- Obesity Type I
- Obesity Type II
- Obesity Type III

## Dataset
The dataset includes features such as age, physical activity, and dietary habits. It is sourced from [provide source if available].

## Techniques and Tools
- **Data Cleaning and Preparation**: Addressed duplicates and ensured data consistency.
- **Binary Encoding**: Transformed obesity levels into three binary columns for efficient representation.
- **Normalization**: Applied Min-Max scaling to normalize feature values.
- **Neural Network**: Built using Keras with multiple hidden layers.
- **Loss Function**: Binary cross-entropy used for optimized performance.

## Model Architecture
- Input Layer
- Three Hidden Layers (ReLU activation)
- Output Layer (Sigmoid activation)

## Results
- **Accuracy**: Achieved 85% accuracy with binary cross-entropy.
- **Evaluation**: High precision and recall, validated through confusion matrices and classification reports.

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Obesity-Classification-Project.git

