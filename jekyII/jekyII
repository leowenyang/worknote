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

- _config.yml

Jekyll配置文件

- _includes/

该目录存放可以与_layouts和_posts混合、匹配并重用的文件。Liquid标签{% include file.md %}可以用于嵌入文件_includes/file.md

- _layouts/

该目录下存放的可以说成是你的“动态内容”。这些文件的格式很重要，它们的命名模式必须遵循 YEAR-MONTH-DATE-title.MARKUP 。每一个帖子的固定链接URL可以作弹性的调整，但帖子的发布日期和转换所使用的标记语言会根据且仅根据文件名中的相应部分来识别。

- _site/

这里是Jekyll用以存放最终生成站点的根路径位置。也许把它加到你的 .gitignore 列表中会是个不错的主意。

- index.html及其他文件

如果一个文件的头部存在YAML前置数据的部分，那么Jekyll将会自动处理转换该文件并传送到站点路径下。这对于站点的根目录或其他任意子目录下的所有 .html 、 .markdown 、 .textile 文件都适用

- 其他文件/目录

除了以上提到的文件之外，每一个其他的、不以下划线_开头的目录和文件都会被照原样传送到站点路径下。例如，你可以在网站根目录下面添加一个 css 目录，一个 favicon.ico 。
