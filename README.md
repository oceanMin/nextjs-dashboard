## 欢迎来到 Learn Next.js 中文教程
Next.js v14 版本发布时，除了正常的版本更新之外，还发布了一个基于 App Router 架构的免费学习教程，通过构建全栈 Web 应用程序，可以让您更好的了解 Next.js 的主要功能。

本系列是基于[官方教程](https://nextjs.org/learn)的一个中文翻译版本。在翻译、整理的过程中，每个章节对应的 Example 代码，笔者也都进行了测试，有问题的部分也进行了修改，参见 Github 项目 [nextjs-learn-example](https://github.com/qufei1993/nextjs-learn-example)。

## 我们将要做的
![image](https://github.com/user-attachments/assets/477a894e-0d26-4ce9-82ac-3993bd140491)

在这个课程中，我们将构建一个财务 Dashboard 的简化版本，其中包含以下内容：

- 一个公共首页。
- 一个登录页面。
- 受身份验证保护的仪表板页面。
用户能够添加、编辑和删除发票。
该 Dashboard 还将有一个相应的数据库，在后面的章节中将对其进行设置。

通过本课程，您将掌握构建全栈 Next.js 应用程序所需的基本技能。

## 概述
以下是本课程中您将学到的功能：

- Styling（样式化）： 在 Next.js 中样式化应用程序的不同方法。
- Optimizations（优化）： 如何优化图像、链接和字体。
- Routing（路由）： 使用文件系统路由创建嵌套布局和页面。
- Data Fetching（数据获取）： 如何在 Vercel 上设置数据库，以及获取和流式传输的最佳实践。
- Search and Pagination（搜索和分页）： 如何使用 URL 搜索参数实现搜索和分页。
- Mutating Data（数据突变）： 如何使用 React Server Actions 操作数据，并重新验证 Next.js 缓存。
- Error Handling（错误处理）： 如何处理一般错误和 404 未找到错误。
- Form Validation and Accessibility（表单验证和可访问性）： 如何进行服务器端表单验证以及提高可访问性的提示。
- Authentication（身份验证）： 如何使用 [NextAuth.js](https://next-auth.js.org/) 和中间件为应用程序添加身份验证。
- Metadata（元数据）： 如何添加元数据并为社交分享准备您的应用程序。
## 先决知识
本课程假设您对 React 和 JavaScript 有基本的了解。如果您是 React 的新手，我们建议您首先完成我们的 React 基础课程，以学习 [React 的基础知识](https://nextjs.org/learn/react-foundations)，如组件、props、state 和 hooks，以及像 Server Components 和 Suspense 这样的新功能。

## 系统要求
在开始本课程之前，请确保您的系统满足以下要求：

- 安装 Node.js 18.17.0 或更高版本。[下载地址](https://nodejs.org/en)
- 操作系统：macOS、Windows（包括WSL）或Linux。
另外，您还需要一个 GitHub 账号和一个 Vercel 账号。（Vercel 是用来部署用的，如果服务只是在本地运行，做为学习使用，Vercel 账号也不是必须的）。
 
