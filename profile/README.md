<h1 align="center">Tianmouc</h1>

<p align="center"><strong>Complementary vision for open-world sensing</strong></p>

<p align="center">
  <img width="184" alt="Tianmouc camera with its lens and enclosure" src="https://github.com/user-attachments/assets/97c38389-090b-4f00-a49b-433f80a06298">
</p>

<p align="center">
  <a href="#tianmouc-related-research">Research</a> ·
  <a href="#open-source-projects">Projects</a> ·
  <a href="https://lyh983012.github.io/tianmoucv_doc_opensource/index.html#welcome-to-tianmouc-s-project-homepage">Documentation</a>
</p>

## Tianmouc-Related Research

### 2026

- **[Beyond Sensing Fragility: Complementary-Pathway Distillation for Robust Depth Estimation](https://dl.acm.org/doi/10.1145/3767308.3835920)**<br>
  Xiangru Chen, Yapeng Meng, Yuguo Chen, et al.<br>
  *ACM Multimedia 2026*
- **[BCP3D: Robust 3D Object Tracking Using Brain-Inspired Complementary-Pathway for Challenging Scenarios](https://link.springer.com/article/10.1007/s11263-026-03089-3)**<br>
  Lijian Wang, Taoyi Wang, Xiangru Chen, et al.<br>
  *International Journal of Computer Vision*
- **[A unified calibration framework and synthesis methodology for high dynamic range imaging with complementary vision sensors](https://www.sciencedirect.com/science/article/pii/S0263224126022712)**<br>
  Yihan Lin, Yapeng Meng, Xiangru Chen<br>
  *Measurement*
- **[Brain-inspired visual sensing–perception for open-world environments](https://www.nature.com/articles/s44460-026-00095-3)**<br>
  Yihan Lin, Yuguo Chen, Yapeng Meng, et al.<br>
  *Nature Sensors* · [Code](https://github.com/Tianmouc/TMC-SSL-Representation)
- **[Espresso: Exploiting the Sparsity Property in Brain-Inspired Vision Sensors With Spatiotemporal Ordering](https://ieeexplore.ieee.org/document/11270873/)**<br>
  Leshan Li, Hongyi Li, Qingyuan Yang, et al.<br>
  *IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems*
- **[An adaptive filter for denoising brain-inspired complementary vision sensor](https://iopscience.iop.org/article/10.1088/2634-4386/ae0a76)**<br>
  Taoyi Wang, Yuxiang Li, Yihan Lin, et al.<br>
  *Neuromorphic Computing and Engineering*
- **[SDGS: Spatial Difference Guided Gaussian Splatting for Simultaneous Localization and 3D Reconstruction](https://openaccess.thecvf.com/content/CVPR2026/html/Tian_SDGS_Spatial_Difference_Guided_Gaussian_Splatting_for_Simultaneous_Localization_and_CVPR_2026_paper.html)**<br>
  Yijian Tian, Mingtao Ou, Zijian Pan, et al.<br>
  *CVPR 2026*
- **[Spatio-Temporal Difference Guided Motion Deblurring with the Complementary Vision Sensor](https://openaccess.thecvf.com/content/CVPR2026/html/Meng_Spatio-Temporal_Difference_Guided_Motion_Deblurring_with_the_Complementary_Vision_Sensor_CVPR_2026_paper.html)**<br>
  Yapeng Meng, Lin Yang, Yuguo Chen, et al.<br>
  *CVPR 2026* · [Code](https://github.com/Tianmouc/tmcDeblur)

### 2025

- **[CSVO: Complementary-Pathway Spatial-Enhanced Visual Odometry for Extreme Environments with Brain-Inspired Vision Sensors](https://ieeexplore.ieee.org/document/11246288/)**<br>
  Yihan Lin, Zhaoxi Zhang, Yuguo Chen, et al.<br>
  *IROS 2025* · [Code](https://github.com/Tianmouc/CSVO)
- **[Diffusion-Based Extreme High-speed Scenes Reconstruction with the Complementary Vision Sensor](https://openaccess.thecvf.com/content/ICCV2025/html/Meng_Diffusion-Based_Extreme_High-speed_Scenes_Reconstruction_with_the_Complementary_Vision_Sensor_ICCV_2025_paper.html)**<br>
  Yapeng Meng, Yihan Lin, Taoyi Wang, et al.<br>
  *ICCV 2025* · [Code](https://github.com/Tianmouc/GenRec)
- **[Quantitative evaluation of brain-inspired vision sensors in high-speed robotic perception](https://ieeexplore.ieee.org/document/11345925/)**<br>
  Taoyi Wang, Lijian Wang, Yihan Lin, et al.<br>
  *International Conference on Neuromorphic Systems (ICONS) 2025*

### 2024

- **[A vision chip with complementary pathways for open-world sensing](https://www.nature.com/articles/s41586-024-07358-4)**<br>
  Zheyu Yang, Taoyi Wang, Yihan Lin, et al.<br>
  *Nature* · [Demo code](https://github.com/Tianmouc/tianmouc_paper_code)

## Open-source Projects

### Core Library and SDKs

<a href="https://github.com/Tianmouc/tianmoucv">
  <img width="168" alt="TianMouCV logo" src="https://github.com/user-attachments/assets/c05f3113-0eb6-4dbf-88c8-9de322072c29">
</a>

- **[tianmoucv](https://github.com/Tianmouc/tianmoucv)** · Python toolkit for Tianmouc V1 data and algorithms. [PyPI](https://pypi.org/project/tianmoucv/)
- **[tianmouc_sdk_minimum](https://github.com/Tianmouc/tianmouc_sdk_minimum)** · Minimal C++ SDK for Tianmouc V1 with a dual-stream data transmission example.
- **[tianmouc_sdk_af_lenCon](https://github.com/Tianmouc/tianmouc_sdk_af_lenCon)** · C development toolkit for Computar LensConnect MPW lenses.

### Reconstruction and Data Tools

- **[tmc-gray-recon](https://github.com/Tianmouc/tmc-gray-recon)** · Python training and inference code for a lightweight U-Net that reconstructs grayscale images from raw spatial differences (SD).
- **[tmdat_tools](https://github.com/Tianmouc/tmdat_tools)** · C++ utility for trimming `.tmdat` recordings.

Research code is linked alongside the corresponding papers in [Tianmouc-Related Research](#tianmouc-related-research).

<details>
<summary>Additional repositories with limited public availability</summary>

GitHub may require repository access to open these links.

#### Library Development, Denoising, and HDR

- **[tianmoucv_dev](https://github.com/Tianmouc/tianmoucv_dev)** · Development version of the Tianmouc V1 Python toolkit.
- **[tianmoucv1_ssl_denoise](https://github.com/Tianmouc/tianmoucv1_ssl_denoise)** · Self-supervised denoising for Tianmouc V1 in Python.
- **[LADF_Denoise](https://github.com/Tianmouc/LADF_Denoise)** · Python implementation of the adaptive denoising filter.
- **[TMC Dual-HDR Synthesis](https://github.com/Tianmouc/TMC-HDR-PFANet)** · Python implementation of the calibration and HDR synthesis method.

#### Calibration, Datasets, and Simulation

- **[Tianmouc_Calib](https://github.com/Tianmouc/Tianmouc_Calib)** · Jupyter notebooks for calibrating RGB, temporal difference (TD), and spatial difference (SD) data.
- **[VectorFieldUndistort](https://github.com/Tianmouc/VectorFieldUndistort)** · Jupyter notebooks for undistorting spatial gradient fields and simulating spatial differences and geometric distortion.
- **[tianmouc_datasets_devtool](https://github.com/Tianmouc/tianmouc_datasets_devtool)** · Python tools for managing dataset paths and loading Tianmouc datasets.
- **[bivs_benchmark](https://github.com/Tianmouc/bivs_benchmark)** · Benchmark for brain-inspired vision sensors.
- **[unisim](https://github.com/Tianmouc/unisim)** · Legacy Python simulator. The current simulator is available in the `sim` module of [tianmoucv](https://github.com/Tianmouc/tianmoucv).

#### Applications and Deployment

- **[tianmouc_gui](https://github.com/Tianmouc/tianmouc_gui)** · Python and Qt 5 source code for the Tianmouc V1 GUI.
- **[Tianmouc_MoCap](https://github.com/Tianmouc/Tianmouc_MoCap)** · Jupyter notebooks for complementary motion capture with Tianmouc.
- **[DualTMC-DepthEstimate](https://github.com/Tianmouc/DualTMC-DepthEstimate)** · C++ depth estimation package for a dual-Tianmouc setup.
- **[Tianmouc6D](https://github.com/Tianmouc/Tianmouc6D)** · C++ framework for six-degree-of-freedom object pose tracking with Tianmouc.
- **[DualTMC-FPGA](https://github.com/Tianmouc/DualTMC-FPGA)** · C++ drivers for FPGA-accelerated dual-Tianmouc capture with a ROS 1 Noetic bridge.
- **[dvs_all_gui](https://github.com/Tianmouc/dvs_all_gui)** · C++ GUI for DVS cameras and Zhengyin test equipment.

</details>

---

[Project site mirror for mainland China](http://www.tianmouc.cn:40000/#welcome-to-tianmouc-s-project-homepage)
