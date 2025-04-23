# 这是一个存档：
用于收录毕设latex模板，欢迎社区贡献
## 山东科技大学本科毕业设计latex模板

2024年画的latex模板...

这个仓库是使用xetex和biber构建模板，参考当前目录下的`template.pdf`（学校教务发的word模板）作为模板绘制。

参考文献应写在`references.bib`中。

## 使用方法：

准备cover.pdf和my.jpg和teacher.png作为签名和封面。签名图片最好和模板中的my.jpg、teacher.png尺寸相同否则会引发排版变化。

首先通过编辑main.tex、references.bib等数学论文，然后通过

```bash
bibtex main.tex
biber main
bibtex mian.tex
bibtex main.tex
```

完成编译，结果应在`main.pdf`。

在模板中保留了部分tikz和公式示例，相关包和插件可酌情增减。

部分字体可能需要安装。

texmaker很好用
