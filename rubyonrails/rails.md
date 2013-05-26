ruby on rails on the road
==============================
Install
-------------------------
1. ruby

ruby tools => irb, 
2. rubygems
3. rails
4. bundle
5. Rake => Ruby 的命令行工具

rails structure
-------------------------

    ---------------------------------------------------------------------
	Gemfile  |  设定Rails会使用哪些Gems插件
    README   |  用来告诉其他人软件是做什么的，如何使用
    Rakefile |  用来载入可以被命令行执行的一些Rake任务
    app/     |  存放Controllers Models 和 Views file
    config/  |  程序的设定文档、路由规则、资料库设定等等
    config.ru|  用来启动程序的Rack服务器配置文档
    db/      |  资料库的结构纲要
    doc/     |  用来放你的文件
    lib/     |  放一些自定的Module和类别文件
    log/     |  程序的Log记录文件
    public/  |  唯一在网络上看到的目录，存放JavaScript CSS和其它静态文件
    script/  |  放rails这个指令和其他的script指令
    test/    |  单元测试 fixtures及整合测试
    tmp/     |  暂时性的文件
    vendor/  |  用来放第三方程序的的目录
    ----------------------------------------------------------------------

rails operate
-------------------------

- rails 安装套件  =>  bundle install (every modify Gemfile need execute)
- 启动rails 服务  =>  rails server (need work catalog execute)
- 创建rails工程   =>  rails new project_name
- 创建controller  =>  rails generate controller controller_name
- 建立数据库      =>  bundle exec rake db:create
- 建立 CRUD       =>  rails g scaffold person name:string bio:text birthday:date(scaffold 会自动产生一组Model Views Controller代码)
- 

