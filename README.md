
# A TensorFlow implementation of U-Net for aerial imagery semantic segmentation
<p align="center">
<kbd>
   <img align="center" src="https://user-images.githubusercontent.com/54831801/189468893-29420c1f-714b-40b1-86c4-49f9f78e1176.png" width="700" height="500">
</kbd>
</p>

## Description 
In this repo, we review the problem of semantic segmentation on unbalanced binary masks. We train the U-Net implemented in TensorFlow to perform semantic segmentation on aerial images. 

## Dataset
The dataset used here is “Semantic segmentation of aerial imagery” which contains 72 satellite images of Dubai, the UAE, and is segmented into 6 classes. The classes include water, land, road, building, vegetation, and unlabeled.
<p align="center">
<kbd>
   <img align="center" src="https://user-images.githubusercontent.com/54831801/189468915-d5f76ea4-f462-4cb1-a9ab-b26631a06c69.png" width="700" height="500">
</kbd>
</p>
Link to dataset is as follows:

[link](https://www.kaggle.com/datasets/humansintheloop/semantic-segmentation-of-aerial-imagery)
## U-Net Neural Network
U-Net is a convolutional neural network that originally was presented for biomedical image segmentation at the Computer Science Department of the University of Freiburg. It is based on fully convolutional neural networks and has a modified and extended architecture to work with fewer training images and yield more precise segmentation.
Link to the paper is as follows:

[link](https://arxiv.org/pdf/1505.04597v1.pdf)


## Result
We trained the U-Net on the mentioned dataset. It’s important to note that there were only 65 images for training and 7 images for validation, so we can’t expect great results. But this number of data is enough for our purpose.
<figure>
  <img
  src="https://user-images.githubusercontent.com/54831801/189468927-158c295f-24a3-4364-9118-61b6c9a8e9f9.png"
  alt="segmentation result.">
  <figcaption>MDN Logo</figcaption>
</figure>
