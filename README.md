# simon_auto_test
捕获android app崩溃日志的自动化脚本.

1.1 环境搭建
主要解决android app测试过程中的盲目“点”，bug无法复现，问题无法准确定位的痛点，通过使用抓取测试过程中遇到问题的log ,准确定位问题，做到有的放矢.
1.2 安装JDK配置环境变量
(1）下载JDK并安装，以Windows 64位为例 ，打开下载链接
jdk下载地址 
（2）配置环境变量
JDK安装路径：JAVA_HOME = D:\jdk1.8.0_131
CLASS_PATH=
.;%JAVA_HOME%\lib\dt.jar;%JAVA_HOME%\lib\tools.jar;
PATH = %JAVA_HOME%\bin\;%JAVA_HOME%\jre\bin
改一下安装目录就可以用了.
  (3)环境校验
  在dos中输入java 或者 javac有提示信息，表示成功.
  
（4）安装ADT Bundle
           选择32位或者64位,下载并安装:adt-bundle 
           环境配置：
           ANDROID_HOME=D:\adt-bundle\sdk\
           PATH=%ANDROID_HOME%\platform-tools\;
                %ANDROID_HOME%\tools\ 
           环境检查：
 在dos中输入adb有提示信息，表示成功.
           
