# vs_fftw3
可在VS下编译的fftw3

1.将所有.c文件添加进项目
2.将各个子文件夹路径包含在vs附加包含目录中
3.设置C/C++ ——>输出文件 ——>对象文件名：$(IntDir)/%(RelativeDir)/ 
