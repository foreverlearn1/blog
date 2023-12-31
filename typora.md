[TOC]

# typora使用方法

## 一、标题

> 语法： #（一级标题） ##（二级标题）……

## 二、段落

### 1、换行

> 语法： shift + enter （会获得一个段落）==小换行==

> 效果：
>
> 这是第一行
> 这是shift + enter 

### 2、分割线

> 语法：--- 或者 *** +enter

## 三、文字显示

### 1、字体

> 语法：在最上面==格式==选项也可以使用
>
> ```text
> **这是粗体**
> *这是斜体*
> ~~这是错误线~~
> <u>这是下划线</u>
> ==这是高亮==
> ```
>
> 上述字体可以组合使用：
>
> ```text
> ***粗体 + 斜体***
> ==**粗体 + 高亮**==
> ```

### 2、上下标

> 语法：
>
> ```text
> x^2^
> H~2~O
> ```

> 效果：
>
> x^2^
>
> H~2~O

### 3、练习题

#### 习题1

> 输出1 \* 2 \* 3 \* 4 \* 5
>
> 输出 \\*

> 关键是 “ \ ” 转义字符的使用

#### 习题2

> 输出$x_1^2$

> 如果使用上下标输出，则为x^2^ ~1~ 或者x~1~^2^ (这就是上下标的局限性，故需要使用==数字公式输入==）

## 四、列表

### 1、无序列表

> 语法： */-/+ +空格   
>
> **列表会以enter键的方式继承上一行的列表，也可以使用enter + tab进行列表缩进**
>
> **可以使用ctrl + [ 或者 ]  来进行缩进和反缩进**

### 2、有序列表

> 语法： 数字 + . + 空格

### 3、任务列表

> 语法：在无序列表的基础上  + [ + 空格 + ]
>
> * [x] 

## 五、区块显示

> 语法：
>
> ```text
> > + enter
> ```

## 六、代码显示

### 1、行内代码

> 语法：`代码内容`

### 2、代码块

> 语法：``` + 代码类型

## 七、连接

**语法**

1. 直接写网站连接

   > www.baidu.com (要按住==ctrl==点击才会跳转)

2.  [别名] + (网站连接)    **\[]()之间不能有==空格==**

      > [百度一下](https://www.baidu.com)

3. [别名] + (网站连接 “鼠标悬停的显示内容”） **\[]()之间不能有==空格==，网站链接与\"之间要有==空格==**

   > [百度一下](www.baidu.com "www.baidu.com")

4. **可以用上述方法在本markdown内进行跳转到标题**

   > 语法：[别名] + (##标题名)  **##与标题名之间没有==空格==**

## 八、脚注

> 语法:
>
>  `[^脚注名]`     **然后再用同样语法 + ：去写解释，按住==ctrl==点击脚注可跳转到脚注解释**

> 效果：
>
> 脚注1[^1]
>
> [^1]:  脚注1的意思

> 习题：把注脚解释变为两行
>
> 脚注2[^2]
>
> [^2]: 脚注2的意思<br/>第二行
>
> **实际上两行是一行，可以在*文件*->*偏好设置*->*markdown* 中设置“显示\<br/>”**

## 九、图片插入

> 语法：！ + 连接的语法

## 十、表格

> 语法： 推荐直接使用快捷键ctrl + T
>
> 1. 在表格中插入多行：使用 shift + enter 或者 手动输入\<br>

## 十一、表情

> 语法：使用快捷键win + 。呼出表情菜单然后进行选择

## 注：

1. 在两个代码块之间插入一句话，需要使用源代码模式连续在对应位置加上两个enter，及可以获得新的一行用来编辑
2. 可以在最开头使用[TOC]来加入目录链接

