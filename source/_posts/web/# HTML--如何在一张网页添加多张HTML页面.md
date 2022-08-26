# HTML--如何在一张网页添加多张HTML页面

- [HTML5](https://www.it610.com/search/HTML5/1.htm)

1.在一个网页有多个HTML页面。

使用标签

```
rows="25%,50%,25%">
```

把网站分成三部分，rows代表行，cols代表列。 

```
src="text2.html" noresize="noresize">
```

添加三个HTML的位置即可，noresize 代表网页的大小固定，不可调节，不加则可调节。 

2.定义三个跳转按钮

```
href="text6.html" target="showframe">页面一
href="text5.html" target="showframe">页面二
href="test3.html" target="showframe">页面三
```

我们在添加多个HTML的某个页面加入name

```
src="text4.html" name="showframe">
```

这样，就可以指定点击按钮，哪个HTML页面跳转。