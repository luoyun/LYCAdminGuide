LuoYunCloud 管理员手册
=====================

这是 LuoYunCloud 的管理员手册。


如何生成手册：

1. 安装 publican 工具 ( [安装方法](http://jfearn.fedorapeople.org/en-US/Publican/2.7/html/Users_Guide/chap-Users_Guide-Installing_Publican.html) )

2. 获取本项目

    git clone git://github.com/luoyun/LYCAdminGuide.git

3. 进入 LYCAdminGuide 目录，发布 html 格式：

    publican build --formats html --lang zh-CN --common_content=Common_Content/
