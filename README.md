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
![redhat](data:image/svg+xml;base64,PHN2ZyBpZD0iTGF5ZXJfMSIgZGF0YS1uYW1lPSJMYXllciAxIiB4bWxucz0iaHR0cDovL3d3dy53%0D%0AMy5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCA2MTMgMTQ1Ij48ZGVmcz48c3R5bGU+LmNscy0x%0D%0Ae2ZpbGw6I2UwMDt9PC9zdHlsZT48L2RlZnM+PHRpdGxlPlJlZEhhdC1Mb2dvLUEtQ29sb3I8L3Rp%0D%0AdGxlPjxwYXRoIGNsYXNzPSJjbHMtMSIgZD0iTTEyNy40Nyw4My40OWMxMi41MSwwLDMwLjYxLTIu%0D%0ANTgsMzAuNjEtMTcuNDZhMTQsMTQsMCwwLDAtLjMxLTMuNDJsLTcuNDUtMzIuMzZjLTEuNzItNy4x%0D%0AMi0zLjIzLTEwLjM1LTE1LjczLTE2LjZDMTI0Ljg5LDguNjksMTAzLjc2LjUsOTcuNTEuNSw5MS42%0D%0AOS41LDkwLDgsODMuMDYsOGMtNi42OCwwLTExLjY0LTUuNi0xNy44OS01LjYtNiwwLTkuOTEsNC4w%0D%0AOS0xMi45MywxMi41LDAsMC04LjQxLDIzLjcyLTkuNDksMjcuMTZBNi40Myw2LjQzLDAsMCwwLDQy%0D%0ALjUzLDQ0YzAsOS4yMiwzNi4zLDM5LjQ1LDg0Ljk0LDM5LjQ1TTE2MCw3Mi4wN2MxLjczLDguMTks%0D%0AMS43Myw5LjA1LDEuNzMsMTAuMTMsMCwxNC0xNS43NCwyMS43Ny0zNi40MywyMS43N0M3OC41NCwx%0D%0AMDQsMzcuNTgsNzYuNiwzNy41OCw1OC40OWExOC40NSwxOC40NSwwLDAsMSwxLjUxLTcuMzNDMjIu%0D%0AMjcsNTIsLjUsNTUsLjUsNzQuMjJjMCwzMS40OCw3NC41OSw3MC4yOCwxMzMuNjUsNzAuMjgsNDUu%0D%0AMjgsMCw1Ni43LTIwLjQ4LDU2LjctMzYuNjUsMC0xMi43Mi0xMS0yNy4xNi0zMC44My0zNS43OCIv%0D%0APjxwYXRoIGQ9Ik0xNjAsNzIuMDdjMS43Myw4LjE5LDEuNzMsOS4wNSwxLjczLDEwLjEzLDAsMTQt%0D%0AMTUuNzQsMjEuNzctMzYuNDMsMjEuNzdDNzguNTQsMTA0LDM3LjU4LDc2LjYsMzcuNTgsNTguNDlh%0D%0AMTguNDUsMTguNDUsMCwwLDEsMS41MS03LjMzbDMuNjYtOS4wNkE2LjQzLDYuNDMsMCwwLDAsNDIu%0D%0ANTMsNDRjMCw5LjIyLDM2LjMsMzkuNDUsODQuOTQsMzkuNDUsMTIuNTEsMCwzMC42MS0yLjU4LDMw%0D%0ALjYxLTE3LjQ2YTE0LDE0LDAsMCwwLS4zMS0zLjQyWiIvPjxwYXRoIGQ9Ik01NzkuNzQsOTIuOGMw%0D%0ALDExLjg5LDcuMTUsMTcuNjcsMjAuMTksMTcuNjdhNTIuMTEsNTIuMTEsMCwwLDAsMTEuODktMS42%0D%0AOFY5NWEyNC44NCwyNC44NCwwLDAsMS03LjY4LDEuMTZjLTUuMzcsMC03LjM2LTEuNjgtNy4zNi02%0D%0ALjczVjY4LjNoMTUuNTZWNTQuMUg1OTYuNzh2LTE4bC0xNywzLjY4VjU0LjFINTY4LjQ5VjY4LjNo%0D%0AMTEuMjVabS01MywuMzJjMC0zLjY4LDMuNjktNS40Nyw5LjI2LTUuNDdhNDMuMTIsNDMuMTIsMCww%0D%0ALDEsMTAuMSwxLjI2djcuMTVhMjEuNTEsMjEuNTEsMCwwLDEtMTAuNjMsMi42M2MtNS40NiwwLTgu%0D%0ANzMtMi4xLTguNzMtNS41N201LjIsMTcuNTZjNiwwLDEwLjg0LTEuMjYsMTUuMzYtNC4zMXYzLjM3%0D%0AaDE2LjgyVjc0LjA4YzAtMTMuNTYtOS4xNC0yMS0yNC4zOS0yMS04LjUyLDAtMTYuOTQsMi0yNiw2%0D%0ALjFsNi4xLDEyLjUyYzYuNTItMi43NCwxMi00LjQyLDE2LjgzLTQuNDIsNywwLDEwLjYyLDIuNzMs%0D%0AMTAuNjIsOC4zMXYyLjczYTQ5LjUzLDQ5LjUzLDAsMCwwLTEyLjYyLTEuNThjLTE0LjMxLDAtMjIu%0D%0AOTMsNi0yMi45MywxNi43MywwLDkuNzgsNy43OCwxNy4yNCwyMC4xOSwxNy4yNG0tOTIuNDQtLjk0%0D%0AaDE4LjA5VjgwLjkyaDMwLjI5djI4LjgySDUwNlYzNi4xMkg0ODcuOTNWNjQuNDFINDU3LjY0VjM2%0D%0ALjEySDQzOS41NVpNMzcwLjYyLDgxLjg3YzAtOCw2LjMxLTE0LjEsMTQuNjItMTQuMUExNy4yMiwx%0D%0ANy4yMiwwLDAsMSwzOTcsNzIuMDlWOTEuNTRBMTYuMzYsMTYuMzYsMCwwLDEsMzg1LjI0LDk2Yy04%0D%0ALjIsMC0xNC42Mi02LjEtMTQuNjItMTQuMDltMjYuNjEsMjcuODdoMTYuODNWMzIuNDRsLTE3LDMu%0D%0ANjhWNTcuMDVhMjguMywyOC4zLDAsMCwwLTE0LjItMy42OGMtMTYuMTksMC0yOC45MiwxMi41MS0y%0D%0AOC45MiwyOC41YTI4LjI1LDI4LjI1LDAsMCwwLDI4LjQsMjguNiwyNS4xMiwyNS4xMiwwLDAsMCwx%0D%0ANC45My00LjgzWk0zMjAsNjdjNS4zNiwwLDkuODgsMy40NywxMS42Nyw4LjgzSDMwOC40N0MzMTAu%0D%0AMTUsNzAuMywzMTQuMzYsNjcsMzIwLDY3TTI5MS4zMyw4MmMwLDE2LjIsMTMuMjUsMjguODIsMzAu%0D%0AMjgsMjguODIsOS4zNiwwLDE2LjItMi41MywyMy4yNS04LjQybC0xMS4yNi0xMGMtMi42MywyLjc0%0D%0ALTYuNTIsNC4yMS0xMS4xNCw0LjIxYTE0LjM5LDE0LjM5LDAsMCwxLTEzLjY4LTguODNoMzkuNjVW%0D%0AODMuNTVjMC0xNy42Ny0xMS44OC0zMC4zOS0yOC4wOC0zMC4zOWEyOC41NywyOC41NywwLDAsMC0y%0D%0AOSwyOC44MU0yNjIsNTEuNThjNiwwLDkuMzYsMy43OCw5LjM2LDguMzFTMjY4LDY4LjIsMjYyLDY4%0D%0ALjJIMjQ0LjExVjUxLjU4Wm0tMzYsNTguMTZoMTguMDlWODIuOTJoMTMuNzdsMTMuODksMjYuODJI%0D%0AMjkybC0xNi4yLTI5LjQ1YTIyLjI3LDIyLjI3LDAsMCwwLDEzLjg4LTIwLjcyYzAtMTMuMjUtMTAu%0D%0ANDEtMjMuNDUtMjYtMjMuNDVIMjI2WiIvPjwvc3ZnPg== "local")  

``` text 
### 图片
![Microsoft Azure](https://www.bespinglobal.cn/wp-content/uploads/2019/02/微软.png "Microsoft Azure")
![QQ Cloud](https://www.bespinglobal.cn/wp-content/uploads/2019/02/腾讯云.png "Tencent Cloud")
![SB Ali](https://www.bespinglobal.cn/wp-content/uploads/2019/02/阿里云140x60.png "Ali Cloud SB")
![HuaWei Cloud](https://www.bespinglobal.cn/wp-content/uploads/2019/02/华为云.png "HuaWei Cloud")
![AWS](https://www.bespinglobal.cn/wp-content/uploads/2019/02/aws-2.png)
![redhat](https://raw.githubusercontent.com/LightningMQ/demo/master/RHLogo.svg "local")  
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

