JekyII
==============================

what is jekyII
-------------------------
- 是一个静态网站生成器，会根据网页源码生成静态文件
- 提供了模板、变量、插件等功能

什么是静态网站生成器
-------------------------
将所有的页面、布局和帖子集合在一起，预先生成静态的站点的工具

what jekyII can do
-------------------------
- 文本转换引擎
- 整合标记语言格式书写的文本(Markdown, Textile or HTML)到一整套页面布局中

JekyII 使用
-------------------------
1. 设定站点的基本结构，使用HTML和Liquid模板语言创建网页布局
2. 创建一些帖子
3. 本地测试，查看效果
4. 部署网站

JekyII 基本结构
-------------------------
     .
     | -- config.yml
     | -- _includes
     | -- _layouts
     |   |-- default.html
     |   `-- post.html
     | -- _posts
     |   | -- 2013-05-01-first-blog.md
     |   ` -- 2013-05-01-secord-blog.md
     | -- _site
     ` -- index.html
    
    1. _config.yml   Jekyll的配置文件
    2. _includes/    include文件所在的文件夹
    3. _layouts/     模板文件夹
    4. _posts/       自己要发布的内容
    5. _site/        预览时产生的文件都放在该文件夹中

JekyII 变量
-------------------------
### 全局变量

    | 变量      | 描述
    |-----------|------------------------------------------- 
    | site      | 全站的信息+ _config.yml 文件中的配置选项
    | page      | YAML 前置数据，url 和 content
    | content   | 页面的子视图
    | paginator | 

### Site变量
### Page变量
### Paginator变量 
