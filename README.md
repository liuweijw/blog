# blog
通过[Hexo](https://hexo.io/zh-cn/docs/) 搭建github博客系统

# 安装前提

安装 Hexo 相当简单。安装前，您必须检查电脑中是否已安装下列应用程序：
* Nodejs
* Git

# 安装Hexo
~~~
$ yarn global add hexo-cli
~~~

# 初始化项目
~~~
$ hexo init <folder>
$ cd <folder>
$ yarn install
~~~

# 配置项目 _config.yml

* [参考配置](https://hexo.io/zh-cn/docs/configuration)

# 编译项目
~~~
$ hexo g
~~~

# 本地运行项目
~~~
$ hexo s -p 3000
~~~

# 发布项目
~~~
$ yarn add hexo-deployer-git --save
$ hexo d
~~~
