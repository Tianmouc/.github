
# Tianmouc GitHub Organization Repositories

Code repositories related to TianMouC

<img width="231" height="173" alt="image" src="https://github.com/user-attachments/assets/97c38389-090b-4f00-a49b-433f80a06298" />

for a brief introduction to Tianmouc, see [[Here](https://lyh983012.github.io/tianmoucv_doc_opensource/index.html)]


## 核心算法库与SDK
| 仓库 | 描述 | 语言 |
|------|----------|------|
| [tianmoucv](https://github.com/Tianmouc/tianmoucv) | Python tool-chain for tianmouc V1 sensor | Python |
| [tianmoucv_dev](https://github.com/Tianmouc/tianmoucv_dev) | (developing version) Python tool-chain for tianmouc V1 sensor | Python |
| [tianmouc_sdk_minimum](https://github.com/Tianmouc/tianmouc_sdk_minimum) | The minimum Tianmouc-v1 cpp SDK, with a simple two-stream data transmission app | C++ |
| [tianmouc_sdk_af_lenCon](https://github.com/Tianmouc/tianmouc_sdk_af_lenCon) | co-dev toolkit for computar lensconnect MPW | C |


## 顶会论文代码实现
| 仓库 | 描述 | 会议 | 语言 |
|------|----------|------|------|
| [tmcDeblur](https://github.com/Tianmouc/tmcDeblur) | Official implementation of "Spatio-Temporal Difference Guided Motion Deblurring with the Complementary Vision Sensor" | CVPR 2026 | Python |
| [CSVO](https://github.com/Tianmouc/CSVO) | Official implementation of "Complementary-pathway Spatial-enhanced Visual Odometry for Extreme Environments with Brain-inspired Vision Sensors" | IROS 2025 | Python |
| [GenRec](https://github.com/Tianmouc/GenRec) | Official implementation of "Diffusion-Based Extreme High-speed Scenes Reconstruction with the Complementary Vision Sensor" | ICCV 2025 | Python |
| [tianmouc_paper_code](https://github.com/Tianmouc/tianmouc_paper_code) | Some demo codes for the paper "A Vision Sensor Chip with Complementary Pathways for Open-world Sensing" | Nature 2024 | Python |


## 去噪与信号处理
| 仓库 | 描述 | 语言 |
|------|----------|------|
| [TMC-SD2Gray reconstruction](https://github.com/Tianmouc/tmc-gray-recon) | Training and inference of a lightweight UNet for reconstructing high-quality grayscale images from raw SD signals. | Python |
| [tianmoucv1_ssl_denoise](https://github.com/Tianmouc/tianmoucv1_ssl_denoise) | self-supervised denoise for Tianmouc v1 | Python |
| [LADF_Denoise](https://github.com/Tianmouc/LADF_Denoise) | The code for "An Adaptive Filter for Denoising Brain-inspired Complementary Vision Sensor" | Python |




## 标定与几何校正
| 仓库 | 描述 | 语言 |
|------|----------|------|
| [Tianmouc_Calib](https://github.com/Tianmouc/Tianmouc_Calib) | Calibration Toolbox for RGB, TD, and SD toward Tianmouc Data Format | Jupyter Notebook |
| [VectorFieldUndistort](https://github.com/Tianmouc/VectorFieldUndistort) | VectorFieldUndistort provides specific undistortion for spatial gradient field data. Supporting software simulations for both spatial difference (SD) and geomet… | Jupyter Notebook |


## 数据处理与工具
| 仓库 | 官方描述 | 语言 |
|------|----------|------|
| [tianmouc_datasets_devtool](https://github.com/Tianmouc/tianmouc_datasets_devtool) | Tools for dataset path management and data loading （目前所有数据集的路径和读取工具） | Python |
| [tmdat_tools](https://github.com/Tianmouc/tmdat_tools) | tmdat数据裁剪工具 | C++ |



## 应用与部署
| 仓库 | 官方描述 | 语言 |
|------|----------|------|
| [tianmouc_gui](https://github.com/Tianmouc/tianmouc_gui) | Qt GUI for Tianmouc sensor 天眸一代的GUI软件源码 使用Qt5实现 | Python |
| [Tianmouc_MoCap](https://github.com/Tianmouc/Tianmouc_MoCap) | The code for Tianmouc Complementary Motion Capture project | Jupyter Notebook |
| [DualTMC-DepthEstimate](https://github.com/Tianmouc/DualTMC-DepthEstimate) | dual tmc depth estimate package | C++ |
| [Tianmouc6D](https://github.com/Tianmouc/Tianmouc6D) | 6DoF object pose tracking framework using Tianmouc | C++ |
| [DualTMC-FPGA](https://github.com/Tianmouc/DualTMC-FPGA) | drivers for dual tmc with fpga acced, compined with ros1 noetic bridge | C++ |
| [dvs_all_gui](https://github.com/Tianmouc/dvs_all_gui) | GUI for all DVS and a test equipment from zhengyin | C++ |


## 其他仓库
| 仓库 | 官方描述 | 语言 |
|------|----------|------|
| [unisim](https://github.com/Tianmouc/unisim) | 旧版仿真器 Legacy simulator. The updated version is integrated into the sim module of tianmoucv; please use the latest version. | Python |
| [bivs_benchmark](https://github.com/Tianmouc/bivs_benchmark) | Brain-inspired vision sensor benchmark | - |


---

## 官方国内可访问资源
- 项目主站：http://www.tianmouc.cn:40000
- PyPI安装包：https://pypi.org/project/tianmoucv/
