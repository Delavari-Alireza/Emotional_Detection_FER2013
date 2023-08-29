# Facial Expression Recognition using Deep Neural Networks

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

## Abstract

Emotional interaction capability stands as a pivotal concern in determining the nature and extent of interactions between machines and humans. Understanding facial expressions constitutes a key skill in advancing such interactions. Accurate facial expression recognition is a formidable challenge due to the intricacies and variability of facial states, as well as diverse influencing factors.

In this study, the objective is to recognize seven basic emotions (anger, disgust, fear, sadness, surprise, neutrality, happiness) based on individuals' facial expressions using deep neural networks. To achieve this goal, the FER-2013 dataset, compiled from natural images, encompassing factors such as gender, age, ethnicity, etc., has been utilized.

Three models based on the ResNet34 neural network architecture and two variants of EfficientNet, recognized as prominent neural network architectures, have been constructed and experimented on the aforementioned dataset. Ultimately, accuracy rates of 63.97%, 65.71%, 64.73%, 64.32%, and 64.18%, which are notably high considering the dataset complexity, have been achieved.
## Project Overview

This project aims to develop and evaluate deep neural network models for facial expression recognition. The key highlights of the project include:

- Utilization of the FER-2013 dataset, incorporating real-world images with diverse attributes.
- Implementation of five sets of experiments, each located in different folders:
  1. [1 - ResNet](1%20-%20Resnet): Basic ResNet architecture.
  2. [2 - resnetLike without convBlock](2%20-%20resnetLike%20without%20convBlock): ResNet-like architecture without convolutional blocks.
  3. [3 - resnetLike with dropout](3%20-%20resnetLike%20with%20dropout): ResNet-like architecture with dropout layers.
  4. [4 - defeat underfitting](4%20-%20%20defeat%20underfitting): Strategies to mitigate underfitting.
  5. [5 - EfficientNet](5-%20efficientNet): Implementation using the EfficientNet architecture.
- Rigorous evaluation and comparison of model performance using the FER-2013 dataset.
- Achievement of noteworthy accuracy rates for emotion recognition.

## Installation

To run the Jupyter Notebook experiments and replicate the results, follow these steps:

1. Clone this repository: `git clone https://github.com/Alireza499/Emotional_Detection_FER2013.git`
2. Install the required dependencies: `pip install -r requirements.txt`
3. Navigate to the specific experiment folder you want to explore.
4. Launch Jupyter Notebook: `jupyter notebook`
5. Open the notebook containing the experiment code.

## Results

The culmination of this research effort yields the following accuracy rates for emotion recognition:

- ResNet34 Model 1: 63.97%
- ResNet34 Model 2: 65.71%
- ResNet34 Model 3: 64.73%
- EfficientNet Model 1: 64.32%
- EfficientNet Model 2: 64.18%

These results underscore the effectiveness of the developed models, especially considering the complexities inherent in the FER-2013 dataset.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

We would like to express our gratitude to the authors of the FER-2013 dataset for providing valuable data for our research.

For more details and insights, please refer to the Jupyter Notebooks in the respective experiment folders.

---

Feel free to explore the notebooks, contribute to the project, or use the models for your own applications!
