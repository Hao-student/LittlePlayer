# LittlePlayer
## 项目说明
程序代码：`littlePlayer.cpp`  
创建工程：CMake  
编译工程：VS 2019  
项目中包括FFmpeg，SDL和openAL的库文件：`.dll`文件，`include`文件夹和`lib`文件夹    
## 使用说明
1.项目编译成功后，`build`文件夹中会生成`Debug`文件夹  
2.`Debug`文件夹中会生成`littlePlayer.exe`应用程序文件  
3.在该应用程序文件所在目录下打开cmd窗口  
4.输入命令`littlePlayer xxx.mp4`  
5.传递给程序的启动参数是测试文件的文件路径，若文件与`littlePlayer.exe`文件在同一文件夹下，则可直接将文件名作为启动参数  
6.若输入正确的命令后遇到`查找不到.dll文件`错误信息，请将所需的`.dll`文件复制到`C:\Windows\System32`目录下即可解决  
7.若在VS编译程序过程中遇到`无法打开xxx.lib文件`错误信息，请确认程序是否正确附加包含目录和库目录
