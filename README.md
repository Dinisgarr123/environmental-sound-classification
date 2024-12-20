# Environmental Sound Classification

## Description
This project implements an **Environmental Sound Classification** system using transfer learning and supervised learning techniques. The pre-trained **YAMNet** model is used for feature extraction, and a **Random Forest Classifier** is employed for sound classification. The approach focuses on classifying audio samples from the **ESC-50** dataset into 50 different environmental sound categories.

## Installation
To run the project, ensure you have Python installed along with the required libraries.

### Prerequisites
Install the following dependencies:

```bash
pip install -r requirements.txt
```

The `requirements.txt` file should include:
```
tensorflow
tensorflow-hub
numpy
scikit-learn
librosa
matplotlib
```

## Usage
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/environmental-sound-classification.git
   ```

2. Navigate to the project directory:
   ```bash
   cd environmental-sound-classification
   ```

3. Run the script:
   ```bash
   python main.py
   ```

4. View the results, including metrics and cross-validation scores.


The dataset should be placed in the appropriate directory. Update the `main.py` script to point to your dataset location.


## Instructions to Access Code
The complete code and instructions for running the project are available in this repository. Visit the repository on GitHub:
[https://github.com/your-username/environmental-sound-classification](https://github.com/your-username/environmental-sound-classification)

##
- `Transfer_learning_GA03.ipynb`: Interactive notebook with explanation and sections.
- `transfer_learning_ga03 (1).py`: Linearized source code for direct execution.
