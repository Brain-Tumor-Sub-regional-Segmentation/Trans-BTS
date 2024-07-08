# Trans-BTS
 TransBTS (Transformer-based Brain Tumor Segmentation) represents a cutting-edge approach in medical image analysis, specifically targeting the
 segmentation of brain tumors from 3D MRI scans. Traditional methods, like
 CNNs, struggle with capturing long-range dependencies crucial for dense segmentation tasks. This limitation arises because CNNs have limited recep
tive fields, only processing small local regions of the image, which hampers
 their ability to understand broader contextual information essential for precise segmentation. In response, TransBTS integrates Transformer architecture,renowned for its ability to model global relationships in sequential data, such as language. By adapting Transformer’s strengths to volumetric medical data,TransBTS combines a 3D CNN encoder for local context extraction with a Transformer encoder for global feature modeling. This hybrid approach allows TransBTS to excel in capturing both local and global information, achieving more accurate and detailed segmentation results than previous methods.

 # Resources
 We used the implementation of this paper https://arxiv.org/abs/2103.04430.

 # Experiment
 We run the model on Brats-20 using kaggle free GPU. so with this limited resources we was able to run **51 epoch**.  
