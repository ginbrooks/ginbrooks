<picture>
  <img src="assets/cover.svg" alt="ginbrooks — 把想法做成可以用的工具。Practical tools for reading and real work." width="100%">
</picture>

我在做一些从实际问题出发的小产品：把读过的内容留成能查的知识库，把反复核对的资料整理成可靠的工作流程。

[**打开作品集 · 直接体验两个项目**](https://ginbrooks.github.io/)

### 01 · Book Wiki Reader

**读完以后，还能找到当时的理解。**

将本地原文、共读笔记与主题线索放在同一个阅读工作台里。支持关键词检索、来源导航与本机阅读进度；配套 Codex Skill 继续讨论书里的问题。

- Python 标准库导入、归档与分块，保留原文和笔记各自的结构。
- 可生成离线网页，无需账号或模型密钥就能浏览、搜索。
- AI 共读由 Codex 执行；独立网页不内置 AI 聊天。

[体验阅读工作台](https://ginbrooks.github.io/demos/book/) · [查看源码与安装方法](https://github.com/ginbrooks/book-wiki-reader-skill)

### 02 · 出运单证工作台

**同一票货，每份文件都要对得上。**

围绕出口单证的资料、复核与文件生成流程，集中处理共用字段、来源确认和业务计算。公开演示可以亲手修改合成资料，检查字段差异并导出预检报告。

- 对比缺项、冲突与待确认来源，保留人工判断。
- Decimal 金额计算，分离客户价与报关价，支持包装与打托方案。
- 本地 Python / Streamlit / SQLite 应用；正式出单需要适配公司模板。

[体验单证预检](https://ginbrooks.github.io/demos/shipping/) · [查看源码与使用边界](https://github.com/ginbrooks/shipping-document-workbench)

---

结果有出处，计算能复现，重要的判断留给人。
