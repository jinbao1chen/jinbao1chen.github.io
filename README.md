### 环境要求

* Jekyll 支持: Mac 、Windows、ubuntu 、Linux 操作系统                     
* Jekyll 需要依赖: Ruby、bundler

### 使用手册

原作者的博客：[Jekyll搭建个人博客](https://leopardpan.cn/2016/10/jekyll_tutorials1/)  :  使用Jekyll搭建个人博客的教程，及如何把这个博客模板修改成你自己的博客，里面也有大量的评论、Jekyll 搭建博客各种环境出现过的问题。

#### 安装Jekyll

[Jekyll中文官方文档](http://jekyll.bootcss.com/) ， 如果你已经安装过了 Jekyll，可以忽略此处。

> $ gem install jekyll

#### 获取博客模板

> $ git clone https://github.com/leopardpan/leopardpan.github.io.git

或者直接[下载博客](https://github.com/leopardpan/leopardpan.github.io/archive/master.zip)   

进leopardpan.github.io/ 目录下， 开启本地服务

> $ jekyll server

在浏览器输入 [127.0.0.1:4000](127.0.0.1:4000) ， 就可以看到博客效果了。

### 搭建过程可能需要查阅的一些资料
* 搭建博客视频教程
> https://www.bilibili.com/video/BV14x411t7ZU?from=search&seid=2757499629640417432

* 安装Atom
>  https://www.cnblogs.com/EasonJim/p/7570667.html

* 安装jekyll可能遇到的问题
> https://blog.csdn.net/rui888/article/details/103822690

* 百度统计注册
> https://tongji.baidu.com/web/welcome/login

* 来必力注册
> http://livere.com/my_Livere

### 提示

>* 如果你想使用原作者的模板，请把 _posts/ 目录下的文章都去掉。
>* 修改 _config.yml 文件里面的内容为你自己的个人信息。

### 如何写博客
所有的文章都是 _posts 目录下面，文章格式为 mardown 格式，文章文件名可以是 .mardown 或者 .md。

　　编写一篇新文章很简单，你可以直接从 _posts/ 目录下复制一份出来 2016-10-16-welcome-to-jekyll副本.markdown ，修改名字为 2016-10-16-article1.markdown ，注意：文章名的格式前面必须为 2016-10-16- ，日期可以修改，但必须为 年-月-日- 格式，后面的 article1 是整个文章的连接 URL，如果文章名为中文，那么文章的连接URL就会变成这样的：http://leopardpan.cn/2015/08/%E6%90%AD%E5/ ， 所以建议文章名最好是英文的或者阿拉伯数字。 双击 2016-10-16-article1.markdown 打开

---
>* layout: post

>* title:  "Welcome to Jekyll!"

>* date:   2016-10-16 11:29:08 +0800

>* categories: jekyll update
---

正文...

title: 显示的文章名， 如：title: 我的第一篇文章

date: 显示的文章发布日期，如：date: 2016-10-16

categories: tag标签的分类，如：categories: 随笔

注意：文章头部格式必须为上面的，…. 就是文章的正文内容。

原作者写文章使用的是 Sublime Text2 编辑器，如果你对 markdown 语法不熟悉的话，可以看看https://www.zybuluo.com/mdeditor       


### 把这个博客变成你自己的博客

根据上面【提示】修改过后，在你的github里创建一个username.github.io的仓库，username指的值你的github的用户名。      
创建完成后，把我的这个模板使用git push到你的username.github.io仓库下就行了。


### 如何git push
1.本地仓库修改完毕后，进入到~/github/jinbao1chen.github.io$执行：git add .

2.检查当前的git状态: git status

3.commit推送,将缓存区的修改提交到本地仓库: git commit -m "first time to upload github"

4.如果该仓库是第一次进行push，则指令如下：git push origin master

4.1 如果不能push成功，多push几次。https://blog.csdn.net/u013171226/article/details/115306396

5.之前已经传输过，此处只是更新，所以只需输入：git push

参考博客：https://www.cnblogs.com/wmr95/articles/7768492.html



#### 感谢   

本博客在[潘柏信大佬的个人博客](https://github.com/leopardpan/leopardpan.github.io.git)基础上修改的。  
