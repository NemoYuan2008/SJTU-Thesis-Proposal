# SJTU Thesis Proposal 上海交大开题报告模板

本仓库含有上海交通大学**开题报告**以及**博士生年度进展报告** LaTeX 模板，基于上海交通大学研究生院官网给出的 [word 模板](https://www.gs.sjtu.edu.cn/xzzx/pygl) 制作。

本模板**仅支持 XeTeX 引擎和 UTF-8 编码，请使用 XeLaTeX 编译！！！**

如果你觉得本仓库有用，请点个 star 小星星 :star::star::star: 支持一下 :star_struck:

## 模板内容

本仓库中含有**开题报告**以及**博士生年度进展报告**模板：

- 若需要**开题报告**模板，请使用 `main.tex` 文件；
- 若需要**博士生年度进展报告**模板，请使用 `main_phd_mid_report` 文件。

## 免责声明

本模板仅为开题报告模板的参考实现，不保证审查老师不提意见。任何由于使用本模板而引起的论文格式审查问题均与本模板作者无关。

**更新**：本模板作者已使用该模板顺利通过开题答辩，请放心食用~

## 获取方法

点击上方绿色 Code，选择 Download ZIP 下载源码到本地。或者使用 git 克隆本仓库。

Overleaf 用户可直接点击链接使用: [Overleaf 模板链接](https://www.overleaf.com/latex/templates/sjtu-thesis-proposal/wpxfhqvwdbwc)，需注意 Overleaf 上模板的更新速度可能会滞后于在 GitHub 上更新的速度。

## 使用方法

**请仔细阅读对应 `.tex` 文件中的注释，按照注释的提示进行文档的编写。**

## 编译方法

这里以 Overleaf 和 VSCode 为例说明。注意如果在本地使用需安装最新版 TeXLive 套装。使用其他编辑器的用户可参考相应编辑器的使用说明，只需注意将编译器设置为 XeLaTeX 即可。

### Overleaf 用户

从 GitHub 下载下来的压缩包上传至 Overleaf 平台，**注意将编译器设置为 XeLaTeX**。
设置编译器的方法请参见 [Overleaf 官方文档](https://www.overleaf.com/learn/how-to/Changing_compiler)。

### 本地 VSCode 用户

安装 LaTeX Workshop 插件，使用 VSCode 打开文件夹，打开 `main.tex`，在边栏中展开 `Build LaTeX project`，选择 `Recipe: latexmk (xelatex)` 进行编译。
在 VSCode 设置中搜索 `latex-workshop.latex.recipe.default` 并将其改为 `lastUsed` 以便一直使用该选项编译。
注意，**使用其他选项会导致报错**。

### 从命令行编译

使用 `latexmk -xelatex main` 命令来编译开题报告模板。

使用 `latexmk -xelatex main_phd_mid_report` 命令来编译博士生年度进展报告模板。

## 贡献

本模板可能存在一些问题，同时学校提供的官方 word 模板可能随时会更新。如果你发现了模板的问题，欢迎给我发 PR 或者提 issue。

## 许可证

上海交通大学校徽校名图片的版权 (`figures/sjtu-logo.png`) 归上海交通大学所有, 该图片下载自[上海交通大学视觉形象识别系统](https://vi.sjtu.edu.cn)。

其余部分使用 MIT 许可证授权。

## 致谢

感谢 @AlexaraWu 和 @LogCreative 对于表格设计的帮助！
