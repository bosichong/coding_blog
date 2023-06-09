## coding_blog 碎言静态博客主题

### 介绍
这是一款适合程序员的简约blog。

本项目为[碎言静态博客](https://github.com/bosichong/suiyan.git)主题。

[碎言静态博客Gitee](https://gitee.com/J_Sky/suiyan)

[碎言静态博客GitHub](https://github.com/bosichong/suiyan.git)

### 效果展示

![](doc/111.png)


### 技术框架

主题模板采用了jinja2的模板引擎，使用了Bootstrap5.3等框架，模板设计移动优先。


### 安装教程

1. 首先克隆下载本主题到碎言静态博客程序`theme`目录下。
2. 复制主题目录下的`config_.json`到主目录下。
3. 更换`s.py`中的配置项`APP_CONFIG = "config_my.json"`为当前的配置文件
4. 修改配置文件 `config_.json`中的"theme": "coding_blog",即可启用。


### 运行预览

本地主题开发编写，推荐使用`Live Server`这个vscode得插件，非常方便。
在配置文件里修改：
"dev": 1,  # 调试模式，如果改为1，则使用"blog_test_url"来添加静态资源地址前缀，方便本地调试。

### 修改主题样式

主题采用jinja2模板引擎，在主题或是模板目录修改样式，一键生成页面，直接同步页面。
在jinja2 模板中使用`{{ 属性名称 }}`来调用。

### github pages

如何部署GitHub pages 搭建自己的博客，请参考下文。

[GitHub Pages 快速入门](https://docs.github.com/zh/pages/quickstart)

除了部署GitHub，也可以将静态文件部署到虚拟主机云服务器上，复制静态文件目录下的所有文件到你的站点目录下即可。

