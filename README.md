﻿优创软件平台
===========

优创软件平台。使用Spring .NET、ASP .NET MVC、ELinq作为基本项目架构，Web Api作为移动App接口、同时使
Unit Test单元测试、RouteDebug路由测试、Log4Net日志记录、支持多数据库，目前支持Access、SQLServer、SqlCE、SQLite、MySQL、ORACLE，未来还会支持更多的数据库、T4模板代码自动生成
、Bootstrape作为前端框架。

版本信息
-------
>版本: V1.0     
>开发工具：Microsoft Visual Studio 2013      
>作者: Terwer,Huang   
>作者邮箱: cbgtyw@gmail.com   
>作者博客: [http://www.terwer.com](http://www.terwer.com)       

项目简介
-------
>优创软件平台。使用Spring .NET、ASP .NET MVC、ELinq作为基本项目架构，Web Api作为移动App接口、同时使
Unit Test单元测试、RouteDebug路由测试、Log4Net日志记录、支持多数据库，目前支持Access、SQLServer、SqlCE、SQLite、MySQL、ORACLE，未来还会支持更多的数据库、T4模板代码自动生成
、Bootstrape作为前端框架。


技术架构
------



>1、本程序基于Asp .Net 4.0和.NET MVC4，编译版本为VS2013，最低运行版本为.Net 4.0，IIS 6.0+；  
>2、支持Access、SQLServer、SqlCE、SQLite、MySQL、ORACLE数据库切换，使用 ELinq作为ORM框架。    
>3、兼容IE6、7、8+、Firefox、Chrome、Safari             
>4、层次结构
>>UCsoft.Doc
>>=============
说明：项目文档

>>UCsoft.Web（Web主项目）提示：时间关系，只列了部分，其他的类似
>>=====================

>>|--App_Start
>>>|--RouteConfig.cs（路由配置信息）

>>|--Areas(区域，包含项目中的所有模块)

>>|--Themes（存放界面主题（CSS和图片、js脚本和js库））
>>>|--default（默认主题）



更新历史
-------
2014-11-05
----------
>1、平台初始化。

关键点
------


程序发布
-------
1、如果使用MySQL数据库，需要安装 mysql-connector-net-6.8.3.msi。   

参考资料
-------
1、Markdown css   
[http://www.oschina.net/question/124879_76399](http://www.oschina.net/question/124879_76399)   
2、Markdown语法   
[http://equation85.github.io/blog/markdown-examples/](http://equation85.github.io/blog/markdown-examples/ )  
3、Asp.Net MVC路由调试的好帮手RouteDebugger   
[http://www.cnblogs.com/dingji/archive/2012/05/17/2506587.html](http://www.cnblogs.com/dingji/archive/2012/05/17/2506587.html)   
4、使用Areas分离ASP.NET MVC项目     
[http://www.cnblogs.com/dingji/archive/2012/05/30/2506420.html](http://www.cnblogs.com/dingji/archive/2012/05/30/2506420.html)     
5、ELinq    
[http://elinq.codeplex.com/](http://elinq.codeplex.com/)

改进方案
-------                                                               
1、SqLite和Oracle暂时未进行严格测试。                                                





  
