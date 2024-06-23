# Mask Detection Using Meta-Learning

## Overview

This project implements a mask detection system using Model-Agnostic Meta-Learning (MAML). The system is designed to classify images into three categories:
- Without mask
- With mask
- Mask worn incorrectly

The goal is to develop a model that can quickly adapt to new tasks with minimal training data, leveraging the principles of meta-learning.

## Project Structure

The project consists of the following main components:
1. **Data Loading and Preprocessing**: Reading images and their corresponding labels, converting images to grayscale, resizing them, and splitting the dataset into training and testing sets.
2. **Improved Neural Network Model**: A neural network with additional layers to enhance the model's ability to learn complex patterns.
3. **Meta-Learning Training Loop**: Implementing MAML to train the model across multiple tasks, enabling quick adaptation to new tasks.
4. **Evaluation**: Assessing the model's performance on various tasks and visualizing the results using classification reports and confusion matrices.

## Setup and Installation

### Prerequisites

- Python 3.x
- pip (Python package installer)

### Required Libraries

Install the necessary libraries using pip:

```bash
pip install -r requirements.txt
