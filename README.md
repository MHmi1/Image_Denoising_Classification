# Image Denoising and Classification model 
Final project of computer vision course 


We have used for classification from these deep models : 
<p>1- CNN
<p>2- VGG 16
<p>3- AlexNet
<p>4- ResNet 50
<p>5- Inception V3

<p> We have used Noise detection and reduction from these deep models: 
<p>-VGG16 and InceptionV3 for noise type detection
<p>- Deep Autoencoder model for periodic and Gaussian noise reduction 
<p>- Median filter (kernel size=3)  for salt and pepper noise reduction 

<p> Result of binary classification models :
<p> Our metrics are:  Accuracy, Sensitivity, Specificity, and F-1 Score 
<p> <img src="https://s8.uupload.ir/files/binary_classification_report_435r.png">
   
  
<p> Result of denoiser models :
<p> Our metrics are: PSNR, SSIM, LPIPS
<p> <img src="https://s8.uupload.ir/files/median-filter-result_5gwf.png">
<p> <img src="https://s8.uupload.ir/files/gaussian-filter-result_pyup.png">
<p> <img src="https://s8.uupload.ir/files/periodic-filter-result_sm61.png">

<p> Result of binary classification after applying denoiser models with VGG16 :
<p> Our metrics are:  Accuracy, Sensitivity, Specificity, and F-1 Score 



By Mohsen Hami , Mahdi Jamebozorg
