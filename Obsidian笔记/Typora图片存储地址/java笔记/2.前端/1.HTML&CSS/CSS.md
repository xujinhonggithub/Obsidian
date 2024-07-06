# CSS

## 1. 参考资料

[Flex 布局教程--阮一峰](http://www.ruanyifeng.com/blog/2015/07/flex-grammar.html)

[W3Cschoool菜鸟教程](http://home.ustc.edu.cn/~xie1993/index.htm)

## 2. 文本省略

### 单行省略

```
white-space:nowrap;
overflow:hidden;
text-overflow:ellipsis;
```

### 多行省略

```
word-break: break-all;
text-overflow: ellipsis;
overflow: hidden;
display: -webkit-box;
-webkit-line-clamp: 2;
-webkit-box-orient: vertical;
```

## 3. Transform详解(图片位移)

参考: 	 https://www.jianshu.com/p/8a33214a1b26

```
.tramsform{
        /*transform: translateY(100px) rotate(30deg) scale(1 , 2) skew(30deg,0deg);*/
        /*transform: matrix(1,1,1,1,3,1)*/
        /*transform: rotate(45deg);*/
        /*transform-origin:left top;*/
    }
```

## 4. 移除样式

```
*{margin:0;padding:0}

 li{list-style:none}

img{vertical-align:top;border:none}
```

## 5. 文本首行缩进2格

```
style="text-indent: 2em"
```

