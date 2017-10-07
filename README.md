# 标题
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题
<pre>
# 标题
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题
</pre>
# 列表
## 无序列表
* 1
* 2
* 3
<pre>
* 1
* 2
* 3
</pre>
# 锚点地址
## 空心原点
* 实心1
* 实心2
* 实心3
    * 空心1
    * 空心2
    * 空心3
```
* 实心1
* 实心2
* 实心3
    * 空心1
    * 空心2
    * 空心3
```
## 实心方块
* 实心1
* 实心2
* 实心3
    * 空心1
    * 空心2
    * 空心3
        * 实心方块1
        * 实心方块2
        * 实心方块3

```
* 实心1
* 实心2
* 实心3
    * 空心1
    * 空心2
    * 空心3
        * 实心方块1
        * 实心方块2
        * 实心方块3
```
## 有序列表
1. 1
2. 2
3. 3
<pre>
1. 1
2. 2
3. 3
</pre>
# 引用
> 这里是引用
<pre>
> 这里是引用
</pre>
# 锚点
[锚点文本](#锚点地址)
```
[锚点文本](#锚点地址)
...
# 锚点地址
```
# 图片
![小狗狗](https://avatars2.githubusercontent.com/u/26648209?v=4&s=400&u=4108ba0a850f9f390a449b40629651a8e31d05cd '我喜欢的狗狗')
```
![小狗狗](https://avatars2.githubusercontent.com/u/26648209?v=4&s=400&u=4108ba0a850f9f390a449b40629651a8e31d05cd '我喜欢的狗狗')
![alt](URL title)
```
# 插入链接
[baidu](https://www.baidu.com "我是百度")
```
[baidu](https://www.baidu.com "我是百度")
```
# 本仓库的链接
[我的简介](/example/profile.md)

# 图片链接
[![csdn-logo]][csdn-link]  
[![csdn-logo]][csdn-link2]
```
[![csdn-logo]][csdn-link]  
[![csdn-logo]][csdn-link2]
[csdn-logo]:/image/couple.jpeg "我的CSDN博客logo-title"
[csdn-link]:http://blog.csdn.net/guodongxiaren "我的博客link-title"
[csdn-link2]:/example/profile.md "我的简介link-title"
```
# 粗体
**粗体**
<pre>**粗体**</pre>
# 斜体
*斜体* 
<pre>*斜体* </pre>
# 删除线
~~删除线~~
```
~~删除线~~
```
# 表格
| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |
<pre>
| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |
</pre>
# 代码高亮
## index.html[html]
三个\`\`\`后边跟上中括号后边的内容
```html
<html>
    <head>
        <script src="main.js"></script>
    </head>
    <body>
    </body>
</html>
```
## main.js[javascript]
```javascript
var a = require('./a');
var b = require('./b');

a.doSth();
b.doSth();//javascript
```
## css[css]
```css
body{
	background:teal;
}
```
## Java[Java]
```Java
public static void main(String[]args){} //Java
```
## c[c]
```c
int main(int argc, char *argv[]) //C
```
## Bash[Bash]
```Bash
echo "hello GitHub" #Bash
```
## cpp[cpp]
```cpp
string &operator+(const string& A,const string& B) //cpp
```
# 粗分界线
****
这里分界线中间的内容
****
```
****
这里分界线中间的内容
****
```
# 换行
直接回车不能换行，  
可以在上一行文本后面补两个空格，  
这样下一行的文本就换行了。
```
直接回车不能换行，  
可以在上一行文本后面补两个空格，  
这样下一行的文本就换行了。
```
# 复选框列表
[x] 选中
[x] 选中
[ ] 未选中
[ ] 未选中
# 图标
:closed_book:




















-----------------
[csdn-logo]:/image/couple.jpeg "我的CSDN博客logo-title"
[csdn-link]:http://blog.csdn.net/guodongxiaren "我的博客link-title"
[csdn-link2]:/example/profile.md "我的简介link-title"


