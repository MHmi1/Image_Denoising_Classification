# Image Denoising and Classification model 
**Final project of computer vision course** 

**We have used for classification from these deep models:** 
<p>1- CNN
<p>2- VGG16
<p>3- AlexNet
<p>4- ResNet50
<p>5- Inception V3

<p> We have used Noise detection and reduction from these deep models: 
<p>-VGG16 deep model for noise type detection in the frequency  domain 
<p>- Deep Autoencoder model for periodic and Gaussian noise reduction 
<p>- Median filter (kernel size=3)  for salt and pepper noise reduction 

**<p> Result of binary classification models:**
<p> Our metrics are:  Accuracy, Sensitivity, Specificity, and F-1 Score 
<p> <img src="https://s8.uupload.ir/files/binary_classification_report_435r.png">
   
  
**<p> Result of denoiser models :**
<p> Our metrics are: PSNR, SSIM, LPIPS
<p> <img src="https://s8.uupload.ir/files/median-filter-result_5gwf.png">
<p> <img src="https://s8.uupload.ir/files/gaussian-filter-result_pyup.png">
<p> <img src="https://s8.uupload.ir/files/periodic-filter-result_sm61.png">


<p> Final lap: investigating the effect of noise on image classification models
<p> Our metrics are:  Accuracy, Sensitivity, Specificity, and F-1 Score 
<p> <img src="https://s8.uupload.ir/files/vgg16-performance_m0w9.png" width=450 height=550>
<p> <img src="https://s8.uupload.ir/files/inceptionv3-performance-comparison_5ix3.png" width=450 height=550>

**Result: **
<p> <img src="https://s8.uupload.ir/files/image_2024-03-13_19-24-53_xire.png" width=750 height=320>
<p>Periodic noise reduction (using autoencoder) -> PSNR= 26
<p> <img src="https://s8.uupload.ir/files/image_2024-03-13_19-32-16_1e7o.png" width=750 height=320>
<p>Gaussian noise reduction (using autoencoder) -> PSNR= 28
   <p> <img src="https://s8.uupload.ir/files/image_2024-03-13_19-28-25_dhdk.png" width=750 height=320>
<p>salt and pepper noise reduction (using median filter) ->  PSNR= 35


By Mohsen Hami , Mahdi Jamebozorg
