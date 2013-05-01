Markdown Grammar Tutorial
==============================
> block Element
>
> inline Element
>
> 兼容HTML

block Element
-------------------------
- h1-h6
    1. ====  表示最高标题
    2. ----  表示第二阶标题
    3. 1-6 个#，对应标题1到6阶    
- p  : 空行 + 回车
- br : 两个以上空格 + 回车
- li
    1. 无序列表用"*,+ -" 表示
    2. 有序列表用"数字. " 表示  
- blockquote : > 表示
- pre : 缩进4个空格或1个制表符
- 分割线 : 一行中三个以上的*、-、_

inline Element:
-------------------------
- em and strong : * 或 _包围
- code : ` 包围
- a
    1. * \[文字\]\(url\)
    2. * \[文字\]\(url "文字"\)
- img : ![Alt text][id]

兼容HTML
-------------------------
Markdown 中可以直接引用HTML标签,但

- Markdown 中未定义的标签，可以直接在文档里面用HTML撰写.  
- 一些区块元素,比如<div> <table> <pre> <p>, 须在前后加上空行。
