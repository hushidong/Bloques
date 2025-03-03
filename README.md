update 2025-03-03 to v1.1

bloques.sty

A package based on tikz for control diagrams in power electronics.

    
updated 2025-03-03 to v1.1 by hu zhenzhen

    * add a mixer bMultiplyDown

updated 2021-12-28 by hu zhenzhen (hzzmail@163.com)
       
    * add more commands for feed and branch drawing
    * add more config api for linestyle,arrow style, xdis,ydis
    * add more instructions of cmds in the doc
       
version 1.0
       
author:  Alejandro Garces(alejandrogarces@gmail.com)
  


 
 package address：https://www.ctan.org/pkg/bloques
 
 issue address: https://github.com/hushidong/Bloques
  
 License: LPPL
 This work may be distributed and/or modified under the  conditions of the LaTeX Project Public License, either version 1.3
 of this license or (at your option) any later version.  The latest version of this license is in http://www.latex-project.org/lppl.txt
 and version 1.3 or later is part of all distributions of LaTeX version 2005/12/01 or later.


=================================================

一个绘制控制系统图的tikz包

是一个绘制系统图非常方便的包。

考虑到该包没有长期维护且github上没有，所以放在这进行维护。在原版基础上做了少许修改，进一步完善前馈、反馈绘制和接口设置。


示例一：一个线性时不变系统的状态变量图

![图片](https://user-images.githubusercontent.com/20421795/147715005-5fbe83f3-2c6f-4c5d-a521-8bd65f1acf66.png)


示例二：一个线性时不变系统的状态观测器

![图片](https://user-images.githubusercontent.com/20421795/147715028-7d7848f9-1824-4e51-84f3-42fb7dad3bf9.png)


示例三：一个多干扰源系统

![图片](https://user-images.githubusercontent.com/20421795/147715044-f6c0a733-0e83-45e6-85df-d4dededb6159.png)








