## 📄 Assessing The Impact of CNN Auto Encoder-Based Image Denoising on Image Classification Tasks (https://arxiv.org/abs/2404.10664)

<p><b> Abstract: </p></b>
Images captured from the real world are often affected by different types of noise, which can significantly impact the performance of Computer Vision systems and the quality of visual data. This study presents a novel approach for defect detection in casting product noisy images, specifically focusing on submersible pump impellers. The methodology involves utilizing deep learning models such as VGG16, InceptionV3, and other models in both the spatial and frequency domains to identify noise types and defect status. The research process begins with preprocessing images, followed by applying denoising techniques tailored to specific noise categories. The goal is to enhance the accuracy and robustness of defect detection by integrating noise detection and denoising into the classification pipeline. The study achieved remarkable results using VGG16 for noise type classification in the frequency domain, achieving an accuracy of over 99%. Removal of salt and pepper noise resulted in an average SSIM of 87.9, while Gaussian noise removal had an average SSIM of 64.0, and periodic noise removal yielded an average SSIM of 81.6. This comprehensive approach showcases the effectiveness of the deep AutoEncoder model and median filter, for denoising strategies in real-world industrial applications. Finally, our study reports significant improvements in binary classification accuracy for defect detection compared to previous methods. For the VGG16 classifier, accuracy increased from 94.6% to 97.0%, demonstrating the effectiveness of the proposed noise detection and denoising approach. Similarly, for the InceptionV3 classifier, accuracy improved from 84.7% to 90.0%, further validating the benefits of integrating noise analysis into the classification pipeline.


<p> Proposed Auto-encoder model architecture: <p></p>
<p> <img src="https://s8.uupload.ir/files/auto_encoder_architecture_ergt.png">


**<p> ✅   Result of binary classification models:**
<p> Our metrics are:  Accuracy, Sensitivity, Specificity, and F-1 Score 
<p> <img src="https://s8.uupload.ir/files/binary_classification_report_435r.png">
   
  
**<p> ✅   Result of denoiser models :**
<p> Our metrics are: PSNR, SSIM, LPIPS
<p> <img src="https://s8.uupload.ir/files/median-filter-result_5gwf.png">
<p> <img src="https://s8.uupload.ir/files/gaussian-filter-result_pyup.png">
<p> <img src="https://s8.uupload.ir/files/periodic-filter-result_sm61.png">


<p> ✅  Final lap: investigating the effect of noise on image classification models
<p> Our metrics are:  Accuracy, Sensitivity, Specificity, and F-1 Score 
<p> <img src="https://s8.uupload.ir/files/vgg16-performance_m0w9.png" width=450 height=550>
<p> <img src="https://s8.uupload.ir/files/inceptionv3-performance-comparison_5ix3.png" width=450 height=550>

** 📄 Result: **
<p> <img src="https://s8.uupload.ir/files/image_2024-03-13_19-24-53_xire.png" width=750 height=320>
<p>Periodic noise reduction (using autoencoder) -> PSNR= 26
<p> <img src="https://s8.uupload.ir/files/image_2024-03-13_19-32-16_1e7o.png" width=750 height=320>
<p>Gaussian noise reduction (using autoencoder) -> PSNR= 28
   <p> <img src="https://s8.uupload.ir/files/image_2024-03-13_19-28-25_dhdk.png" width=750 height=320>
<p>salt and pepper noise reduction (using median filters) ->  PSNR= 35

# Image Denoising and Classification 🖼️🔍  

## 🔹 Classification Models  
We have used the following deep learning models for image classification:  
1️⃣ **CNN** – A baseline convolutional model for feature extraction.  
2️⃣ **VGG16** – A deep architecture with sequential convolutional layers.  
3️⃣ **AlexNet** – A compact model designed for efficient classification.  
4️⃣ **ResNet50** – A residual network with 50 layers for improved accuracy.  
5️⃣ **Inception V3** – A deep architecture with multiple kernel sizes in parallel.  

## 🔹 Noise Detection & Reduction  
We applied deep learning-based noise detection and reduction techniques using:  

### 🛠️ Noise Detection in the Frequency Domain  
- **VGG16** – Used to classify different noise types from frequency domain representations.  

### 🧹 Noise Reduction Techniques  
- **Deep Autoencoder for Denoising** 🌀  
  - A **fully convolutional autoencoder (with skip connections) ** was trained to remove **Gaussian and periodic noise** from images.  
  - The encoder compresses the noisy image into a **low-dimensional latent space**, removing noise-related information.  
  - The decoder reconstructs a denoised version of the image using transposed convolutions.  
  - A **Mean Squared Error (MSE) loss** is used to train the network, ensuring that the restored images remain as close as possible to their original noise-free versions.  

- **Median Filter (Kernel Size = 3)** 🏗️  
  - Applied for **salt-and-pepper noise** removal by replacing pixel values with the median of their neighborhood.  

## 🚀 Future Updates  
🔜 This repository **will be updated** with **diffusion-based denoiser models** for both **image and speech domains** to further enhance noise reduction capabilities! 🎤🖼️  

Stay tuned for more improvements! ⭐  

### 🚀 Also for tracing our work you can access both Phase1 and Phase2 datasets from these two links:

<a href='https://drive.google.com/file/d/1P4E6cTn4X6rgK9SyOsMA344kLNyISPHQ/view' > Phase 1  </a> 
,
<a href='https://drive.google.com/file/d/18UXIh3mGA_M0oxlapPIrUG-VVpF6PN2S/view' >  Phase 2 </a>
,
<a href='https://docs.google.com/spreadsheets/d/1bGshf6J4UxfDM3pVp5VjuqP-Sk5HTEgR/edit?gid=1231934396#gid=1231934396' >  Labels </a>

**Citation: **
```
@misc{hami2024assessing,
  title={Assessing The Impact of CNN Auto Encoder-Based Image Denoising on Image Classification Tasks},
  author={Mohsen Hami and Mahdi JameBozorg},
  year={2024},
  eprint={2404.10664},
  archivePrefix={arXiv},
  primaryClass={cs.CV}
}
```


### ⭐ Final project of computer vision course  By Mohsen Hami, Mahdi Jamebozorg **
