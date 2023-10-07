# Fish-Classification-VGG16
Deep learning project for classifying different types of fish species based on their images. The core of the project is a convolutional neural network (CNN) model built on the VGG16 architecture.

Which has been fine-tuned to achieve high accuracy in fish classification. Whether you're a marine biologist, a wildlife enthusiast, or just interested in image classification, this project provides a powerful tool for automatic fish species recognition.

# Key Features:

* Leverages the VGG16 architecture, a proven choice for image classification tasks.
* Offers a Jupyter notebook for model training and evaluation.
* Demonstrates transfer learning and fine-tuning techniques for optimal results.
* Utilizes visualization tools for analyzing model performance and prediction results.
* Allows you to experiment with hyperparameters and model configurations.

# About Dataset
***A Large-Scale Dataset for Segmentation and Classification***
* https://www.kaggle.com/datasets/crowww/a-large-scale-fish-dataset/
* Paper: https://ieeexplore.ieee.org/abstract/document/9259867

Authors: O. Ulucan, D. Karakaya, M. Turkan
Department of Electrical and Electronics Engineering, Izmir University of Economics, Izmir, Turkey
Corresponding author: M. Turkan
Contact Information: mehmet.turkan@ieu.edu.tr


***General Introduction***

This dataset contains 9 different seafood types collected from a supermarket in Izmir, Turkey
for a university-industry collaboration project at Izmir University of Economics, and this work
was published in ASYU 2020.
Dataset includes, gilt head bream, red sea bream, sea bass, red mullet, horse mackerel, 
black sea sprat, striped red mullet, trout, shrimp image samples. 

If you use this dataset in your work, please consider to cite:

@inproceedings{ulucan2020large,
  title={A Large-Scale Dataset for Fish Segmentation and Classification},
  author={Ulucan, Oguzhan and Karakaya, Diclehan and Turkan, Mehmet},
  booktitle={2020 Innovations in Intelligent Systems and Applications Conference (ASYU)},
  pages={1--5},
  year={2020},
  organization={IEEE}
}

* O.Ulucan , D.Karakaya and M.Turkan.(2020) A large-scale dataset for fish segmentation and classification.
In Conf. Innovations Intell. Syst. Appli. (ASYU)



***Data Gathering Equipment and Data Augmentation***

Images were collected via 2 different cameras, Kodak Easyshare Z650 and Samsung ST60. 
Therefore, the resolution of the images are 2832 x 2128, 1024 x 768, respectively.

Before the segmentation, feature extraction and classification process, the dataset was resized to 590 x 445
by preserving the aspect ratio. After resizing the images, all labels in the dataset were augmented (by flipping and rotating). 

At the end of the augmentation process, the number of total images for each class became 2000; 1000 for the RGB fish images
and 1000 for their pair-wise ground truth labels. 
 
