# 上海海事大学(SHMTU) Beamer 模板主题

#### 介绍

一个供上海海事大学(SHMTU)同学使用的非官方的 LaTeX Beamer 主题模板。

An unofficial LaTeX beamer template for Shanghai Maritime University students.

[English Version README](README.en.md)

#### 仓库地址

**github 仓库地址**

[https://github.com/a645162/SHMTU-Beamer-Theme](https://github.com/a645162/SHMTU-Beamer-Theme)

**gitee 仓库地址**

[https://gitee.com/a645162/shmtu-beamer-theme](https://gitee.com/a645162/shmtu-beamer-theme)

**注:**

1. gitee 仓库地址只用于加速下载，版本可能较旧。
2. 最新改动请参考 [dev分支](https://github.com/a645162/SHMTU-Beamer-Theme/tree/dev)

#### 什么是 Beamer？

Beamer 是一个用于制作演示文稿(PPT)的 LaTeX 文档类。它提供了许多用于创建幻灯片的功能和样式。

Beamer 使得使用 LaTeX 来创建专业和美观的幻灯片变得非常方便。它提供了一些预定义的主题和颜色主题，但也允许用户根据自己的需求进行自定义。通过使用 Beamer，用户可以使用 LaTeX 的强大排版功能，如**数学公式**、图表、图像等，来便捷地创建高质量的演示文稿。

Beamer 的语法和使用方式与普通的 LaTeX 文档类类似。用户可以在 LaTeX 编辑器(TeXstudio)中编写 Beamer 文档，并使用 XeLaTeX 编译器来生成 PDF 格式的幻灯片。

##### 字太多不想看？总结一下！OK！安排！

简单来说，其实就是用 LaTeX 套模板，快速制作PPT，不一定多好看，反正不会很丑就是啦！

而且，这个风格？**学术风**！

众所周知，LaTeX输入公式非常滴方便！

#### 样本展示

请参考
[slide.pdf](slide.pdf)

#### LaTeX编译器

**XeLaTeX**

一定要使用 XeLaTeX ！！！否则卡你半天，最后报一堆错！

#### 安装教程

1. 安装 TeXLive/MacTeX
2. 安装 TeXstudio(支持Windows/macOS/Linux)
3. 克隆仓库/下载ZIP

注：最新版本的 TeXLive 2022/2023 经过测试是可以使用的！

我的 TeXLive 2023 已经将所有包更新至最新(2023年10月16日)，依旧可以使用！

然而 TeXLive 2021 可能会出现以下错误，貌似不影响编译但是并不推荐使用！

```
GPL Ghostscript 9.56.1: Unrecoverable error, exit code 1
```


#### 使用说明

1. 设置 TeXstudio 的默认编译器为 XeLaTeX
2. 修改 tex 文件内容(只有.tex文件允许修改文件名)
3. 编译 .tex 文件

注意：由于 .gitignore 将会生成文件忽略，因此一些文件不会被上传到仓库，
因此，首次编译，或者您修改Bib文件后可能需要较长的时间进行编译！

#### 其他说明书

以下说明书以及更多的说明书均位于 Instructions 目录下

**TeXstudio安装/配置教程**
请参考 [TeXstudio.md](Instructions/TeXstudio.md)

**魔改教程**
请参考 [ModifyInstructions.md](Instructions/ModifyInstructions.md)

#### 参与贡献

1. Fork 本仓库
2. 新建 Feat_xxx 分支
3. 提交代码
4. 新建 Pull Request

注:gitee 仓库地址只用于加速下载，版本可能较旧。

#### 工作计划

推荐一个仓库

[https://github.com/hellckt/SHMTUThesis](https://github.com/hellckt/SHMTUThesis)

这是我们学校一位校友制作的硕士毕业论文模板，但是经过我的测试 TeXLive 2023 是不可以正常编译的！TeXLive 2022 不支持某些数学输入，不过还是可以通过公式的形式输入，影响并不大，但是到了 TeXLive 2023，直接完全用不了！但是 TeXLive 2021 还是可以用滴，所以暂时凑活一下吧！我准备修改一下，也许就咕咕咕了，但是我准备修改一个课设可以用的模板！

#### 致谢

本项目基于 [lwDavid/ShanghaiTech-Beamer-Theme](https://github.com/lwDavid/ShanghaiTech-Beamer-Theme)
