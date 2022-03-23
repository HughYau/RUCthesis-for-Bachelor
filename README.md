# RUCthesis-for-Bachelor
中国人民大学本科生毕业论文（2021年修订版）latex模板
# RUC Thesis: 中国人民大学本科生毕业论文模板
Copyright 2022  Qiu Renxiang
2022/03/20 v1.2 beta

## 3.24日重大维护！！！
如果你一直采取windows系统本地编译，请忽略此次更新，否则：

如果你打算在知网论文系统提交论文，请注意，知网系统自带的阅览系统（可能与查重有关）对于汉字的识别不太完善，目前来看，Fandol字库下的宋体和黑体均无法解析。

CTex库下不同系统和编译器下的配置宏集策略如下图所示：
![image](https://github.com/HughYale/RUCthesis-for-Bachelor/blob/master/font.png)
如果你采用本地编译，windows和mac系统下的中易字库和华文字库均可以正常被知网系统解析。（但也有出现mac系统编译出Fandol字库的情况，请使用Adobe Acrobat等PDF阅读器对字体进行识别）

然而线上的Overleaf平台内部由于版权问题，仅内置了Fandol字库，其宋体黑体均无法被知网系统解析。

于是我将中易字库的字体加入了模板当中，使用者需要在overleaf平台上传字体库文件，并添加更改字体的代码（已更新main.tex）。

如果你有更好的解决方法，请联系我。

## 3.20日1.2更新
1. 新增原创性声明和使用授权说明页面
2. 新增作者签名
3. 修改了1.1中参考文献部分不符合指导手册的问题。

本文编写的依据是中国人民大学教务处2021年修订的《本科生毕业论文（设计）指导手册》（http://jiaowu.ruc.edu.cn/wjxz6/sjjx3/828d0d99e9bd4686b41b3526fe553b73.htm）以及本科毕业论文模板（http://jiaowu.ruc.edu.cn/wjxz6/sjjx3/d5aba7b8b1574080a34af94916c2464d.htm）
本文在2020年的1.0版本（2017年版论文指导手册）基础上进行修改完善：
1. 首页格式依据最新指导手册进行更新
2. 修改了上一版本部分字号以及字体使用不当的问题（针对多级标题和目录进行大量优化）
3. 在参考文献引用上采用了GB/T7714－2015标准，按照著者-出版年制排序，如需更改请参考手册：https://ctan.math.illinois.edu/macros/latex/contrib/biblatex-contrib/biblatex-gb7714-2015/biblatex-gb7714-2015.pdf
4. 脚注采用圆形脚注
5. 添加了附录页和致谢页
6. 官方本科毕业论文Word模板有较多地方与指导手册冲突，如遇与本模板不同，一切以指导手册为准



如果你有任何建议和疑问请发送邮件至qrx_math@ruc.edu.cn,协助我做的更好。
重要提示：
  1. 请确保使用 UTF-8 编码保存
  2. 请使用 XeLaTeX编译
  3. 修改、使用、发布本文档请务必遵循 LaTeX Project Public License
  4. 不需要的注释可以尽情删除
