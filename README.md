---

🚀 TensorRT-YOLO is an **easy-to-use**, **extremely efficient** inference deployment tool for the **YOLO series** designed specifically for NVIDIA devices. The project not only integrates TensorRT plugins to enhance post-processing but also utilizes CUDA kernels and CUDA graphs to accelerate inference. TensorRT-YOLO provides support for both C++ and Python inference, aiming to deliver a 📦**out-of-the-box** deployment experience. It covers various task scenarios such as [object detection](examples/detect/), [instance segmentation](examples/segment/), [image classification](examples/classify/), [pose estimation](examples/pose/), [oriented object detection](examples/obb/), and [video analysis](examples/VideoPipe), meeting developers' deployment needs in **multiple scenarios**.

<div align="center">

<img src='assets/example.gif' width="800px">

</div>

### 🎯 Diverse YOLO Support
- **Comprehensive Compatibility**: Supports YOLOv3 to YOLO12 series models, as well as PP-YOLOE+, YOLO-World and YOLO-Master, meeting diverse needs. See [🖥️ Supported Models List](https://github.com/laugh12321/TensorRT-YOLO/blob/export/README.md#%EF%B8%8F-model-support-list) for details.
- **Flexible Switching**: Provides simple and easy-to-use interfaces for quick switching between different YOLO versions. 🌟 NEW
- **Multi-Scenario Applications**: Offers rich example codes covering [Detect](examples/detect/), [Segment](examples/segment/), [Classify](examples/classify/), [Pose](examples/pose/), [OBB](examples/obb/), and more.

### 🚀 Performance Optimization
- **CUDA Acceleration**: Optimizes pre-processing through CUDA kernels and accelerates inference using CUDA graphs.
- **TensorRT Integration**: Deeply integrates TensorRT plugins to significantly speed up post-processing and improve overall inference efficiency.
- **Multi-Context Inference**: Supports multi-context parallel inference to maximize hardware resource utilization. 🌟 NEW
- **Memory Management Optimization**: Adapts multi-architecture memory optimization strategies (e.g., Zero Copy mode for Jetson) to enhance memory efficiency. 🌟 NEW

### 🛠️ Usability
- **Out-of-the-Box**: Provides comprehensive C++ and Python inference support to meet different developers' needs.
- **CLI Tools**: Built-in command-line tools for quick model export and inference, improving development efficiency.
- **Docker Support**: Offers one-click Docker deployment solutions to simplify environment configuration and deployment processes.
- **No Third-Party Dependencies**: All functionalities are implemented using standard libraries, eliminating the need for additional dependencies and simplifying deployment.
- **Easy Deployment**: Provides dynamic library compilation support for easy calling and deployment.

### 🌐 Compatibility
- **Multi-Platform Support**: Fully compatible with various operating systems and hardware platforms, including Windows, Linux, ARM, and x86.
- **TensorRT Compatibility**: Perfectly adapts to TensorRT 10.x versions, ensuring seamless integration with the latest technology ecosystem.

### 🔧 Flexible Configuration
- **Customizable Preprocessing Parameters**: Supports flexible configuration of various preprocessing parameters, including **channel swapping (SwapRB)**, **normalization parameters**, and **border padding**. 🌟 NEW
