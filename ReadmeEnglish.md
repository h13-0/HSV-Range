# HSV Threshold Editor
[Chinese](./Readme.md)
HSV threshold is usually used for color block recognition in opencv, etc.  
The color space of this threshold editor is `HSV_FULL` instead of `HSV`.  
# Usage
Download release version. (x86 version is not available at present, please compile by yourself.)  
[Release](https://github.com/h13-0/HSV-Range/releases)
## Open picture
`Open picture` button is `打开图片`, parameter is the path of the picture file.  
When using, you can manually enter a path in the text box on the left of the `打开图片` button and click the button to open the picture.  
You can also click the button to manually select file opening with the UI dialog box of the file manager **after clearing the text box** or **when the content of the text box is the last open path**. ~~You can find out how to use it by yourself.~~  
![Photo1.jpg](./Images/Photo1.jpg)
### HSV preview
HSV preview is to convert pictures into RGB color space for preview in real time.  
Click the radio box `HSV预览` to enter this mode.  
![Photo2.jpg](./Images/Photo2.jpg)
### Threshold editing effect
![Photo3.jpg](./Images/Photo3.jpg)
Of course, you can click the `重置阈值` button to reset the threshold.  

## Open video stream
Parameters can be camera ID, video file, HTTP video stream, etc.  
Parameter meaning is the same as OpenCV.  
For example, enter 1 to turn on camera 1, enter http://localhost:8888 Open HTTP video stream.
![Demo.gif](./Images/Demo.gif)