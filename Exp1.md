# 安装 Android Studio  
1. 进入网站 https://developer.android.google.cn/studio 下载软件并安装,本次实验使用如下版本：  
![0](https://github.com/Bucky95/Android/blob/main/images/02.png?raw=true)
2. 安装后界面如下：  
![1](https://github.com/Bucky95/Android/blob/main/images/01.png?raw=true)  
3. 创建一个新项目，并使用数据线将安卓手机连接至电脑，运行项目，在手机中观察结果：  
![2](https://github.com/Bucky95/Android/blob/main/images/13.jpg?raw=true)  
# 安装 Anaconda和jupyter notebook  
1. 启动Anaconda的Navigator，在该面板中启动jupyter notebook  
![3](https://github.com/Bucky95/Android/blob/main/images/05.png?raw=true)  
2. 也可以通过Anaconda的powershell终端进行启动，在终端中输入jupyter notebook  
![4](https://github.com/Bucky95/Android/blob/main/images/03.png?raw=true)  
3. jupyter notebook界面如下：  
![5](https://github.com/Bucky95/Android/blob/main/images/04.png?raw=true)  
4. 在jupyter notebook中运行python程序:  
![6](https://github.com/Bucky95/Android/blob/main/images/10.png?raw=true)  
# 修改jupyter notebook的默认路径
1. 启动Anaconda终端，输入 jupyter notebook --generate-config 在初始路径中生成一个默认配置文件  
![7](https://github.com/Bucky95/Android/blob/main/images/07.png?raw=true)  
2. 使用记事本方式打开该文件,并查找关键字 c.NotebookApp.notebook_dir 然后给其赋值 E:\Android\Android  
![8](https://github.com/Bucky95/Android/blob/main/images/08.png?raw=true)  
3. 打开jupyter的快捷方式的属性，删除目标一栏中最后的值 %USERPROFILE% ，并添加路径 E:\Android\Android  
![9](https://github.com/Bucky95/Android/blob/main/images/14.png?raw=true)  
4. 启动jupyter 观察界面变化  
![10](https://github.com/Bucky95/Android/blob/main/images/09.png?raw=true)
