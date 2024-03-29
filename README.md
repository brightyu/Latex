# Latex 结构化 

一篇文章通常很长。那么就需要把它分成多个子文件。
每个文件都是以.tex为后缀，用命令\input 或者\include 把它们添加进主文件中。
```
\input{introduction}
\input{model1}
\input{model2}
\input{model3}
\input 在插入子文件的时候不换页
\include在插入子文件的时候强制换页
```

# 引用参考文献
```
\bibliographystyle{plain}
\bibliography{bib/tex}
```
把参考文献写入一个以.bib为后缀名的文件中，例如bib/tex.bib，然后用上面的两条语句就可以了。

获取这样的内容有一个小技巧：
在谷歌学术中输入你要引用的论文名字，然后点开“引用”那个链接，再点击"导入BibTeX",引用的格式就出来了。

\@article{KDE,article={}... 在这个命令中，KDE是这篇引用文章的索引号，是你自己定义的。
在你的正文中要引用他的话，就用 `\cite{KDE}`。 
同时引用两篇：`\cite{KDE,Another}`注意逗号前后都不要有空格，不然会报错。

# 有用的知识

 - [latex-example](https://github.com/MartinThoma/LaTeX-examples)
  
 - [Latex引用参考文献-BibTex的使用](https://blog.csdn.net/caiandyong/article/details/70258670)
  
  
 - [LaTeX 科技排版 ](http://math.ecnu.edu.cn/~latex/)
  
  
 - [Using the LaTeX Resume Templates](http://rpi.edu/dept/arc/training/latex/resumes/)
  
  
 - [LaTeX Templates](http://www.latextemplates.com/template/awesome-resume-cv)
  
  
 - [LaTeX/数学公式](https://zh.wikibooks.org/zh-cn/LaTeX/%E6%95%B0%E5%AD%A6%E5%85%AC%E5%BC%8F)
  
  
 - [Latex基本表格绘制](https://blog.csdn.net/JueChenYi/article/details/77116011)



