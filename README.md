# 上海交大 开题报告/中期报告 LaTeX 模板

本仓库含有上海交大**研究生开题报告**、**硕士生中期报告**、**博士生年度进展报告** LaTeX 模板，基于上海交通大学研究生院官网给出的 [word 模板](https://www.gs.sjtu.edu.cn/xzzx/pygl) 制作。

本模板**仅支持 XeTeX 引擎和 UTF-8 编码，请使用 XeLaTeX 编译！！！**

如果你觉得本仓库有用，请点个 star 小星星 :star::star::star: 支持一下 :star_struck:

## 模板内容

本仓库中含有**开题报告**以及**博士生年度进展报告**模板：

- 若需要**开题报告**模板，请使用 `main.tex` 文件；
- 若需要**硕士生中期报告**模板，请使用 `main_master_mid_report.tex` 文件；
- 若需要**博士生年度进展报告**模板，请使用 `main_phd_mid_report.tex` 文件。

## 免责声明

本模板仅为开题报告模板的参考实现，不保证审查老师不提意见。任何由于使用本模板而引起的论文格式审查问题均与本模板作者无关。

**更新**：本模板作者已使用该模板顺利通过开题答辩，请放心食用~

## 编译方法

这里以 Overleaf 和 VSCode 为例说明。注意如果在本地使用需安装最新版 TeXLive 套装。使用其他编辑器的用户可参考相应编辑器的使用说明，只需注意将编译器设置为 XeLaTeX 即可。

### Overleaf 用户

1. 从 GitHub 下载项目压缩包（点击绿色 Code 按钮，选择 Download ZIP）并上传至 Overleaf 平台（官方 Overleaf 或学校的 LaTeX 助手均可），点击创建新项目-上传项目，并选择下载下来的压缩包
2. **（重要）** 打开项目后，点击左上角菜单，将 编译器 设置为 XeLaTeX。
3. **（重要）** 同样在菜单中，将 主文档 (main tex) 设置为你需要的模板对应的 tex 文件（开题报告为 `main.tex`，硕士生中期报告为 `main_master_mid_report.tex`，博士生年度进展报告为 `main_phd_mid_report.tex`）。
4. 回到编辑器界面，打开在前一步中所选的 tex 文件，然后再点击重新编译。

### 本地 VSCode 用户

1. 安装 LaTeX Workshop 插件，使用 VSCode 打开文件夹
2. 打开你需要的模板对应的 tex 文件 `main.tex`（开题报告为 `main.tex`，硕士生中期报告为 `main_master_mid_report.tex`，博士生中期报告为 `main_phd_mid_report.tex`）。
3. 在左边栏中点击 TeX 图标，展开 `Build LaTeX project`，选择 `Recipe: latexmk (xelatex)` 进行编译。
4. （可选）在 VSCode 设置中搜索 `latex-workshop.latex.recipe.default` 并将其改为 `lastUsed` 以便一直使用该选项编译。

## 使用方法

**请仔细阅读对应 `.tex` 文件中的注释，按照注释的提示进行文档的编写。**

## 贡献

本模板可能存在一些问题，同时学校提供的官方 word 模板可能随时会更新。如果你发现了模板的问题，欢迎给我发 PR 或者提 issue。

## 许可证

上海交通大学校徽校名图片的版权 (`figures/sjtu-logo.png`) 归上海交通大学所有, 该图片下载自[上海交通大学视觉形象识别系统](https://vi.sjtu.edu.cn)。

其余部分使用 MIT 许可证授权。

## 致谢

感谢 @AlexaraWu 和 @LogCreative 对于表格设计的帮助！
