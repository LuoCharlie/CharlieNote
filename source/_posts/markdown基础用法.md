---
title: markdown基础用法
date: 2024-05-30 17:36:38
tags: [markdown]
categories: '技术'
isInRecentPost: true
---
# 前言
好几没纯用markdown写文档了，回顾一下，正好试一下博客发布。

## 基础用法

尝试一下换行<br>换行结束

尝试一下 **粗体**  再尝试一下**粗体**

尝试一下*斜体*

尝试一下 ***粗体斜体***

有序列表
1. 哈哈
2. 嘻嘻
3. 呵呵
4. 嘿嘿

无序列表
* 11
* 22

    > 列表里的引用块
* 33
  
    列表里的段落
* 44

> 尝试一下块引用

> 尝试一下多个段落块引用段落
> 
> 段落1
>
>> 再来嵌套一下
>>
>> 嵌套段落
>
> 段落2
>
> 段落3
>

试一下转义咯 \*\*123123\*\*

## 代码块
第一种代码区块

    javascript
    const test = 1

第二种代码区块：可选择语言类型
```js
const test = 1;
console.log(test);
```

第三种在段落里的`javascript console.log(test)`代码块

## 表格

|基础表格|表头|
|:---|---:|
|1单元格|2单元格|
|3|4|


## 图片
![我有一张图片](https://github.com/LuoCharlie/picx-images-hosting/raw/master/CharlieNote/2221699197138_.pic.1vyhlpd5hq.webp)

图床地址
> https://picx.xpoet.cn/#/management


## 其他内容
使用 <kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>Del</kbd> 重启电脑 


所有需要转义的符号: \
\\   反斜线\
\`   反引号\
\*   星号 \
\_   下划线\
\{\}  花括号\
\[\]  方括号\
\(\)  小括号\
\#   井字号\
\+   加号\
\-   减号\
\.   英文句点\
\!   感叹号\

&emsp;&emsp;缩进一下


## markdown语法如下

```markdown
# 前言
好几没纯用markdown写文档了，回顾一下，正好试一下博客发布。

## 基础用法

尝试一下换行<br>换行结束

尝试一下 **粗体**  再尝试一下**粗体**

尝试一下*斜体*

尝试一下 ***粗体斜体***

有序列表
1. 哈哈
2. 嘻嘻
3. 呵呵
4. 嘿嘿

无序列表
* 11
* 22

    > 列表里的引用块
* 33
  
    列表里的段落
* 44

> 尝试一下块引用

> 尝试一下多个段落块引用段落
> 
> 段落1
>
>> 再来嵌套一下
>>
>> 嵌套段落
>
> 段落2
>
> 段落3
>

试一下转义咯 \*\*123123\*\*

## 代码块
第一种代码区块

    javascript
    const test = 1

第二种代码区块：可选择语言类型
\`\`\`js
const test = 1;
console.log(test);
\`\`\`

第三种在段落里的`javascript console.log(test)`代码块

## 表格

|基础表格|表头|
|:---|---:|
|1单元格|2单元格|
|3|4|


## 图片
![我有一张图片](https://github.com/LuoCharlie/picx-images-hosting/raw/master/CharlieNote/2221699197138_.pic.1vyhlpd5hq.webp)

图床地址
> https://picx.xpoet.cn/#/management


# 其他内容
使用 <kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>Del</kbd> 重启电脑 


所有需要转义的符号: \
\\   反斜线\
\`   反引号\
\*   星号 \
\_   下划线\
\{\}  花括号\
\[\]  方括号\
\(\)  小括号\
\#   井字号\
\+   加号\
\-   减号\
\.   英文句点\
\!   感叹号\

&emsp;&emsp;缩进一下
```