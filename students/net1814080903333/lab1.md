# 实验一
## 一、实验目标
1. 搭建 Android（Android Studio）开发环境
2. 熟悉并掌握Git与GitHub.com提交实验代码的方法
## 二、实验内容
1. 安装Git并练习是使用Git bash
2. 安装与使用andriod studio 创建第一个项目
## 三、实验步骤
1. 下载Xcode、Android Studio;  
2. 搭建开发环境（Android Studio）;    
3. 加入Git项目（Fork），将项目克隆（Clone）到自己帐号下:  
- 进入终端输入如下代码:  
$ cd /Users/yaozhenbin  
$ git clone https://github.com/yichouge/android-labs-2020/  
$ cd android-labs-2020    
2.创建以学号命名的个人实验目录(在用户里创建)：  
   - students/net814080903333  (也可使用终端命令 mkdir /Users/yaozhenbin/android-labs-2020/students/net1814080903333)   
   - 编写edu.hzuapps.androidlabs.Net1814080903333Activity.java  
4. 使用git命令提交实验代码和结果  
$ cd /Users/yaozhenbin/android-labs-2020  
$ git add net1814080903333/*
$ git commit -m "#1 #72 第1次实验"  
$ git push  
## 四、实验结果
1. ![图1.android studio虚拟机运行结果](https://raw.githubusercontent.com/yichouge/android-labs-2020/master/students/net1814080903333/lab1.png)
## 五、实验心得
本次实验我遇到挺多问题的第一是运用命令把github上的多余或错误文件删除，结果我把自己的student文件删除了，原因是我少写了一级目录结果不得不把老师库里的所有文件克隆到本地，寻求老师和同学帮助后我懂得了
如何用命令删除GitHub上自己库内的文件。我使用的设备是Mac所以下载Xcode自带git功能所以安装git我选择下载Xcode可以直接在APPStore里下载比较方便。
