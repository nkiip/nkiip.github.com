---
title: How to post
---

**对如何更新及发布本站博文进行说明**

<!-- more -->

## 上传与同步

### 初始工作

- 确认自己电脑安装了[git](https://git-scm.com/downloads)同步工具
- 在希望放置项目文件的根目录下右键 *git bash here* 执行  
`git clone https://github.com/nkiip/nkiip.github.com nkiip.github.com`
- 在控制面板中打开凭据管理器切换到实验室git账号	(nkcsiip@gmail.com  nkcs313)
- 在第二次及之后每次上传之前请先执行  
`git pull origin master`

### 上传
> `git add . `  
> `git commit –m “*decription for this commit*”`  
> `git push origin master`

### 同步
> `git pull origin master`

## 关于编写博文

- 本站博文均位于 ***/_posts*** 目录下，且应遵循统一命名规范：`year-month-day-description`  
<u>不建议包含中文字符于文件名内，有可能无法解析</u>
- 本站有许多博文示例代码，存放于 **/示例博文** 目录下，对应显示效果请点击[这里](http://simpleyyt.com/jekyll-jacman/)，本站的许多配置信息也可在该页面查询

### markdown常用语法说明  

**上方显示书写代码下方显示实际显示效果**

- 标题

```
# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6
```

# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6


- 段落及突出显示
  
```
Lorem ipsum dolor sit amet, [test link]() consectetur adipiscing elit.  
 **Strong text** pellentesque ligula commodo viverra vehicula.   
*Italic text* at ullamcorper enim. Morbi a euismod nibh.   
<u>Underline text</u> non elit nisl. ~~Deleted text~~ tristique, sem id  

Interdum et malesuada fames ac ante ipsum primis in faucibus. `Sed erat diam`,  
Lorem <sup>superscript</sup> dolor <sub>subscript</sub> amet  
<cite>cite</cite>. Nunc iaculis suscipit dui.  
<acronym title="National Basketball Association">NBA</acronym> Mauris a ante.  
 Suspendisse quam sem, consequat at, commodo vitae, feugiat in, nunc. Morbi imperdiet augue quis tellus.  <abbr title="Avenue">AVE</abbr>  

> Praesent diam elit, interdum ut pulvinar placerat, imperdiet at magna.
```
Lorem ipsum dolor sit amet, [test link]() consectetur adipiscing elit.  
 **Strong text** pellentesque ligula commodo viverra vehicula.   
*Italic text* at ullamcorper enim. Morbi a euismod nibh.   
<u>Underline text</u> non elit nisl. ~~Deleted text~~ tristique, sem id  

Interdum et malesuada fames ac ante ipsum primis in faucibus. `Sed erat diam`,  
Lorem <sup>superscript</sup> dolor <sub>subscript</sub> amet  
<cite>cite</cite>. Nunc iaculis suscipit dui.  
<acronym title="National Basketball Association">NBA</acronym> Mauris a ante.  
 Suspendisse quam sem, consequat at, commodo vitae, feugiat in, nunc. Morbi imperdiet augue quis tellus.  <abbr title="Avenue">AVE</abbr>  

> Praesent diam elit, interdum ut pulvinar placerat, imperdiet at magna.

### 一些需要注意的

- 每一个博文最开始应包含下方***title***内容 其余仅供需要时使用

```
---
title: 组会与讨论班_2017_1 #文章所显示的标题 必含
date: 2017-10-24 10:29:08 #日期与时间 可有可无
tags:
- Group Meeting #文章所属标签
excerpt_separator:  <!--more--> #在首页是否全部显示
---
```

- 关于换行  

若在paragragh中需要自行换行请打`两个空格加回车`  

- 注意行首标识与内容之间有空格
- 一些更高级的显示功能请参照示例博文及对应显示效果



