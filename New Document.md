# 一级标题

## 二级标题

### 三级标题

#### 四级标题

##### 五级标题

###### 六级标题

####### 六级标题

总共六级标题，建议在井号后加一个空格，这是最标准的 Markdown 语法。

#### 无序列表
* 1
* 2
* 3
* 
- 1
- 2
- 3

#### 有序列表
1. 1
2. 2
3. 3  

在文字前加上 - 或 * 即可变为无序列表；  
在文字前加1. 2. 3. 即可变为有序列表。  
符号要和文字之间加上一个字符的空格。

在句末敲入2个空格即可换行。  
在句末敲入2个空格即可换行。  

> 这里是引用

如果你需要引用一小段别处的句子，那么就要用引用的格式。  
只需在文本前加入 > 尖括号（即大于号）

#### 插入链接
[Baidu](http://baidu.com)  

#### 插入图片
![Mou icon](http://mouapp.com/Mou_128.png)  

插入链接与插入图片的语法区别在于一个 ! 号  
链接为：[]()  
图片为：![]()  
其中，插入图片需要在()中输入图片的URL地址

**这里是粗体** *这里是斜体*  

用两个 * 包含一段文本就是粗体的语法，  
用一个 * 包含一段文本就是斜体的语法。

Name | Academy | score 
 - | :-: | -: 
Harry Potter | Gryffindor | 90 
Hermione Granger | Gryffindor | 100 
Draco Malfoy | Slytherin | 90

语法说明：  
1. 第一行为表头，第二行分隔表头和主体部分，第三行开始每一行代表一个表格行；  
2. 列与列之间用管道符号 “|” 隔开，原生方式的表格每一行的两边也要有管道符；  
3. 可在第二行指定不同列单元格内容的对齐方式，默认为左对齐，在 “-” 右边加上 “:” 为右对齐，在 “-” 两侧同时加上 “:” 为居中对齐。

`
// HelloDate.java  
import java.util.*;
public classvoid Hello  
{
	public static void main(String[] args)
	{
		System.out.println("Hello!");
	}
}
`  
用两个 ` 把中间的代码包裹起来

<pre>
// HelloDate.java  
import java.util.*;
public classvoid Hello  
{
	public static void main(String[] args)
	{
		System.out.println("Hello!");
	}
}
</pre>
直接使用HTML的pre标签来插入代码块，里面的换行不会被转义

***
分割线的语法只需要三个 * 号

* [x] 这是复选框
- [x] 这是复选框 
