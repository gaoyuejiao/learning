# learning
the problem and new knowledge of learning
## Markdown
  Markdown 是一种轻量级的「标记语言」，它的优点很多，目前也被越来越多的写作爱好者，撰稿者广泛使用。看到这里请不要被「标记」、「语言」所迷惑，Markdown 的语法十分简单。常用的标记符号也不超过十个，这种相对于更为复杂的HTML 标记语言来说，Markdown 可谓是十分轻量的，学习成本也不需要太多，且一旦熟悉这种语法规则，会有一劳永逸的效果。
### 用途
  Markdown的语法简洁明了、学习容易，而且功能比纯文本更强，因此有很多人用它写博客。世界上最流行的博客平台WordPress和大型CMS如Joomla、Drupal都能很好的支持Markdown。完全采用Markdown编辑器的博客平台有Ghost和Typecho。
用于编写说明文档，并且以“README.MD”的文件名保存在软件的目录下面。
### 语法
#### 标题
标题是每篇文章都需要也是最常用的格式，在 Markdown 中，如果一段文字被定义为标题，只要在这段文字前加 # 号即可。
！[This is a title](E:\img\img.png)
#### 列表
##### 无序列表 *，-
* wo
* ni
- n
- m

##### 有序列表
1. q
2. w

#### 引用
>这里是引用

#### 链接
[百度](http://baidu.com)
#### 图片
！[]()

#### 粗体与斜体
**这里是粗体**
*这里是斜体*

#### 表格
| 序 号 | 姓 名 | 年 龄 |
| ----- | :---: | ----: |
|   1   | lili  |  16   |
|   2   | kaka  |  20   |

#### 代码
'public class s99{
public static void main(String[] args){
for (int i=1;i<=9;i++) {
	for (int j=1;j<=i;j++){
		System.out.print(i+"*"+j+"="+(i*j)+"\t");
}
	System.out.print("\n");
}
}
}
g:\android\code>java s99
1*1=1
2*1=2   2*2=4
3*1=3   3*2=6   3*3=9
4*1=4   4*2=8   4*3=12  4*4=16
5*1=5   5*2=10  5*3=15  5*4=20  5*5=25
6*1=6   6*2=12  6*3=18  6*4=24  6*5=30  6*6=36
7*1=7   7*2=14  7*3=21  7*4=28  7*5=35  7*6=42  7*7=49
8*1=8   8*2=16  8*3=24  8*4=32  8*5=40  8*6=48  8*7=56  8*8=64
9*1=9   9*2=18  9*3=27  9*4=36  9*5=45  9*6=54  9*7=63  9*8=72  9*9=81
正确，为什么
public class s99{
public static void main(String[] args){
for (int i=1;i<=9;i++) {
	for (int j=1;j==i;j++){
		System.out.print(i+"*"+j+"="+(i*j)+"\t");
}
	System.out.print("\n");
}
}
}'
#### 分割线
我是谁
***
哈哈

