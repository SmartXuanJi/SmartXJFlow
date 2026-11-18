# 玄机数据AI智能流程编排软件 · 发布页

本仓库是 **v2027.1.0** 的产品介绍页、下载入口与使用文章，**不包含应用源码**。
应用为 Windows 桌面软件（绿色免安装），源码与内部文档不入库。

- 发布页（GitHub Pages）：https://smartxuanji.github.io/SmartXJFlow/
- 版本对比：https://smartxuanji.github.io/SmartXJFlow/version-diff.html
- 使用文章：https://smartxuanji.github.io/SmartXJFlow/articles/index.html

## 下载

| 项目 | 内容 |
|---|---|
| 安装包 | `SmartXJFlow_v2027.1.0.zip`（234.5 MB） |
| 直链 | https://github.com/SmartXuanJi/SmartXJFlow/releases/download/v2027.1.0/SmartXJFlow_v2027.1.0.zip |
| 全部版本 | https://github.com/SmartXuanJi/SmartXJFlow/releases |
| 平台 | Windows 10 / 11（64 位），解压即用，无需 Python 环境 |
| SHA-256 | `0da1d9729e90268448790844f2faef231704ad5fdd60466fea9097bed3cb1bb5` |

下载后建议核对校验值（PowerShell）：

```powershell
Get-FileHash .\SmartXJFlow_v2027.1.0.zip -Algorithm SHA256
```

## 这是一个什么软件

本地优先的可视化流程自动化工作台：24 种节点把 LLM、代码、文件、数据库与外部工具连成流程，
支持手动、定时、批量、文件夹监听、API、轻量表单、子流程与不落库试跑等触发方式。
流程、执行记录、知识库与日志默认保存在本机；云端模型由用户自配 API Key，费用与服务商直接结算。

免费版可跑通核心编排（单流程 ≤10 节点、1 个 AI 接口等数量限制），专业版解锁本地模型、
图片/视频、知识库、子流程、高级调试与导出等能力。价格与额度以应用内「账户与授权」为准。

## 演示视频

- [表单入口与文件夹监听](https://github.com/SmartXuanJi/SmartXJFlow/releases/download/v2027.1.0/demo-folder-watch-feature.mp4)
- [保存预检与运行前预检](https://github.com/SmartXuanJi/SmartXJFlow/releases/download/v2027.1.0/demo-preflight-check.mp4)
- [MCP 客户端：把外部工具变成节点](https://github.com/SmartXuanJi/SmartXJFlow/releases/download/v2027.1.0/demo-mcp-client.mp4)

## 文章目录

| # | 标题 |
|---|---|
| 01 | [不写代码批量处理 100 个 Excel 文件：配一次，之后拖进文件夹就跑](articles/01-excel-batch.html) |
| 02 | [本地模型下载完却跑不起来：依赖缺失与文件不完整的排查顺序](articles/02-local-model-troubleshooting.html) |
| 03 | [换电脑不丢流程：拷贝数据目录（附必须带走的清单）](articles/03-migrate-to-new-pc.html) |
| 04 | [客户资料不想上传云端：本地跑 AI 的三种做法与边界](articles/04-client-data-stays-local.html) |
| 05 | [AI 生成的流程总跑不起来？先看「运行前体检」这一页](articles/05-preflight-check.html) |
| 06 | [定时任务总在半夜失败：错过执行、补跑与静默怎么设](articles/06-scheduled-tasks.html) |
| 07 | [把执行记录整理成一份能交给老板看的报告](articles/07-execution-report.html) |
| 08 | [不想租服务器做自动化：本地工具与云端自动化怎么选](articles/08-local-vs-cloud-automation.html) |
| 09 | [表格按列筛完再让 AI 逐行改写：一条流程的搭法](articles/09-ai-rewrite-table-rows.html) |
| 10 | [会议纪要转待办：从粘贴文本到结构化输出](articles/10-meeting-notes-to-todos.html) |
| 11 | [API Key 怎么存才不会写进流程文件](articles/11-api-key-and-redaction.html) |
| 12 | [免费版能跑到哪一步：10 个节点的真实边界](articles/12-free-plan-limits.html) |

## 授权与说明

- 授权与分发说明：以安装包内 `LICENSE` 与应用内「账户与授权」页说明为准
- 数据处理说明：流程、执行记录、知识库与日志默认保存在本机，详见应用内「关于」页
- 支持邮箱：support@smartxuanji.cn
- 本仓库页面与文章由开发者本人撰写；不刷评论、不买榜、不请人代写好评。
- 安装包随包第三方组件许可证见安装目录 `THIRD_PARTY_NOTICES.txt` 与 `licenses/`。
