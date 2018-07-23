

博客搭建
=======================================
    Github        托管项目
  
    Sphinx        生成网页
  
    ReadtheDocs   发布网页

安装 Sphinx
---------------------------------------

- 下载安装

由于我使用了Anaconda,Sphinx库已经自带了，所以不做说明，没使用的可自行pip安装这个库
  
- 初始化

    - 创建工程目录：    mkdir+文件夹名称
  
    - 转到工程目录下：  cd+目录地址
  
    - 初始化项目 ::
	
	    sphinx-quickstart

到这一步初始化基本完成，之后一路选择默认就好

- 个性化配置：

    - Project name;	
    - Author name;	
    - Project release[]:1.0;	
    - Project language[en]:zh_CN

- 创建成功

    - build:html文件存放地
    - source:源文件所在地
    - Makefile:编译文件	
    - make.bat:WIN脚本

- 开始写博客

在source目录下新建xxx.rst。在里面开始写内容，保存之后在把文档写进目录排版index.rst里。
  
目录配置文件：source\\index.rst
  
插入图片吧，写太麻烦

- 生成网页

在终端项目目录下输入 ::

    make html
  
再打开 build\\html\\index.html  
    


项目托管
----------------------------------------




