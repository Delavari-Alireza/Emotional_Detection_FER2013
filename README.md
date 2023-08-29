# Facial Expression Recognition using Deep Neural Networks

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

## Abstract

The ability for emotional interaction stands as a paramount concern in shaping the dynamics between machines and humans, with the accurate perception of facial expressions emerging as a pivotal skill in this interplay. However, achieving precise facial expression recognition proves to be a formidable challenge due to the intricate nature of facial states and the myriad of influential factors at play.

This research endeavors to discern seven fundamental emotions (anger, disgust, fear, sadness, surprise, neutrality, happiness) by analyzing individuals' facial expressions through the utilization of deep neural networks. To facilitate this, the FER-2013 dataset, comprising real-world images and accounting for factors like gender, age, and ethnicity, is harnessed.

## Project Overview

This project aims to develop and evaluate deep neural network models for facial expression recognition. The key highlights of the project include:

- Utilization of the FER-2013 dataset, incorporating real-world images with diverse attributes.
- Implementation of five sets of experiments, each located in different folders:
  1. [1 - ResNet](1%20-%20ResNet): Basic ResNet architecture.
  2. [2 - resnetLike without convBlock](2%20-%20resnetLike%20without%20convBlock): ResNet-like architecture without convolutional blocks.
  3. [3 - resnetLike with dropout](3%20-%20resnetLike%20with%20dropout): ResNet-like architecture with dropout layers.
  4. [4 - defeat underfitting](4%20-%20defeat%20underfitting): Strategies to mitigate underfitting.
  5. [5 - EfficientNet](5%20-%20EfficientNet): Implementation using the EfficientNet architecture.
- Rigorous evaluation and comparison of model performance using the FER-2013 dataset.
- Achievement of noteworthy accuracy rates for emotion recognition.

## Installation

To run the Jupyter Notebook experiments and replicate the results, follow these steps:

1. Clone this repository: `git clone https://github.com/yourusername/your-repo.git`
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
