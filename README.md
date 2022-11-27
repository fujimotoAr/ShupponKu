# ShupponKu

## About
The repository of ShupponKu team, Gemastik XV. Our team consists of:
- Theofilus Arkhi S.
- Nur Alfi Laily
- Siti Muslimah K. H. N.
- Erwin Eko W. (supervisor)

## Context
We are one of the data mining competition participants in Gemastik XV. Our research is named "U-Net and Fully Convolutional Network for Forest Segmentation: A Comparative Study".

## Background
Nowadays, with the increase of population in Indonesia, deforestation are done in order to fulfill economic needs. Deforestation has adverse effects towards the environment such as global warming and the destruction of fauna habitat. With technological advances, forest aerial images can be taken with drones or satellites. Therefore, forest aerial segmentation from aerial images becomes a feasible way to monitor deforestation rate.
 
In our research, we compare various architectures for image segmentation tasks such as U-Net, FCN-16, and FCN-8 in order to find the best method for forest aerial segmentation. We hope that our research can be useful to monitor deforestation in Indonesia.

## Goals
Our research was done in order to:
1. To do forest area segmentation from aerial images
2. To find the best architecture for forest segmentation task

## Research flow
Our research was done with these following steps:
1. Dataset selection
2. Data understanding
3. Data preprocessing
4. Modeling
5. Model evaluation

## Results
The results of our research can be seen in these tables:

**Amazon dataset :**
|                             | U-Net | FCN-16 | FCN-8 |
|-----------------------------|-------|--------|-------|
| **IoU** | 79.63 | 74.63  | 83.38 |
| **Dice**         | 86.65 | 83.03  | 90.06 |
| **Accuracy**          | 93.65 | 90.24  | 94.18 |


**Forest Aerial Images dataset :**
|              | U-Net | FCN-16 | FCN-8 |
|--------------|-------|--------|-------|
| **IoU**      | 64.11 | 68.42  | 69.48 |
| **Dice**     | 73.57 | 76.57  | 77.53 |
| **Accuracy** | 77.08 | 76.06  | 79.83 |

## Conclusion
Based on our experiment, FCN-8 architecture gives the highest IoU, Dice, and pixel accuracy scores for both datasets. In the other hand, U-Net architecture can recognize forest areas not present in the labels. Therefore, we conclude that FCN-8 can recognize forest areas well given accurate labels, while U-Net can be used for data with less accurate labels.
## Google Colab
Link of the google colab (for interactive uses) can be viewed [here](https://drive.google.com/drive/folders/1IOgAyQgyVVqZGlQWIudsMyqSBRENCn8e?usp=sharing).

## Datasets
The datasets we're using can be accessed at [amazon](https://drive.google.com/drive/folders/1HaPL-I5-VC1ToCBXobUxo5RB8OE0uA_U?usp=sharing) and [forest](https://drive.google.com/file/d/1SebYZSanMQRiMZbbwOzAYUr5P7HQrHVv/view?usp=sharing).

The above datasets are from :
1. L. Bragagnolo, R. V. da Silva, and J. M. V. Grzybowski, “Amazon Rainforest dataset for semantic segmentation.” Zenodo, 27 May 2019. doi: 10.5281/ZENODO.3233081.
2. Q. Shaikh, “Forest Aerial Images for Segmentation,” June 2018. https://www.kaggle.com/datasets/quadeer15sh/augmented-forest-segmentation (accessed 21 September 2022).

## Code references
- [Tensorflow tutorial](https://www.tensorflow.org/tutorials/images/segmentation)
- [Kaggle 1](https://www.kaggle.com/code/quadeer15sh/how-to-perform-semantic-segmentation-using-u-net)
- [Kaggle 2](https://www.kaggle.com/code/codelad/fcn-transfer-learning-image-segmentation)
- [Kaggle 3](https://www.kaggle.com/code/minorii/notebookd7cb71e985)