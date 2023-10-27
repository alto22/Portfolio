# Bird_Sound_Classification


> MSc Business Administration and Data Science

> Submission Date: 19.05.23

## Data Download

- [Google Drive](https://1drv.ms/f/s!AiqIYDThiBNP4WLLT5VrUad6RpTG?e=1l5ab9)
- [OneDrive](https://1drv.ms/f/s!AiqIYDThiBNP4WLLT5VrUad6RpTG?e=1l5ab9)

## Authors
- Tommaso Ghisini
- Alexander Mealor
- Alexander Ries
- Aleksander Torp


## Abstract
The monitoring of bird species has the potential for meaningful application far beyond avian conservation efforts, including - but not limited to - environmental change and land usage. Historically onerous tracking efforts have become far less burdensome with the growth of crowd-sourced bird audio recordings and the ability to use this data for species classification. In this paper we address the problem of how such classification efforts can be best performed by applying machine learning techniques. Utilizing the BirdCLEF 2023 dataset, we implement three different models - a Random Forest Classifier (RF), a Convolutional Neural Network (CNN) and a Recurrent Convolutional Neural Network (RCNN) - that build upon audio classification tasks in an evolutionary way. Two different preprocessing pipelines are employed in order to explore different spatial and temporal aspects of audio data. We find that neural networks outperform traditional models with the CNN achieving an accuracy of 0.62. The RCNN performs even more strongly across pipelines on average, suggesting that the temporal features of audio should be utilized in machine learning techniques and particularly when audio is lengthier. Imbalanced data, however, remains a key challenge and requires addressing carefully in bird sound classification preprocessing pipelines. We recommend practitioners experiment with different augmentation techniques and handle noise and silence appropriately for optimal results.

Keywords: Bird audio classification, Convolutional Neural Network, Random Forest, Recurrent Convolutional Neural Network, Bioacoustics
