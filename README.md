## STM32AI_Overall_Offer


<img width="" src="./Images/home-featured-st-centered-image-1067x600px.jpg" alt="ST centered image">

Simple, fast, optimized.
Our extensive solutions for embedded AI.

This repository is the primary entry point for all Artificial Intelligence (AI) projects related to STMicroelectronics' [**STM32 microcontrollers (MCUs)**](https://www.st.com/en/microcontrollers-microprocessors/stm32-32-bit-arm-cortex-mcus.html) and [**microprocessors (MPUs)**](https://www.st.com/en/microcontrollers-microprocessors/stm32-arm-cortex-mpus.html). It provides a comprehensive overview of the AI and Computer Vision resources available for STM32 devices, guiding developers to the tools and software needed to add smart features to their products.

Visit our dedicated website at [**stm32ai.st.com**](https://www.st.com/content/st_com/en/ecosystems/artificial-intelligence-ecosystem-stm32.html).

### ✨ STM32 ModelZoo
<details open><summary><b>View links</b></summary>

| Project       | Description    |
| ------------- | -------------- |
| [stm32ai-modelzoo-services](https://github.com/STMicroelectronics/stm32ai-modelzoo-services) | AI Model Zoo Services (training, quantization, evaluation scripts...) for STM32 devices |
| [stm32ai-modelzoo](https://github.com/STMicroelectronics/stm32ai-modelzoo) | Storage for the AI Model Zoo for STM32 devices |
| [HuggingFace-STMicroelectronics](https://huggingface.co/STMicroelectronics) | Hugging Face space containing the models card and a space for the model zoo app  |
</details>

### 🌱 Application packages
<details open ><summary><b>STM32N6</b></summary>

<img width="30%" src="./Images/model-zooegif-people-detect.gif" alt="Object detection">
<img width="30%" src="./Images/model-zoo-gif-pose-estimation.gif" alt="Pose estimation">
<img width="30%" src="./Images/model-zoo-gif-hand-landmark.gif" alt="Hand landmark">

The application packages are organized into 3 categories:

1. <b>Demonstration binary code</b>

2. <b>Getting Started</b>, simple code example, usually in Bare metal to enable fast and easy hands-on

3. <b>Optimized application</b>, optimized code example, usually in FreeRTOS to enable advanced application code development 

| Category | Project       | Description    |
| ------------- | ------------- | -------------- |
|Demo binary| [STM32N6 AI](https://www.st.com/en/development-tools/stm32n6-ai.html) | STM32N6 AI ecosystem with application examples and demonstrations|
|Getting Started| [Audio](https://github.com/STMicroelectronics/STM32N6-GettingStarted-Audio) | Simple application example performing Audio Event Detection (AED) and Speech Enhancement (SE)|
|Getting Started| [Image Classification](https://github.com/STMicroelectronics/STM32N6-GettingStarted-ImageClassification) | Simple application example performing Image Classification|
|Getting Started| [Object Detection](https://github.com/STMicroelectronics/STM32N6-GettingStarted-ObjectDetection) | Simple application example performing Object Detection|
|Getting Started| [Pose Estimation](https://github.com/STMicroelectronics/STM32N6-GettingStarted-PoseEstimation) | Simple application example performing Pose Estimation|
|Getting Started| [Instance Segmentation](https://github.com/STMicroelectronics/STM32N6-GettingStarted-InstanceSegmentation) | Simple application example performing Instance Segmentation|
|Getting Started| [Semantic Segmentation](https://github.com/STMicroelectronics/STM32N6-GettingStarted-SemanticSegmentation) | Simple application example performing Semantic Segmentation|
|Optimized application| [	People detection and tracking](https://github.com/STMicroelectronics/x-cube-n6-ai-people-detection-tracking) | FreeRTOS-based application example for people detection with AI |
|Optimized application| [	Pose estimation](https://github.com/STMicroelectronics/x-cube-n6-ai-multi-pose-estimation) | FreeRTOS-based application example for multi pose estimation with AI |
|Optimized application| [	Hand landmarks](https://github.com/STMicroelectronics/x-cube-n6-ai-hand-landmarks) | FreeRTOS-based application example for hand landmark detection with AI |
|Optimized application| [	AI with h264 encoder and USB UVC](https://github.com/STMicroelectronics/x-cube-n6-ai-h264-usb-uvc) | Multimedia application example with AI, H264 encoding and USB UVC streaming |
|Optimized application| [	Power measurement utilities](https://github.com/STMicroelectronics/x-cube-n6-ai-power-measurement) | Application example enabling power measurement on STM32N6570-DK |


</details>

### 📂 STM32 MPU
<details open><summary><b>View links</b></summary>
<img width="30%" src="./Images/DEMO-STM32MP2-FaceReco.gif" alt="Face recognition">
<img width="30%" src="./Images/DEMO-STM32MP2-Heatmap-1.gif" alt="People detection and heatmap">
<img width="30%" src="./Images/DEMO-STM32MP2-PoseEstimation-2.gif" alt="Pose estimation">

| Project       | Description    |
| ------------- | -------------- |
| [meta-st-x-linux-ai](https://github.com/STMicroelectronics/meta-st-x-linux-ai) | OpenEmbedded meta layer to install AI frameworks, tools and application samples for the STM32MPU series |
| [meta-st-x-linux-isp](https://github.com/STMicroelectronics/meta-st-x-linux-isp) | OpenEmbedded meta layer to install ISP tools and applications for the STM32MP2x series |
</details>

### 📷 Computer vision & ISP
<details><summary><b>View links</b></summary>

| Project       | Description    |
| ------------- | -------------- |
| [stm32-mw-isp](https://github.com/STMicroelectronics/stm32-mw-isp) | The ISP (Image Signal Processing) middleware library supports camera applications development for STM32 microcontrollers embedding the ISP camera pipeline called DCMIPP. |
| [stm32-mw-camera](https://github.com/STMicroelectronics/stm32-mw-camera) | The camera middleware library simplifies the development process for applications that require camera functionality by abstracting hardware-specific details. |
| [stm32-mw-ipl](https://github.com/STMicroelectronics/stm32-mw-ipl) | The STM32 Image Processing Library (IPL) is a C software library of image processing and computer vision functionalities enabling to accelerate the development of vision applications on STM32 microcontrollers. |
| [x-cube-isp](https://github.com/STMicroelectronics/x-cube-isp) | The X-CUBE-ISP is an image signal processing (ISP) tuning software. It targets STM32 microcontrollers embedding an ISP camera pipeline called DCMIPP. It offers advanced image quality tuning services, enabling developers to easily create ISP-based applications. |
| [stm32h7 webcam](https://github.com/STMicroelectronics/x-cube-webcam) | Software application package performing camera data capture on STM32H747 DK board. This application package relies on USB Video Device Class (UVC) and enable the STM32H747 DK board to be enumerated as a Webcam when connected to a PC. |
| [stm32n6 webcam](https://github.com/STMicroelectronics/x-cube-n6-camera-capture) | Software application package performing camera data capture on STM32N6570 DK board. This application package relies on USB Video Device Class (UVC) and enable the STM32N6570 DK board to be enumerated as a Webcam when connected to a PC. |
</details>

### 🔧 AI Tools
<details><summary><b>View links</b></summary>

|        | Description    |
| ------------- | -------------- |
| <a href="https://www.st.com/en/embedded-software/x-cube-ai.html"> <img src="https://img.shields.io/badge/AI%20Tool-x--cube--ai-FFD700?style=flat&logo=stmicroelectronics&logoColor=white"/></a> | X-CUBE-AI - AI expansion pack for STM32CubeMX |
| <a href="https://www.st.com/en/development-tools/stedgeai-core.html"> <img src="https://img.shields.io/badge/AI%20Tool-ST%20Edge%20AI%20Core-FFD700?style=flat&logo=stmicroelectronics&logoColor=white"/></a> | ST Edge AI Core - Desktop tool to evaluate, optimize and compile edge AI models on multiple ST products |
| <a href="https://stedgeai-dc.st.com/home"> <img src="https://img.shields.io/badge/AI%20Tool-STM32Cube.AI%20Developer%20Cloud-FFD700?style=flat&logo=stmicroelectronics&logoColor=white"/></a> | ST Edge AI Developer Cloud - Online optimization platform |
| <a href="https://www.st.com/en/development-tools/nanoedgeaistudio.html"> <img src="https://img.shields.io/badge/AI%20Tool-NanoEdge%20AI%20Studio-FFD700?style=flat&logo=stmicroelectronics&logoColor=white"/></a> | NanoEdge AI Studio - Automated machine learning tool |
| <a href="https://www.st.com/en/development-tools/stm32-isp-iqtune.html"> <img src="https://img.shields.io/badge/IQ%20Tool-STM32%20ISP%20IQTune-blue?style=flat&logo=stmicroelectronics&logoColor=white"/></a> | STM32 ISP IQTune - Comprehensive STM32 ISP tuning software |
</details>

### 💡 AI Utilities
<details><summary><b>View links</b></summary>

| Project       | Description    |
| ------------- | -------------- |
| [stm32ai-datalogger](https://github.com/STMicroelectronics/stm32ai-datalogger) | GenericDataLogger for AI is a project composed of tools that format and log data with ease, especially between a STM32 and a computer |
| [stm32ai-nanoedge-vibration-monitoring](https://github.com/stm32-hotspot/stm32ai-nanoedge-vibration-monitoring) | STM32 Application for vibration monitoring with NanoEdge AI Studio |
| [stm32ai-nanoedge-datalogger](https://github.com/stm32-hotspot/stm32ai-nanoedge-datalogger) | STM32 Application for datalogging feature with NanoEdge AI Studio |
</details>

###  🚀 AI partners
<details><summary><b>View links</b></summary>


| Project       | Description    |
| ------------- | -------------- |
| [stm32ai-nota](https://github.com/STMicroelectronics/stm32ai-nota) | This repository contains Jupyter notebooks that demonstrate how to use Netspresso to prune pre-trained deep learning models from STM32AI Model Zoo and fine-tune them for your specific use case. Learn how to reduce the size of your models without sacrificing accuracy and customize them for your own applications |
| [stm32ai-tao](https://github.com/STMicroelectronics/stm32ai-tao) | Nvidia TAO (Train, Adapt, Optimize) with STM32Cube.AI Developer Cloud |
| [STEdgeAI Ultralytics fork](https://github.com/stm32-hotspot/ultralytics) | Fork of the Ultralitics repository that implements STEdgeAI models |
</details>

### 📍 Miscellaneous
<details><summary><b>View links</b></summary>

| Project       | Description    |
| ------------- | -------------- |
| [stm32ai-wiki](https://github.com/STMicroelectronics/stm32ai-wiki) | Application examples and resources that demonstrate Artificial Neural Networks running on STM32 microcontrollers and microprocessors. It illustrates and supports the STM32 AI Wiki articles |
| [stm32ai-perf](https://github.com/STMicroelectronics/stm32ai-perf) | MLPerf™ Tiny Deep Learning Benchmarks for STM32 devices |
</details>

### ❓ Help and support

For community discussion and support, please refer to:

- [ST Support Center](https://my.st.com/ols#/ols/) 
- [ST Community Forum](https://community.st.com/s/)
