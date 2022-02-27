## Beamer of  XMU WISERCLUB & WISE :octocat:

:point_right: Author: [RankFan](https://www.cnblogs.com/RankFan/) & Gauss

:dart: Run `Xelatex` **twice**

Fonts: https://mirrors.tuna.tsinghua.edu.cn/adobe-fonts/

ref:

1. https://www.latexstudio.net/index/details/index/mid/1166
2. https://github.com/IQSS/iqss-beamer-theme
3. https://www.latexstudio.net/index/details/index/mid/75
4. https://github.com/CamuseCao/XMU-thesis

Download: git clone https://github.com/RankXiaoLong/Beamer-of-XMU-WISERCLUB.git

If you do not like the logo or the color of the beamer , you can modify the codes of `XMUtheme.sty`

Acknowledge: Thanks for the Gauss, God of Wei, Doctor Zhang, etc.

## How to modify？
- 修改head大小
```latex
\defbeamertemplate*{headline}{xmu theme}{%
  \leavevmode%
  % 6.4375ex
  \@tempdimb=7ex # 修改具体高度
  
\begin{beamercolorbox}[wd=.76\paperwidth,ht=\@tempdimb,left]{outline in head/foot}%
\vbox to\@tempdimb{\scriptsize\vfil\insertsectionnavigationhorizontal{0\textwidth}{\hskip0pt 
plus1filll}{}\vfil} # \scriptsize 可以修改具体字的大小
``` 

## Questions :question:
If you have questions, you can email me or issue the problems here

## Lincense

本作品采用[知识共享署名-非商业性使用-相同方式共享 4.0 国际许可协议](https://creativecommons.org/licenses/by-nc-sa/4.0/)进行许可
