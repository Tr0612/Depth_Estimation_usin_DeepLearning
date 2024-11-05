This project was done in order to learn about Depth Estimation using Deep Learning.

# Paper
1. [UMD_CODED](https://prg.cs.umd.edu/CodedVO) 

# Abstract
This project aims to enhance monocular depth
 estimation accuracy by combining phase-coded aperture imaging
 with a neural network model. The approach leverages depth
aware blur synthesis from RGB images, ground truth depth
 maps, and custom point spread functions (PSFs).
 Key components include depth-dependent blur synthesis
 using convolution operations on RGB images with discrete
 PSFs, followed by training on NYUv2 and UMDCodedVO
LivingRoom datasets. Model evaluation is conducted on out-of
domain datasets (ICL-NUIM and UMDCodedVO-DiningRoom)
 using quantitative metrics (RMSE, Abs-Rel) and qualitative
 assessments with ’viridis’ color scheme.
 This approach improves depth accuracy, particularly at occlu
sion boundaries, and highlights the potential of coded aperture
 imaging in monocular depth estimation.

 # Result
 AiF - All in Focus images refers to RGB Images
 CodedDepth - This refers to training the model on using CodedDepth Images which we obtained using that paper /
 ![image](https://github.com/user-attachments/assets/0c7821a8-b2b9-4ef8-9a00-d445e068cdf6)

