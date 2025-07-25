# <center><font face="仿宋" font color=black>Markdown</font></center>
## <center><font face="楷体" size=4>Lucky 2025.7.14</font></center>
---
### 一、准备工作
1. **安装vscode**
2. **下载必要的插件**
   - Markdown All in One
   - Markdown Preview Enhance
   - Markdown PDF
   - Paste Image
3. **创建.md文档，打开同步预览功能，开始编辑**
### 二、基本语法
1. **标题**
   #一级标题
   ##二级标题
   最多六级标题

2. **引用**
   使用>
   >可以插入引用内容
   >>可以嵌套引用
3. **列表**
   1. 无序列表（列表前面是点）
   - 列表1
   - 列表2
   - 列表3
   1. 有序列表（1,2,3->i,ii->a,b,c）
      1. 列表1
      2. 列表2
   2. 嵌套（见上）
   3. TodoList
      - [x] a
      - [ ] b
      - [ ] c
4. **表格**
   | 左对齐 | 居中对齐 | 右对齐 |
   | :----- | :---: | ----: |
   | a | b | c |
5. **段落**
   - 分割线：三个*
     ***
   - 字体
        | 字体 | 代码 |
        |:--: | :--: |
        |*斜体*|*  *|
        |==高亮==|== ==|
        |**粗体**|** **|
        |***斜粗体***|*** ***|
        |~~删除~~|~~ ~~|
        |<u>下划线</u>|```<u> </u>```|
    - 脚注
      参考文献[^1]
6. **代码**
   ```
   #include<stdio.h>
   int main()
   {
    printf("hello,world!");
    return 0;
   }
   ```
7. **超链接**
   - [B站教程]：https://b23.tv/OMfRLYI
   - 查看更多使用教程请[点击链接](https://www.runoob.com/markdown/md-link.html)
8. **图片**
将图片上传到图床（见下链接），然后复制图床的代码到md即可
   - [路过图床]：https://imgse.com/
   - 使用markdown语法插入
     [![pV1Vxk8.png](https://s21.ax1x.com/2025/07/14/pV1Vxk8.png)](https://imgse.com/i/pV1Vxk8)
   - 使用html语言实现调整图片大小和位置功能
     <a href="https://imgse.com/i/pV1Vxk8"><div align=center><img src="https://s21.ax1x.com/2025/07/14/pV1Vxk8.png" alt="pV1Vxk8.png" 
     border="0" width="80%" height="60%"/></div></a>
### 三、**LaTeX常见数学代码**
1. **公式基本结构**
   - **行内公式**
     $E=mc^2$
   - **行间公式（无编号）**
     $$ \int_a^b f(x)dx $$
2. **常用符号与运算**
   - **上下标**
      $$
      x^{2}, a_{ij}, y'
      $$
   - **分数**
      $$
      \frac{a}{b}, \dfrac{1}{3}	 
      $$
   - **根号**
      $$\sqrt{x}, \sqrt[3]{x+y}$$
   - **关系符号**
      $$
      \ne, \ge, \approx, \propto
      $$
   - **运算符**
      $$
      ​	\times, \div, \cdot, \pm
      $$
   - **极限**
      $$
      \lim_{x \to 0}
      $$
   - **导数**
      $$
      f'(x)
      $$
3. **大型运算符**
   - **求和** 
    $$\sum_{i=1}^{n} i^2$$
   - **积分**
     $$\int_{0}^{\infty} e^{-x}dx$$
   - **乘积** 
    $$\prod_{k=1}^{n} k$$
   - **二重积分** 
    $$\iint_D f(x,y)dA$$
4. **矩阵与数组**
   - **基础矩阵**
         $$
         \begin{bmatrix} 
            1 & 2 \\ 
            3 & 4 
         \end{bmatrix}
         $$
   - **行列式**
         $$
         \begin{vmatrix} 
         a & b \\ 
         c & d 
         \end{vmatrix}
         $$
   - **分段函数**
         $$
         f(x) = \begin{cases} 
         x^2, & x \geq 0 \\
         -x, & x < 0 
         \end{cases}
         $$

### 四、其他操作
   
   - **html/css语法**
     - ctrl+shift+p 搜索
     "Markdown Preview Ehanced:Customize CSS"
     - 在style中使用css语法修改标题格式
   - **个性化设置**
     File-Preference-Settings
### 五、导出PDF文档
   - 不推荐使用Markdown PDF，会有乱码
   - 右击Preview markdown 界面，Open in Browser-手动在浏览器另存为PDF文档

[^1]:最后要写上注释

   