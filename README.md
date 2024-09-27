# 猎隼代码风格指南

本项目为西北农林科技大学猎隼战队（NWAFU Lie Sun, NLS）代码风格指南，本指南主要有以下几个目标：

+ **一致性**：确保代码风格在整个项目中保持一致，便于维护和协作
+ **可读性**：提高代码的可读性，使开发者能够快速理解代码逻辑
+ **文档化**：保证注释和文档的规范性，帮组开发者理解和使用代码

## C++

C++ 程序员都知道，该语言有很多强大的特性（feature），但其强大之处也伴随着复杂性，让代码更加容易出错，难以阅读、维护。

所以，为了实现上述目标，我们选择使用 Google C++ 风格指南，您可以通过以下途径获取：

+ ReadTheDocs 托管地址：[在线阅读最新版本](https://zh-google-styleguide.readthedocs.io/en/latest/)
+ GitHub 托管地址：[zh-google-styleguide](https://github.com/zh-google-styleguide/zh-google-styleguide)
+ 离线文档下载地址：[release](https://github.com/zh-google-styleguide/zh-google-styleguide/releases)

> [!note] 
>
> 以上所提供的并非 Google 官方项目，而是由国内程序员凭热情创建和维护，使用时应对他们的付出表示感谢。
>
> 如果您也想要加入他们，请联系 [Yang.Y](https://github.com/yangyubo)。
>
> 如果您关注的是 Google 官方英文版，请移步 [Google Style Guide](https://github.com/google/styleguide)。

## Git

为了让开发者提交历史更具可读性，并在自动化工具（如版本管理、发布流程等）中变得更加有用，我们选择使用  Conventional Commits 作为 Git 提交规范，用于在提交消息中添加结构化的信息。您可以通过以下途径获取：

+ 官方网站：[Conventional Commits](https://www.conventionalcommits.org/zh-hans/v1.0.0/)
+ GitHub 托管地址：[conventionalcommits.org](https://github.com/conventional-commits/conventionalcommits.org)

## 文档

在团队开发流程中，一份优秀的开发文档的重要性不言而喻。考虑到简易性、可读性和版本控制，我们选择使用 Markdown 进行开发文档的编写。

同时为了保证文档风格的统一性和排版的优雅度，我们对开发文档编写作出如下规范：

+ 语法上遵循 GitHub Markdown 语法，详情请访问 [GitHub 文档](https://docs.github.com/zh/get-started/writing-on-github)
+ 风格上遵循 [Google Markdown style](https://github.com/google/styleguide/blob/gh-pages/docguide/style.md) 

同时，鉴于中文排版与英文排版的差异性，开发文档也应遵循[中文文案排版指北](https://lrita.github.io/wiki/chinese-copywriting-guidelines/)。

