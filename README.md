SpiderManager
=============

数据库课程设计-爬虫管理系统

###爬虫管理系统说明

>将平时所作爬虫做以归纳管理

>提供方便与用户配置的接口

>引用微博API使用Oauth协议进行登陆操作

>初学前端与jsp.. 渣渣勿喷(-.-)

>使用Bootstrap框架与各种看不懂的模板拼凑开发..

####-------2014.11.18--------

>初步拼凑出一index.jsp页面

####-------2014.11.20--------

>增加动态图表，进一步推进微博Oauth登陆

>为通过微博审核将应用部署至http://spider.glacierlx.com

####-------2014.11.21--------

>增加配置页面，目前出现bug(由于版面id重复导致删除类别时没有反应)

####-------2014.11.26--------

>由于先前bug太多(总是出现编译错误)

>怀疑是由于使用IDEA打包时没有将引入的第三方jar文件打入WEB-INF/lib目录中所致

>于是索性更换调试时使用的servlet容器为jetty 采用maven进行打包操作

>目前编译错误问题得到解决，可以自由使用第三方提供的包

>所以可以方便的使用新浪提供的SDK进行微博相关操作

>目前已经完成微博登录功能

>由于未通过新浪审核，所以目前仅限我所指定的用户可以访问