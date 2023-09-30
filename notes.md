# 网页属性相关内容

### 网页基础标签

```
<!DOCTYPE HTML>
<!--<>标签！强调声明 doctype文档类型 空格 为html 告诉浏览器 我是一个H5标准的文档-->
<html lang="en"><!--双标签 结构性标签 内部需要包裹内容或者其他标签-->
<head> <!--网页的基本信息-->
  <meta charset="utf-8"> <!--设置网页的展示语言设置字符集编码-->
  <meta name="keywords" content="关键字"> <!--让用户可以通过关键字在搜索引擎中找到我们的网页-->
  <meta name="description" content="用一句话描述本网页，打广告">
  <title>网页的标题标签</title>
</head>    
</html>
```

> `<br>`换行符标签，单标签，不推荐
>
> ``` 
> <p>
>  段落标签，用这个标签，每一个段落都是独立的一行。语义化标签，有专门的指代性的名词。 
> </p>
> ```

> `<hr>`横线标签
>
> `<a href="https://www.baidu.com/" target='_blank'>百度</a>`
>
> 1. a 超链接标签；
>    + target 打开网页的位置（目标）：当前 _self | 新开 _blank
>
> 2. href 属性，跳转目的地址：
>
> + 跳转到公网地址 https://www.baidu.com/
>
> + 页面内部跳转
>   + id 独立的号码，唯一的，用#表示 href="id名称" 跳转到id为id名称的标签上
> + 路径跳转
>   + 相对路径：以自身为基准去其他地方寻址的过程
>     + 同级文件路径 "test.html"
>     + href="../test.html"  ”..“表示到上级文件路径
>     + 上级其他文件夹路径，先到上级文件夹路径"../上级其他文件夹名字/test.html"
>     + 下级路径，同级文件夹里，/文件夹名字/test.html
>   + 绝对路径（找的麻烦的时候用绝对路径）：以客观地址为基准进行寻址
>     + windows： "D:\文件夹名字\test.html"
>     + Linux："D://文件夹名字/test.html"
### 网页三要素

```
<meta name="keywords" content="关键字"> <!--让用户可以通过关键字在搜索引擎中找到我们的网页-->
<meta name="description" content="用一句话描述本网页，打广告">
<title>网页的标题标签</title>
```

### BODY标签

> 网页主体内容展示区域

### h1-h6标签

> h1：一个网站只有一个h1标题
>
> h2：网页的分块标题，2-5个
>
> h3：主页详细分块内容的标题，个数根据需求来
>
> h4：非主页下的列表内容标题，相对h3的权重更低

### html内容

> 浏览器不会解析多余的空格，制表符和换行符### Base标签

> 统一修改页面内部超链接的跳转标签方式![image-20230710213814702](C:\Users\Xie\AppData\Roaming\Typora\typora-user-images\image-20230710213814702.png)
>
> 如上图，可以让所有超链接默认打开新页面

### 文本格式化标签

> 加粗、斜体、下划线和删除线
>
> ![image-20230711110014407](C:\Users\Xie\AppData\Roaming\Typora\typora-user-images\image-20230711110014407.png)
>
> 没有语义性的意思是只是表示效果，有语义性是表示给浏览器看的，表示强调。 

### 注释标签

> HTML中<!-- 注释内容-->表示注释标签
>
> “ctrl+/”就是注释的快捷键
>
> CSS中<* 注释内容 *>表示注释
>
> 
