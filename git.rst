

Git 使用安装文档
===============     

=============== 
   第一步  
=============== 

   * 在LINUX上安装，可以用系统提供的包管理工具，\**$ yum install git-core**\  
   * 在Ubuntu这类系统上，用apt-get 安装，$ apt-get install git-core
   * 在Windows上安装，直接去官网下载  http://git-scm.com/  

==================
   第二步  
==================

   * 任何人在使用git之前，都要提交简单的个人信息，以便git区分不同的提交者身份
          * git config --global user.name --your name"
          * git  config --global user.email -your@example.com"

=============== 
   第三步    
=============== 

   * 新建的一个项目，就先建立一个目录，例如名为：myproject，然后所有的项目开发内容在此目录下进行
       * '--$cd myproject'
       * '--$ git init'
       * $ git add .
       * $git commit

===============  
   第四步    
===============   

   * 如果改了项目源代码，提交工作成果使用如下命令：
       * $ git commit -a
 
===============     
   第五步   
===============   

   * 图形化分支信息
       * $ gitk每次本人是用图形化界面进行项目源提交；然后再git push origin master一下


===============   
   第六步   
===============   

   * 也可以clon别人的项目来与自己的合并
       * $git clone(地址)




