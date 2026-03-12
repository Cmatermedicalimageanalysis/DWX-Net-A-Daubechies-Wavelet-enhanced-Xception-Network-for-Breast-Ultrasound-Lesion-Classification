# DWX-Net-A-Daubechies-Wavelet-enhanced-Xception-Network-for-Breast-Ultrasound-Lesion-Classification

## Model Architecture

The overall architecture of **AGU-Net (Attention and Gating-aided U-Net)** is designed to improve lesion segmentation in breast ultrasound images by enhancing feature representation and suppressing irrelevant background information.  
The model follows an encoder–decoder structure inspired by U-Net, where the encoder progressively extracts hierarchical features while the decoder reconstructs the segmentation mask through upsampling and skip connections.

Attention and gating mechanisms are integrated into the network to refine feature propagation across different scales. These modules help the model focus on informative lesion regions while filtering out noise commonly present in ultrasound imaging. The skip connections further preserve spatial details, enabling accurate boundary localization during reconstruction.

![Model_Arch](https://github.com/user-attachments/assets/b949bf86-f66c-4b37-83ec-3732377309a2)

## Proposed Backbone Architecture

The proposed backbone architecture is designed to strengthen feature extraction and improve contextual understanding within the encoder.  
It incorporates convolutional feature blocks along with attention-guided feature refinement to capture both low-level texture information and high-level semantic representations.

![XceptionArch](https://github.com/user-attachments/assets/6d5d333e-30ae-44ad-8911-ca91c9df4af4)

## Comparative Results

| Dataset | Accuracy (%) | Precision (%) |
|--------|-------------|--------------|
| BUSI | **99.43** | **99.43** |
| Breast-Lesions-USG | **98.25** | **98.25** |
| BUS-BRA | **99.05** | **99.06** |
