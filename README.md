## STM32AI_Overall_Offer


<img width="" src="https://stm32ai.st.com/wp-content/uploads/2024/06/home-featured-st-centered-image-1067x600px.jpg" alt="ST centered image">

Simple, fast, optimized.
Our extensive solutions for embedded AI.

This repository is listing all [**AI and Computer Vision resources and tools for STM32**](https://www.st.com/content/st_com/en/ecosystems/artificial-intelligence-ecosystem-stm32.html).

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

<img width="30%" src="https://stm32ai.st.com/wp-content/uploads/2024/12/model-zooegif-people-detect.gif" alt="Object detection">
<img width="30%" src="https://stm32ai.st.com/wp-content/uploads/2024/12/model-zoo-gif-pose-estimation.gif" alt="Pose estimation">
<img width="30%" src="https://stm32ai.st.com/wp-content/uploads/2024/12/model-zoo-gif-hand-landmark.gif" alt="Hand landmark">

The application packages are organized into 3 categories:

1. <b>Demonstration binary code</b>

2. <b>Getting Started</b>, simple code example, usually in Bare metal to enable fast and easy hands-on

3. <b>Optimized application</b>, opimized code example, usually in FreeRTOS to enable advanced application code development 

| Category | Project       | Description    |
| ------------- | ------------- | -------------- |
|Demo binary| [STM32N6 AI](https://www.st.com/en/development-tools/stm32n6-ai.html) | STM32N6 AI ecosystem with application examples and demonstrations|
|Getting Started| [Audio](https://github.com/STMicroelectronics/stm32ai-modelzoo-services/tree/main/application_code/audio/STM32N6) | Simple application example performing Audio Event Detection (AED) and Speech Enhancement (SE)|
|Getting Started| [Image Classification](https://github.com/STMicroelectronics/stm32ai-modelzoo-services/tree/main/application_code/image_classification/STM32N6) | Simple application example performing Image Classification|
|Getting Started| [Object Detection](https://github.com/STMicroelectronics/stm32ai-modelzoo-services/tree/main/application_code/object_detection/STM32N6) | Simple application example performing Object Detection|
|Getting Started| [Pose Estimation](https://github.com/STMicroelectronics/stm32ai-modelzoo-services/tree/main/application_code/pose_estimation/STM32N6) | Simple application example performing Pose Estimation|
|Getting Started| [Instance Segmentation](https://github.com/STMicroelectronics/stm32ai-modelzoo-services/tree/main/application_code/instance_segmentation/STM32N6) | Simple application example performing Instance Segmentation|
|Getting Started| [Semantic Segmentation](https://github.com/STMicroelectronics/stm32ai-modelzoo-services/tree/main/application_code/semantic_segmentation/STM32N6) | Simple application example performing Semantic Segmentation|
|Optimized application| [	x-cube-n6-ai-people-detection-tracking](https://github.com/STMicroelectronics/x-cube-n6-ai-people-detection-tracking) | FreeRTOS-based application example for people detection with AI |
|Optimized application| [	x-cube-n6-ai-multi-pose-estimation](https://github.com/STMicroelectronics/x-cube-n6-ai-multi-pose-estimation) | FreeRTOS-based application example for multi pose estimation with AI |
|Optimized application| [	x-cube-n6-ai-hand-landmarks](https://github.com/STMicroelectronics/x-cube-n6-ai-hand-landmarks) | FreeRTOS-based application example for hand landmark detection with AI |
|Optimized application| [	x-cube-n6-ai-h264-usb-uvc](https://github.com/STMicroelectronics/x-cube-n6-ai-h264-usb-uvc) | Multimedia application example with AI, H264 encoding and USB UVC streaming |
|Optimized application| [	x-cube-n6-ai-power-measurement](https://github.com/STMicroelectronics/x-cube-n6-ai-power-measurement) | Application example enabling power measurement on STM32N6570-DK |


</details>

### 📂 STM32 MPU
<details open><summary><b>View links</b></summary>

<img width="30%" src="https://stm32ai.st.com/wp-content/uploads/2025/06/DEMO-STM32MP2-FaceReco.gif" alt="Face recognition">
<img width="30%" src="https://stm32ai.st.com/wp-content/uploads/2025/06/DEMO-STM32MP2-Heatmap-1.gif" alt="People detection and heatmap">
<img width="30%" src="https://stm32ai.st.com/wp-content/uploads/2025/06/DEMO-STM32MP2-PoseEstimation-2.gif" alt="Pose estimation">

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

| Project       | Description    |
| ------------- | -------------- |
| [x-cube-ai](https://www.st.com/en/embedded-software/x-cube-ai.html) | X-CUBE-AI - AI expansion pack for STM32CubeMX |
| [ST Edge AI Developer Cloud](https://stedgeai-dc.st.com/home) | ST Edge AI Developer Cloud - online optimization platform |
| [NanoEdge AI Studio](https://www.st.com/en/development-tools/nanoedgeaistudio.html) | NanoEdge AI Studio - automated machine learning tool |
| [STM32 ISP IQtune](https://www.st.com/en/development-tools/stm32-isp-iqtune.html) | STM32 ISP IQTune - comprehensive STM32 ISP tuning softwar |
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
