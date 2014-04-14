
昂信嵌入式 git 使用文档
=================================


目录

.. toctree::
   :maxdepth: 2

   git


Git 使用安装文档
===============
   在LINUX上安装，可以用系统提供的包管理工具，$ yum install git-core
   在Ubuntu这类系统上，用apt-get 安装，$ apt-get install git-core
   在Windows上安装，可以从Google Code上下载安装文件(.exe):  http://code.google.com/p/msysgit?或者去官网下载　  http://git-scm.com/
   下一步 
   任何人在使用git之前，都要提交简单的个人信息，以便git区分不同的提交者身份
   git config --global user.name --your name
   git  config --global user.email -your@example.com"

   3

   新建的一个项目，就先建立一个目录，例如名为：myproject，然后所有的项目开发内容在此目录下进行
   $cd myproject
   $ git init
   $ git add .
   $git commit
 
   4

   如果改进了项目源代码，并且到了开发者认为应该再次记录开发信息的时候，则提交工作成果使用
   如下命令
   $ git commit -a
 

   5
   看图形化分支信息
   $　gitk我每次都是图形化提交项目源的。　　然后再git push origin master　一下


   6
   当然也可以clon别人的项目来与自己的合并
   $git clone(地址)



   
  

Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

