# SJTU Thesis Proposal 上海交大开题报告模板

本仓库是上海交通大学开题报告 LaTeX（非官方）模板，基于上海交通大学研究生院官网给出的 [word 模板](https://www.gs.sjtu.edu.cn/xzzx/pygl) 制作。

本模板**仅支持 XeTeX 引擎**。

## 使用方法
这里以 Overleaf 和 VSCode 为例说明使用方法。注意如果在本地使用需安装最新版 TeXLive 套装。使用其他编辑器的用户可参考相应编辑器的使用说明，只需注意将编译器设置为 XeLaTeX 即可。

### Overleaf 用户
将下载下来的压缩包上传至 Overleaf 平台，并将编译器设置为 XeLaTeX，设置编译器的方法请参见 [Overleaf 文档](https://www.overleaf.com/learn/how-to/Changing_compiler)。

### 本地 VSCode 用户
安装 LaTeX Workshop 插件，使用 VSCode 打开文件夹，选择 `Recipe: latexmk (xelatex)` 进行编译。
在 VSCode 设置中搜索 `latex-workshop.latex.recipe.default` 并将其改为 `lastUsed` 以便一直使用该选项编译。
注意，使用其他选项会导致报错。

### 从命令行编译
使用 `latexmk -xelatex main` 命令来进行编译，可以加入 `-synctex=1` 命令行选项来方便编辑器定位。

如果你熟悉 LaTeX 编译流程的也可手动进行编译 `xelatex main && biber main && xelatex main  && xelatex main`。


## 许可证
上海交通大学校徽校名图片的版权 (`figures/sjtu-logo.png`) 归上海交通大学所有, 该图片下载自[上海交通大学视觉形象识别系统](https://vi.sjtu.edu.cn)。

其余部分使用 MIT 许可证授权。
