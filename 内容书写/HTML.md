 
## HTML语法
```
HTML语法为关标签构成
```
### 一、标题

在想要设置为标题的文字两面加`<hn>title</hn>`来表示  
h1是一级标题，h2是二级标题，以此类推。支持六级标题。



示例：

```
<h1>一级标题</h1>
<h2>二级标题</h2>
<h3>三级标题</h3>
<h4>四级标题</h4>
<h5>五级标题</h5>
<h6>六级标题</h6>
```

效果如下：
<h1>一级标题</h1>
<h2>二级标题</h2>
<h3>三级标题</h3>
<h4>四级标题</h4>
<h5>五级标题</h5>
<h6>六级标题</h6>

### 二、字体
em：显示倾斜  
strong：显示加粗  
i：倾斜  
b：加粗  
```
<em>em标签，</em>  
<strong>strong标签</strong>  
<i>i标签</i>  
<b>b标签</b>  
<u>u标签</u> 
```
效果如下：  
 <em>em标签，</em>  
<strong>strong标签</strong>  
<i>i标签</i>  
<b>b标签</b>  
<u>u标签</u> 


### 三、引用
<blockquote>块引用</blockquote>  

<q cite="www.jredu100.com">q标签，短引用</q>  


<cite>cite引用</cite>  



### 四、分割线
```
<hr/>
```
效果：
<hr/>


### 五、图片
示例：
```
<img 
src="https://ss0.bdstatic.com/70cFvHSh_Q1YnxGkpoWK1HF6hhy/it/u=702257389,1274025419&fm=27&gp=0.jpg"
width="100"height="100" 
title="鼠标指上时显示"
alt="图片无法加载"
align="bottom"
/>
```
src属性表示图片所在的路径。  
width、height 宽度和高度属性  
title:鼠标指上时显示的文字  
alt：图片无法加载时显示的文字。省略alt，将默认显示title内容  
align：图片周围的文字，相对于图片的排列方式；top文字居上 center居中 bottom文字居底
### 六、超链接
```
超链接<a herf="www.baidu.com">百度</a>
```
显示效果：
<a herf="www.baidu.com">百度</a>
### 七、列表
```
列表之间的分级通过在关键字符号前加tab键实现
```

#### 1、无序列表ul (unorder list)
```
<ul>
     <li>列表第一项</li>
     <li>列表第二项</li>
     <li>列表第三项</li>
     <li>列表第四项</li>
 </ul>
```
效果如下：
<ul>
     <li>列表第一项</li>
     <li>列表第二项</li>
     <li>列表第三项</li>
     <li>列表第四项</li>
 </ul>


#### 2、有序列表ol (order list)
```
<ol>
     <li>列表第一项</li>
     <li>列表第二项</li>
     <li>列表第三项</li>
     <li>列表第四项</li>
 </ol>
 ```
 效果如下：
 <ol>
     <li>列表第一项</li>
     <li>列表第二项</li>
     <li>列表第三项</li>
     <li>列表第四项</li>
 </ol>


### 十、换行
```
<br>
```
效果如下：

我是上一行<br>我是下一行


### 十一、添加空格
```
&nbsp;
```
