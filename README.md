# 中科大课程统计学习（刘东）

本repo提供了INFO6407P课程的复习提纲和半开卷cheatsheet。开发环境为vscode和XeLaTeX。`cheatsheet.tex`是小抄主体，`outline.tex`是小抄的正常版式文本，供正常查阅，`sl.tex`是两个文件所引用的真实内容，修改小抄的内容在这个文件进行。

Fork自[HowardZorn](https://github.com/HowardZorn/StatisticalLearningCheatsheet)，修正了一些错误，新增了部分图、公式和习题。欢迎在此基础上继续修改。

## 不用vscode开发

请用
```
latexmk -xelatex -8bit -shell-escape cheatsheet
latexmk -xelatex -8bit -shell-escape outline
```
生成文档


