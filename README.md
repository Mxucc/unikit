# UniKit 反馈仓库

> 这个仓库**不是** UniKit 的源码仓库，也**不会**放任何源码。它只用来收反馈（Issue）。
> UniKit 在线工具站：<https://unikit.cc>

## 这个仓库是干什么的

- 收集 **BUG 反馈**与**功能建议**；
- 记录已知问题与处理进度。

本项目**暂未开源**（保留所有权利，见站点上的 `LICENSE`），因此这里不接受代码补丁（Pull Request），也没有源码可以浏览 —— 请只通过 Issue 描述问题。

## 怎么反馈 BUG（推荐）

在 <https://unikit.cc> 任意页面底部点 **反馈 BUG**，会直接打开本仓库的新建 Issue 表单，并**自动预填**下面这些环境信息，你只需要写「发生了什么」：

| 表单字段 | 自动填入的内容 |
| --- | --- |
| 站点版本 | 当前版本号，例如 `0.1.0` |
| 操作系统 | macOS / Windows / Android / iOS / Linux / ChromeOS |
| 浏览器 | Chrome / Safari / Edge / Firefox / Opera |
| 页面地址 | 你出问题时所在的页面（已去掉查询串与锚点） |
| 窗口尺寸 | 例如 `1440x900`（窄屏布局专属的问题常只在这里复现） |

也可以自己拼这个地址：在下面这个链接末尾补上参数即可（参数名就是表单里的字段 id）：

```text
https://github.com/Mxucc/unikit/issues/new?template=bug_report.yml&app-version=0.1.0&os=macOS&browser=Chrome&page-url=https%3A%2F%2Funikit.cc%2Ftools%2Fbase64-string-converter&viewport=1440x900
```

所有参数都是可选的，缺哪个就少填哪个；带中文或空格的值记得做 URL 编码。

## 什么信息最有用

1. **复现步骤**：从打开哪个页面、点了什么、输入了什么，到问题出现，一步步写。
2. **预期 vs 实际**：你以为会发生什么，实际发生了什么。
3. **能贴就贴**：报错文案原文、截图（可拖进输入框）、出问题的输入样例（**请先脱敏**，别贴真实口令 / 密钥 / 隐私数据）。
4. **是否稳定复现**：每次都能复现，还是偶尔出现；换个浏览器还一样吗。

## 用什么方式联系

- 需要私下沟通（含敏感信息、授权与合作），发邮件到 **support@unikit.cc**，不要贴到公开 Issue 里。

## 不在受理范围

- 工具功能本身的咨询 / 用法疑问 —— 请先看工具页底部的常见问题；
- 要求公开源码、要求提供自托管或二次分发 —— 本项目未开源，不提供；
- 让站点接入第三方上传 / 抓取代理的请求 —— 站点承诺「浏览器计算，不上传用户数据」，见站点「关于」页。

---

## English (short)

This repository is **not** the source of UniKit — it exists only to collect **bug reports and feature requests**. UniKit itself is **not open source** (all rights reserved), so there is no source code here and pull requests are not accepted.

Click **Report a bug** in the footer of any page on <https://unikit.cc> to open a pre-filled issue form (site version, OS, browser, page URL and viewport are filled in automatically). For anything sensitive, email **support@unikit.cc** instead of posting publicly.
