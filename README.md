# Food-Classifier


## Project Overview
This project aims to develop a high-performing deep learning model to classify food images into various categories using the Food101 dataset. It leverages advanced techniques like transfer learning, mixed precision training, and optimized data pipelines to achieve competitive accuracy and efficiency, surpassing benchmarks such as the DeepFood paper's 77.4% accuracy.

## Features
- Classification of food images into 101 categories.
- Implementation of transfer learning using EfficientNetB0.
- Use of TensorFlow Datasets for data loading and preprocessing.

## Dataset
- **Source**: Food101 dataset available through TensorFlow Datasets.
- **Structure**:
  - 75,750 training images.
  - 25,250 testing images.
- Includes 101 food categories.

## Requirements
### Software and Libraries
- Python 3.8 or newer
- TensorFlow 2.4 or newer (preferably tf-nightly for latest features)
- NumPy
- Matplotlib
- Pandas
- Scikit-learn

### Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/username/food-vision-project.git
   cd food-vision-project
   ```
2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```

## How to Run the Project
1. **Prepare the Dataset**: The Food101 dataset will be automatically downloaded using TensorFlow Datasets.
2. **Train the Model**:
   - Execute the training pipeline in the provided Jupyter notebook.
   - Leverage the feature extraction phase followed by fine-tuning.
3. **Evaluate the Model**: Evaluate the model on the test set and compare the results to benchmarks.
4. **Use the Model**: Save the model and use it for inference or deployment.
