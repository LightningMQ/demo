# Markdown Notepad
### 参考连接:

Typora 官网：https://typora.io/

在线编辑器 https://c.runoob.com/front-end/712



### “=” 一级标题 和 “-” 二级标题

//我展示的是一级标题
//=================

//我展示的是二级标题
//-----------------



### “#” 一级二级标题

# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题

``` text
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题
```



### 段落
#### 需要换行时在最后添加两个以上的空格, 也可以使用一个空行表示



### 字体

*斜体文本*  `*斜体文本*`

_斜体文本_  `_斜体文本_`

**粗体文本** `**粗体文本**`

__粗体文本__ `__粗体文本__`

***粗斜体文本***  `***粗斜体文本***`
___粗斜体文本___ `___粗斜体文本___`



### 分隔线

***
`***`

* * *
`* * *`

*****
`*****`

- - -
`- - -`

----------
`----------`



### 删除线
~~https://www.azure.cn~~
`~~https://www.azure.cn~~`



### 下划线
##### 下划线可以通过 **HTML** 的 `<u>` 标签来实现:
<u>www.azure.cn</u> 

``` text
<u>www.azure.cn</u> 
```



### 备注

#### Azure 中国区 [^Azure Mooncake]
[^Azure Mooncake]: https://www.azure.cn
``` text
#### Azure 中国区 [^Azure Mooncake]
[^Azure Mooncake]: https://www.azure.cn
```



### 列表
#### Markdown 支持有序列表和无序列表。
#### 无序列表使用星号(`*`)、加号(`+`)或是减号(`-`)作为列表标记：
* 第一项 `* 第一项`
* 第二项 `* 第二项`
* 第三项 `* 第三项`

+ 第一项 `+ 第一项`
+ 第二项 `+ 第二项`
+ 第三项 `+ 第三项`

- 第一项 `- 第一项`
- 第二项 `- 第二项`
- 第三项 `- 第三项`

#### 有序列表使用数字并加上 `.`号来表示, 如:
1.  第一项 `1. 第一项`
2.  第二项 `2. 第二项`
3.  第三项 `3. 第三项`

#### 列表嵌套
列表嵌套只需在子列表中的选项添加四个空格即可:
1. 第一项：
    - 第一项嵌套的第一个元素
    - 第一项嵌套的第二个元素
2. 第二项：
    - 第二项嵌套的第一个元素
    - 第二项嵌套的第二个元素

``` text
1. 第一项：
    - 第一项嵌套的第一个元素
    - 第一项嵌套的第二个元素
2. 第二项：
    - 第二项嵌套的第一个元素
    - 第二项嵌套的第二个元素
```	


#### 区块
Markdown 区块引用是在段落开头使用 `>` 符号 ，然后后面紧跟一个 **空格** 符号：
> 区块引用
> 百度网盘
> 新浪微博

``` text
> 区块引用
> 百度网盘
> 新浪微博
```



#### 区块嵌套
一个 **`>`** 符号是最外层，两个 **`>`** **(>>)** 符号是第一层嵌套, 以此类推退:

`一个 **`>`** 符号是最外层，两个 **`>`** **(>>)** 符号是第一层嵌套, 以此类推退:`

> 最外层
> > 第一层嵌套
> >
> > > 第二层嵌套
``` text
> 最外层
> > 第一层嵌套
> > > 第二层嵌套
```



#### 区块中使用列表
区块中使用列表实例如下:
> 区块中使用列表
> 1. 第一项
> 2. 第二项
> + 第一项
> + 第二项
> + 第三项

``` text
> 区块中使用列表
> 1. 第一项
> 2. 第二项
> + 第一项
> + 第二项
> + 第三项
```



#### 列表中使用区块
如果要在列表项目内放进区块, 那么就需要在 `>` 前添加四个空格的缩进。

区块中使用列表实例如下:
* Tomcat安装
    > 1. 安装JDK
    > 2. 配置环境变量

* Tomcat安装方法
    > 1. 编译安装
    > 2. YUM安装

``` text
* Tomcat安装
    > 1. 安装JDK
    > 2. 配置环境变量

* Tomcat安装方法
    > 1. 编译安装
    > 2. YUM安装
```



### 代码
#### 代码区块
代码区块使用 **4 个空格** , **一个制表符(Tab 键)** 或使用“**```**  表示”。

实例如下：
``` bash
en
conf t
no ip domain loo
line con 0
exec-t 0 0
logging synchronous
exit
enable secret cisco
service password-encryption
alias exec e show crypto engine conn ac
alias exec r show ip route
line vty 0 4
password cisco
login
exit
ip domain name cisco.com
crypto key generate rsa label sshkey modulus 2048
username jack privilege 15 password cisco
ip ssh version 2
line vty 0 4
transport input ssh
login local
exit
```

### 链接
[Azure China](https://www.azure.cn)
[Azure Global](https://www.azure.com)

``` text
[Azure China](https://www.azure.cn)
[Azure Global](https://www.azure.com)
```

或者直接使用如下:
<https://www.azure.cn>
<https://www.azure.com>

### 图片
![Microsoft Azure](https://www.bespinglobal.cn/wp-content/uploads/2019/02/微软.png "Microsoft Azure")
![QQ Cloud](https://www.bespinglobal.cn/wp-content/uploads/2019/02/腾讯云.png "Tencent Cloud")
![SB Ali](https://www.bespinglobal.cn/wp-content/uploads/2019/02/阿里云140x60.png "Ali Cloud SB")
![HuaWei Cloud](https://www.bespinglobal.cn/wp-content/uploads/2019/02/华为云.png "HuaWei Cloud")
![AWS](https://www.bespinglobal.cn/wp-content/uploads/2019/02/aws-2.png "AWS")    

``` text 
### 图片
![Microsoft Azure](https://www.bespinglobal.cn/wp-content/uploads/2019/02/微软.png "Microsoft Azure")
![QQ Cloud](https://www.bespinglobal.cn/wp-content/uploads/2019/02/腾讯云.png "Tencent Cloud")
![SB Ali](https://www.bespinglobal.cn/wp-content/uploads/2019/02/阿里云140x60.png "Ali Cloud SB")
![HuaWei Cloud](https://www.bespinglobal.cn/wp-content/uploads/2019/02/华为云.png "HuaWei Cloud")
![AWS](https://www.bespinglobal.cn/wp-content/uploads/2019/02/aws-2.png)
```

#### 连接图片

这个链接用 1 作为网址变量 [BESPIN GLOBAL][1].
然后在文档的结尾位变量赋值（网址）

[1]: https://www.bespinglobal.cn/wp-content/uploads/2017/02/logo.png

### 表格
Markdown 制作表格使用 `|` 来分隔不同的单元格，使用 `-` 来分隔表头和其他行。

语法格式如下：
| 表头   | 表头   |
| ------ | ------ |
| 单元格 | 单元格 |
| 单元格 | 单元格 |

``` text
|  表头   | 表头  |
|  ----  | ----  |
| 单元格  | 单元格 |
| 单元格  | 单元格 |
```  

##### 对齐方式

**我们可以设置表格的对齐方式:**

- -: 设置内容和标题栏居右对齐。
- :- 设置内容和标题栏居左对齐。
- :-: 设置内容和标题栏居中对齐。

实例如下：
| 左对齐 | 右对齐 | 居中对齐 |
| :----- | -----: | :------: |
| 单元格 | 单元格 |  单元格  |
| 单元格 | 单元格 |  单元格  |



``` text
##### 对齐方式

**我们可以设置表格的对齐方式:**

- -: 设置内容和标题栏居右对齐。
- :- 设置内容和标题栏居左对齐。
- :-: 设置内容和标题栏居中对齐。

实例如下：
| 左对齐 | 右对齐 | 居中对齐 |
| :-----| ----: | :----: |
| 单元格 | 单元格 | 单元格 |
| 单元格 | 单元格 | 单元格 |
```

#### Others
**支持的 HTML 元素**
不在 Markdown 涵盖范围之内的标签, 都可以直接在文档里面用 HTML 撰写。

目前支持的 HTML 元素有: `<kbd> <b> <i> <em> <sup> <sub> <br>` 等 , 如：
`使用 <kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>Del</kbd> 重启电脑`

使用 <kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>Del</kbd> 重启电脑

##### 转义
Markdown 使用了很多特殊符号来表示特定的意义, 如果需要显示特定的符号则需要使用转义字符, Markdown 使用反斜杠转义特殊字符:
**文本加粗** 
\*\* 正常显示星号 \*\*

``` text
**文本加粗** 
\*\* 正常显示星号 \*\*


##### Markdown 支持以下这些符号前面加上反斜杠来帮助插入普通的符号:
``` text
\   反斜线
`   反引号
*   星号
_   下划线
{}  花括号
[]  方括号
()  小括号
#   井字号
+   加号
-   减号
.   英文句点
!   感叹号
```

#### 公式
当你需要在编辑器中插入数学公式时, 可以使用两个美元符 $$ 包裹 TeX 或 LaTeX 格式的数学公式来实现。提交后, 问答和文章页会根据需要加载 Mathjax 对数学公式进行渲染。如:

$$
\mathbf{V}_1 \times \mathbf{V}_2 =  \begin{vmatrix} 
\mathbf{i} & \mathbf{j} & \mathbf{k} \\
\frac{\partial X}{\partial u} &  \frac{\partial Y}{\partial u} & 0 \\
\frac{\partial X}{\partial v} &  \frac{\partial Y}{\partial v} & 0 \\
\end{vmatrix}
$$tep1}{\style{visibility:hidden}{(x+1)(x+1)}}
$$

``` text
$$
\mathbf{V}_1 \times \mathbf{V}_2 =  \begin{vmatrix} 
\mathbf{i} & \mathbf{j} & \mathbf{k} \\
\frac{\partial X}{\partial u} &  \frac{\partial Y}{\partial u} & 0 \\
\frac{\partial X}{\partial v} &  \frac{\partial Y}{\partial v} & 0 \\
\end{vmatrix}
$$tep1}{\style{visibility:hidden}{(x+1)(x+1)}}
$$
```

