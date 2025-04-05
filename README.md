# Hierarchical-Pixel-Wavelength-Fusion-Network-for-Progressive-Hyperspectral-Image-Reconstruction
## Introduction
We propose Hierarchical Pixel- Wavelength Fusion Network (HPWF-Net) to address the challenges of tree species classification and spectral reconstruction in complex forest ecosystems.

HPWF- Net utilizes an enhanced U-Net architecture with multi-level loss supervision and convolutional consistency constraints, enabling accurate reconstruction by supervising intermediate encoder outputs, convolutional regressions, and final decoder predictions.

## Overall Framework
![overall](https://github.com/user-attachments/assets/ad40648e-651b-4647-91b9-75e813e2c4b3)

## Results
<details>
  <summary>Qualitative comparison</summary>
  <img src="https://github.com/user-attachments/assets/1cfc7998-1778-4a0d-a15a-39436c10297b" alt="result">
</details>

<details>
  <summary>Reconstructed hyperspectral imagery in near-true color, false color, and grayscale</summary>
  <img src="https://github.com/user-attachments/assets/0ce1fa1d-0c56-4794-a54c-1469a529c150" alt="four">
</details>

<details>
  <summary>Mean spectral curves of test regions</summary>
  <img src="https://github.com/user-attachments/assets/6042c25a-7107-4b66-a093-629e4c817d85" alt="line">
</details>

<details>
  <summary>PIXEL-WISE TREE SPECIES CLASSIFICATION RESULTS</summary>
  <img src="https://github.com/user-attachments/assets/27c0b98b-e81f-4454-8ae1-e20c490ef97d" alt="table">
</details>

<details>
  <summary>MPSNR</summary>
  <img src="https://github.com/user-attachments/assets/f67a2296-c6bd-4c0e-bbb0-9d76e1e2754f" alt="mpsnr">
</details>

<details>
  <summary>MSSIM</summary>
  <img src="https://github.com/user-attachments/assets/47fc117d-a1eb-4e59-8ba2-622f507d3c55" alt="mssim">
</details>

<details>
  <summary>SAM</summary>
  <img src="https://github.com/user-attachments/assets/4e953355-b9be-4c4f-a12c-c46b87e2a4f3" alt="sam">
</details>

Experimental results demonstrate that the reconstructed hyperspectral data improve tree species classification accuracy by 5.9% compared to the original Sentinel-2 multispectral data. 
This work contributes to hyperspectral reconstruction and fine-grained ecological monitoring, offering a practical solution for remote sensing applications in forest ecosystems.
***
We are packaging the environment configuration file and making the final code changes...
