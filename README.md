# DWX-Net-A-Daubechies-Wavelet-enhanced-Xception-Network-for-Breast-Ultrasound-Lesion-Classification

## Model Architecture

The overall architecture of **AGU-Net (Attention and Gating-aided U-Net)** is designed to improve lesion segmentation in breast ultrasound images by enhancing feature representation and suppressing irrelevant background information.  
The model follows an encoder–decoder structure inspired by U-Net, where the encoder progressively extracts hierarchical features while the decoder reconstructs the segmentation mask through upsampling and skip connections.

Attention and gating mechanisms are integrated into the network to refine feature propagation across different scales. These modules help the model focus on informative lesion regions while filtering out noise commonly present in ultrasound imaging. The skip connections further preserve spatial details, enabling accurate boundary localization during reconstruction.


![Model_Arch](https://github.com/user-attachments/assets/9b16aedb-936a-4c0c-961b-6b36054af074)

## Proposed Backbone Architecture

The proposed backbone architecture is designed to strengthen feature extraction and improve contextual understanding within the encoder.  
It incorporates convolutional feature blocks along with attention-guided feature refinement to capture both low-level texture information and high-level semantic representations.

![XceptionArch](https://github.com/user-attachments/assets/ddbd10bd-4af3-4f66-b0f5-d90aa45a5454)

## Comparative Results

| Dataset | Accuracy (%) | Precision (%) |
|--------|-------------|--------------|
| BUSI | **99.43** | **99.43** |
| Breast-Lesions-USG | **98.25** | **98.25** |
| BUS-BRA | **99.05** | **99.06** |
