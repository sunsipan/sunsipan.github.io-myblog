# Jekyll个人博客搭建
### [学习分享](https://sunsipan.github.io)
* Jekyll 是一个简单的博客形态的静态站点生产机器。它有一个模版目录，其中包含原始文本格式的文档，通过 Markdown （或者 Textile） 以及 Liquid 转化成一个完整的可发布的静态网站，你可以发布在任何你喜爱的服务器上。Jekyll 也可以运行在 GitHub Page 上，也就是说，你可以使用 GitHub 的服务来搭建你的项目页面、博客或者网站，而且是完全免费的

* 使用 Jekyll 搭建博客之前要确认下本机环境，Git 环境（用于部署到远端）、Ruby 环境（Jekyll 是基于 Ruby 开发的）、包管理器 RubyGems 
 　　如果你是 Mac 用户，你就需要安装 Xcode 和 Command-Line Tools了。下载方式 Preferences → Downloads → Components。

* Jekyll 是一个免费的简单静态网页生成工具，可以配合第三方服务例如： Disqus（评论）、多说(评论) 以及分享 等等扩展功能，Jekyll 可以直接部署在 Github（国外） 或 Coding（国内） 上，可以绑定自己的域名。Jekyll中文文档、Jekyll英文文档、Jekyll主题列表。

### 安装 jekyll
$ gem install jekyll  

### 创建博客
$ jekyll new myBlog    

### 进入博客目录
$ cd myBlog  


### 启动本地服务
$ jekyll serve

在浏览器里输入：本地端出现的网址 127.0.0.1:4000，就可以看到你的博客效果了。

## [目录结构](https://www.jekyll.com.cn/)
进入 _config.yml 里面，修改成你想看到的信息，重新 jekyll server ，刷新浏览器就可以看到你刚刚修改的信息了。
到此，博客初步搭建算是完成了，

## 博客部署到远端
部署到 Github Page 创建一个 github 账号，然后创建一个跟自己账户名一样的仓库，把刚才建立的 myBlog 项目 push 到 username.github.io仓库里去（username指的是你的github用户名），检查你远端仓库已经跟你本地 myBlog 同步了，然后你在浏览器里输入 username.github.io ，就可以访问你的博客了。
## 编写文章
所有的文章都是 _posts 目录下面，文章格式为 mardown 格式，文章文件名可以是 .mardown 或者 .md。
* 文章名的格式前面必须为  年-月-日-标题.MARKUP
## 修改成你自己的博客
根据自己的喜好以及风格改变自己博客的页面，
* 修改 _config.yml 文件里面的内容
* 文章位置_posts/ 

# sunsipan.github.io-myblog
