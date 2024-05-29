# Semantic Segmentation of Images
Semantic image segmentation means labeling image regions with predefined classes of objects represented in that region. Autonomous self-driving vehicles is a trending field of research that requires semantic segmentation of roadside scenes
to discover drivable areas.  Inspired by deep learning, we have implemented popular deep Convolutional network architectures - **FCN8, U-Net, PSPNet, LINKNet, and DEEPLABV3+** for performing semantic segmentation of images using Indian Driving Dataset (IDD) (Lite). The performance of each of these models has been analyzed, among which DEEPLABV3+ produced a better accuracy when compared with the other networks.

# Dataset
**The Indian driving dataset** is an ideal dataset for road scene understanding in unstructured environments. The dataset consists of 10,004 images, annotated with 34 classes in 182 driving sequences on Indian roads and the dataset is properly diversified within the class labels. The dataset has been collected by attaching a camera to the front face of the car and the car was driven around Hyderabad and Bangalore cities and their outskirts. The dataset is properly segregated into training, validation and testing, and the input and output images have been provided for training and validation. For this research , we have used the Indian Driving Dataset (IDD) lite dataset, which categorized images into 8 basic categories: drivable, non drivable, living things, vehicles, roadside objects, far objects, sky and not for training (miscellaneous). Dataset has been taken from the Indian Driving Dataset (IDD) on Semantic segmentation of un-
structured driving scenarios of Indian roads. The original Indian driving dataset is very large in size and has a very large number of classes. For training our models, we have used IDD lite dataset that is less than 50 MB in size and has 7 classes. We have added the 8th class to classify miscellaneous objects.

# Results
| Architecture  | FCN    | UNET   | PSPNET | LINKNET | DEEPLABV3+ |
|---------------|--------|--------|--------|---------|------------|
| Training Set  | 0.9032 | 0.8784 | 0.9172 | 0.9231  | 0.8040     |
| Testing Set   | 0.9034 | 0.7406 | 0.7385 | 0.7579  | 0.7712     |
| Mean F1 score | 0.687  | 0.586  | 0.733  | 0.75    | 0.787      |

**Examples**
<br>
<div align="center">
  <img src="https://github.com/SaumyaGupta-99/Semantic-Segmentation-of-Images/blob/main/fcn8-results.png" alt="FCN8-Results">
  <p><em>FCN-8 Results</em></p>
</div>
<div align="center">
  <img src="https://github.com/SaumyaGupta-99/Semantic-Segmentation-of-Images/blob/main/UNet-results.png" alt="UNet-Results">
  <p><em>UNet Results</em></p>
</div>
<div align="center">
  <img src="https://github.com/SaumyaGupta-99/Semantic-Segmentation-of-Images/blob/main/PSPNET-results.png" alt="PSPNET-Results">
  <p><em>PSPNET Results</em></p>
</div>
<div align="center">
  <img src="https://github.com/SaumyaGupta-99/Semantic-Segmentation-of-Images/blob/main/Linknet-results.png" alt="LINKNET-Result">
  <p><em>LINKNET Result</em></p>
</div>
<div align="center">
  <img src="https://github.com/SaumyaGupta-99/Semantic-Segmentation-of-Images/blob/main/DeepLAbV3%2B.png" alt="DEEPLAbV3+-Results">
  <p><em>DEEPLABV3+ Results</em></p>
</div>

# Collaborator 
Girish Kulkarni: [@girish332](https://github.com/girish332)


