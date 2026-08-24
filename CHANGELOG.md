# 更新日志

本文件记录本模板各版本的重要变更。

## [v2.0] - 2026-08-24

### Added

- 新增公共核心 `styles/sjtu-forms-common.sty`，集中处理三类报告共用的信息存储、课题来源和签名配置。
- 新增统一的 `\sjtuformsetup` 键值接口，用于配置信息。

### Changed

- 使用 LaTeX3 重构开题报告、硕士生中期报告和博士生年度进展报告的信息录入逻辑。
- 将三个报告样式中的公共部分提取到公共样式文件，报告专属的字段和排版仍由各自样式文件负责。

### Removed

- 移除旧版独立信息设置命令 `\studentid`、`\name`、`\degreeprogram`、`\studymode`、`\supervisor`、`\thesistitle`、`\school`、`\major`、`\proposaldate`、`\examdate`、`\venue`、`\proposedtitle`、`\researchsources`、`\enrollment`、`\signatureimage`、`\signaturetext` 和 `\signaturedate`，统一改用 `\sjtuformsetup`。

### Fixed

- 修复使用 `xdvipdfmx` 编译时遇到的 `Object @page.1 already defined` 警告
