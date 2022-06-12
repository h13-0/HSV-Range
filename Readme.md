# HSV 阈值编辑器
[English](./ReadmeEnglish.md)  
HSV阈值通常用于OpenCV中的色块识别等。  
本Readme包含一些图像, 由于网络问题, 建议使用上网辅助工具查看本文档。  
本阈值编辑器的颜色空间为`HSV_FULL`而不是`HSV`。  
# 使用方法
下载Release版本(暂不提供x86版)  
[Release](https://github.com/h13-0/HSV-Range/releases)
## 打开图片
参数为文件路径。  
使用时可以在`打开图片`按钮左侧的文本框手动输入路径后单击按钮打开图片, 也可以**在清空文本框后**或**文本框内容为上次打开路径时**单击按钮用文件管理器的UI对话框手动选择文件打开。~~自己摸索一下就知道怎么用了。~~  
![Photo1.jpg](./Images/Photo1.jpg)
### HSV预览
将图片转换为HSV色域预览模式
![Photo2.jpg](./Images/Photo2.jpg)
### 阈值编辑效果
![Photo3.jpg](./Images/Photo3.jpg)

## 打开视频流
参数可以是摄像头ID、视频文件、http视频流等。  
参数含义同OpenCV。  
例如输入1为打开1号摄像头，输入http://localhost:8888为打开http视频流。  
![Demo.gif](./Images/Demo.gif)