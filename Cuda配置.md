# Cuda配置

CUDA（Compute Unified Device Architecture）是由NVIDIA开发的一种通用并行计算架构。CUDA允许程序员利用NVIDIA GPU的并行计算能力，加速各种计算密集型应用程序。

## 配置流程 

### 一、cuda版本

在安装有Nvidia GPU的计算中查看当前cuda版本。

打开Nvidia控制面板，点击左下方系统信息，选择组件，查看cuba版本信息。

![](pic/image1.png)

注意：cuba版本支持向下兼容，一般选择相同版本或略低于当前版本，不能高于。

### 二、cuda下载

[下载地址](https://developer.nvidia.com/cuda-toolkit-archive)

下载需要的cuda版本。

![](pic/image2.png)

![](pic/image3.png)

最后的下载结果示例：

![](pic/image4.png)

### 三、cuda安装

1.运行下载的exe文件，选择合适的路径。

![](pic/image5.png)

2.等待文件的解压缩。

![](pic/image6.png)

3.勾选继续安装，按照图示即可。

![](pic/image7.png)

![](pic/image8.png)

![](pic/image9.png)

![](pic/image10.png)

4.安装位置默认即可，但要记住这个地址，后续配置环境需要用到。

![](pic/image11.png)

### 四、环境变量配置

一般安装完毕后，**12.0**以上版本会自动配置好环境变量，以下为手动配置的过程。

1.打开**我的电脑**->**右击点击属性**

2.选择**高级系统设置**->**环境变量设置**

![](pic/image12.png)

3.在系统变量框中点击新建，依次输入变量名和目录路径，点击确定。

![](pic/image13.png)







