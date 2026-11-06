# 忆栈 MemStack · Windows 安装包

忆栈（MemStack）是一款跨多家 AI 平台的**聊天会话管理系统**：把 ChatGPT、Claude、豆包、千问、元宝、DeepSeek 等 9 家 AI 的对话收进这台电脑上的一个资料库，支持全文检索、项目归集与 Markdown 导出。正文只存本机，不上传。

本仓库只发布安装包，不含源码。

## 下载

**[下载 Windows 安装包（MemStack-setup.exe）](https://github.com/MFCQLM/memstack-download/releases/latest/download/MemStack-setup.exe)**

这条地址永远指向最新一版。官网 [memstack.net](https://memstack.net/) 上的「下载试用」按钮指向同一个文件。

![忆栈主界面：左栏按来源分，中栏是某个来源的会话列表，右边是当时那一整场问答](https://memstack.net/assets/shots/conversation.jpg)

## 能做什么

- **9 家来源**：Claude 桌面、Claude Code、ChatGPT、千问、元宝桌面、豆包桌面、Codex、WorkBuddy、DeepSeek。八家桌面客户端装好就采；DeepSeek 网页版要在浏览器里装一个扩展（不装就是 0 条）。不用逐条导出。
- **留在这台电脑**：资料库就是普通文件夹，随时打开、拷走、删掉；不登录、不注册、正文不上传。
- **找得到**：全文检索，支持短语、排除词；按来源、时间、标签、项目筛选。
- **整理得起来**：同一条会话可以归进项目，挂要点、写状态；也能导出 Markdown 长期保存。
- **看得见全貌**：全量分析给出主题分布、周报与会话画像。

## 安装

1. 点上面的按钮下载 `MemStack-setup.exe`。
2. 双击运行，按提示装完。安装包已做数字签名，右键「属性 → 数字签名」可以看到签名者；安装过程不需要关闭杀毒软件。
3. 打开软件，30 天全功能试用自动开始，不需要序列号，也不需要注册账号。已有的对话会在后台陆续出现在列表里。
4. 软件安装完成后，再装一个浏览器扩展：打开忆栈「采集中心」→「浏览器扩展」卡 → 点「复制路径」；浏览器地址栏进 `chrome://extensions`（Edge 是 `edge://extensions`），打开「开发者模式」，点「加载已解压的扩展程序」，把路径粘进去。回到采集中心，卡片显示「已连接」就成了。已经开着的页面要重新刷新一次才生效。

系统要求：Windows 10 / 11（64 位）。不支持 macOS、Windows 7 / 8，也不支持手机。

八家桌面客户端都不用装插件；扩展只影响 DeepSeek 网页版（ChatGPT 装了更快，不装也能采）。换浏览器或重装忆栈后要再做一次。

## 试用与授权

装完自动开始 30 天全功能试用。到期后转为只读：已有记录照常能看、能搜、能导出、能备份、能自己删，高级功能入口关闭，数据留在库里。授权在本机校验，软件不向我们的服务器发送数据。

## 支持范围与边界

- 只读这台电脑上客户端已经留下的数据；手机上的对话、本机没留过的历史读不到。
- 更早的历史用官方导出包补：ChatGPT、Claude、DeepSeek 三家支持导入（高级版）。
- 「跨平台」指跨多家 AI 平台，不是跨操作系统。

## 相关链接

- 官网：https://memstack.net/
- 支持来源与各家能采什么：https://memstack.net/sources/
- 使用指南：https://memstack.net/docs/
- 常见问题：https://memstack.net/faq/
- 更新记录：https://memstack.net/changelog/
- 数据处理说明：https://memstack.net/privacy/

问题、建议或某个来源采不到，发邮件到 mem@memstack.net，附上版本号与现象。
