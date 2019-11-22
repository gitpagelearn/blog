---
title: Markdown语法介绍
date: 2019-11-09 17:39:01
tags: 
- Markdown
---

在前面的课程中，我们已经成功搭建了我们的blog，并将它放到了github通过域名进行访问，今天我们来学习一下如何用Markdown来写文章。

首先简要介绍一下什么是Markdown：

- Markdown 是一种轻量级标记语言，它允许人们使用易读易写的纯文本格式编写文档。

- Markdown 语言在 2004 由约翰·格鲁伯（英语：John Gruber）创建。

- Markdown 编写的文档可以导出 HTML 、Word、图像、PDF、Epub 等多种格式的文档。

- Markdown 编写的文档后缀为 `.md`,  `.markdown`。

### 1.Markdown标题
我们使用`#`号来标记我们的标题,一共有六级标题,分别对应1到6个`#`号,如下

```
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题
```

对应显示效果如下

![image-20191108202908903](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20191108202908903.png)



### 2、Markdown段落
#### （1）字体
Markdown支持显示以下几种字体

```
*斜体文本*
_斜体文本_
**粗体文本**
__粗体文本__
***粗斜体文本***
___粗斜体文本___
```

对应显示效果如下：

![image-20191108203410562](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20191108203410562.png)

#### （2）分隔线
我们使用三个以上减号来建立分隔线

```
------ 分隔线
```
显示效果如下

![image-20191108203745695](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20191108203745695.png)

#### （3）删除线
删除线只需要在文字两端加上双波浪线即可~~

```
~~HELLO~~
```
显示效果如下
~~HELLO~~

#### （4）下划线

```
<u>下划线</u>
```
显示效果如下

<u>下划线</u>

### 3、Markdown列表
列表分为有序列表和无序列表
#### 1、无序列表如下所示（注意后面加一个空格）

```
- 第一项
- 第二项
- 第三项
```
显示效果如下
- 第一项
- 第二项
- 第三项

#### 2、有序列表如下所示（注意后面加一个空格）

```
1. 第一项
2. 第二项
3. 第三项
```
显示效果如下
1. 第一项
2. 第二项
3. 第三项

#### 3、列表嵌套用法

```
1. 第一项：
    - 第一项嵌套的第一个元素
    - 第一项嵌套的第二个元素
2. 第二项：
    - 第二项嵌套的第一个元素
    - 第二项嵌套的第二个元素
```
显示效果如下
1. 第一项：
    - 第一项嵌套的第一个元素
    - 第一项嵌套的第二个元素
2. 第二项：
    - 第二项嵌套的第一个元素
    - 第二项嵌套的第二个元素

### 4、Markdown引用

```
> 引用的一段话，这里演示用。
```
显示效果如下

> 引用的一段话，这里演示用。

### 5、Markdown代码
#### （1）、代码
```
`printf()`
```
显示效果如下
`printf()`

#### （2）、代码段

输入如下：

![image-20191108210014315](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20191108210014315.png)

显示效果如下：
```javascript
function test() {
	console.log("Hello world!");
}
```

### 6、Markdown链接
如下所示输入超链接

```
[百度](https://www.baidu.com)
```
显示效果如下（可点击跳转百度）
[百度](https://www.baidu.com)

### 7、Markdown表格

实例如下：

```
| 左对齐 | 右对齐 | 居中对齐 |
| :-----| ----: | :----: |
| 单元格 | 单元格 | 单元格 |
| 单元格 | 单元格 | 单元格 |
```

显示效果如下：

| 左对齐 | 右对齐 | 居中对齐 |
| :----- | -----: | :------: |
| 单元格 | 单元格 |  单元格  |
| 单元格 | 单元格 |  单元格  |

### 8、Markdown图片
插入图片我们需要先上传到图床网站获取链接，然后再插入图片链接，具体操作如下：
1. 我们首先打开网站https://imgchr.com/

2. 点击开始上传，上传一张我们想要的图

3. 上传好了我们找到下面Markdown Code并复制
    ![image-20191108211045231](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20191108211045231.png)

4. 将复制的链接粘贴过来

```
[![MZ53S1.md.jpg](https://s2.ax1x.com/2019/11/08/MZ53S1.md.jpg)](https://imgchr.com/i/MZ53S1)
```

显示成功如下

[![MZ53S1.md.jpg](https://s2.ax1x.com/2019/11/08/MZ53S1.md.jpg)](https://imgchr.com/i/MZ53S1) 

这是一些基本的用法,学会了这些我们就可以写一些基本的文章来记录自己的日常啦~~~