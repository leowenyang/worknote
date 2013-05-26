vim mode note
==============================
Insert Mode
-------------------------
    CTRL-a          插入最近插入的文本
    CTRL-t/CTRL-d   将本行缩进/去缩进,无论光标在什么位置
    CTRL-u          删除当前行的所有输入字符
    CTRL-w          删除光标前的单词
    CTRL-y          插入光标上方的单词
    CTRL-e          插入光标下方的单词
    CTRL-n/CTRL-p   搜索匹配,自动完成单词

### CTRL-X 模式

CTRL-X 模式基本上是用来自动完成的.vim的自动完成可以包含当前文件、头文件、tag文件、字典文件等

    CTRL-x CTRL-l          整行自动完成
    CTRL-x CTRL-p/CTRL-n   在当前文本中自动完成单词
    CTRL-x CTRL-i          在头文件中查找匹配的单词
    CTRL-x CTRL-]          在tag中补全单词
    CTRL-x CTRL-f          自动完成文件名
    CTRL-x CTRL-d          在头文件中查找宏定义
    CTRL-x CTRL-o          全能(omni)补全
    
Normal Mode
-------------------------
    CTRL-g                 显示当前文件名和位置
    CTRL-o                 跳转到跳转表表里的第N个较旧的项目 
    CTRL-t                 跳转到标签列表的第N个较老的标签
    CTRL-]                 跳转到光标所在的标示符
    CTRL-r                 重做'u'撤销的改变

Visual Mode
-------------------------
    U                      使高亮区域变大写
    u                      使高亮区域变小写

Command Mode
------------------------

