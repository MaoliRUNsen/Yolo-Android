这是一个将yolov5模型部署到安卓的项目，它依赖于ncnn库
https://github.com/Tencent/ncnn

## 如何构建和运行
### 步骤1

https://github.com/Tencent/ncnn/releases
下载安卓vulkan的ncnn。

### 步骤2

从android vulkan中提取ncnn。压缩到app/src/main/jni，

或者在app/src/main/jni/CMakeLists.txt中将ncnn_DIR路径更改为您的路径

### 步骤3

使用Android Studio打开此项目，并构建！

## 运行截图

![](screenshot.jpg)

