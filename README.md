### 你好，我是范传勋 👋

**AI 应用开发** · 2027 届 · 中原科技学院 · 人工智能专业

大模型应用方向（RAG / Agent / Prompt Engineering），目标是做出能真正上线、被用户使用的 AI 产品。

---

#### 🧰 技术栈

`Python`　`RAG`　`LangChain`　`CrewAI`　`Prompt Engineering`　`Function Calling`　`TypeScript`　`Next.js`　`React`　`Vercel AI SDK`　`Node.js`　`微信云开发（CloudBase）`　`向量检索`　`内容安全`　`Git`

---

#### 🔨 项目

**[向晚问思](https://github.com/fanchuanxun/xiangwan-wensi)** — 经典思想思辨 RAG 微信小程序

> 已正式上线并通过 ICP 备案。在云函数受限环境（Node 16、无原生依赖）下自研轻量中文检索链路
> （N-gram 分词 + 概念桥 + 分层加权打分），零外部依赖冷启动；设计「危机优先 + 5 类意图 + 15 领域」
> 的意图路由，落地四种回答模式（快答 / 深思 / 问思 / 苏格拉底）、Freshness 实时性轨道
> 与 msgSecCheck 内容安全双闸。
>
> `6 云函数`　`8 集合`　`语料 36 部 / 37 片段`　`20 轮上下文`

**[AIClassRoom](https://github.com/fanchuanxun/aiclassroom)** — AI 多智能体互动课堂

> 输入一个教学主题，多智能体协作生成「1 位 AI 老师 + 4 位 AI 同学」的沉浸式互动课程。
> 三个 Agent 走统一的显式节点流水线（Retrieve → Plan → Draft → Validate → Critique → Finalize），
> Validate 用 Zod + 领域不变量双重校验，不通过自动进入重试 / 修复；三条 SSE 端点流式推流，
> 首个场景就绪即可进课堂、剩余场景后台续推。pnpm monorepo，LLM 调用收敛到唯一入口。
> 浏览器实测中发现并修复了「Provider 启用状态被顺序写入覆盖」的状态机缺陷（含 9 个回归用例）。
>
> `117 单测`　`11 家模型服务`　`3 个 SSE 端点`　`Next.js 16 / React 19 / TypeScript strict`

**[企业内部知识问答与制度助手](https://github.com/fanchuanxun/enterprise-knowledge-assistant)** — 证据检索型制度问答原型

> 不引入向量库与外部模型，用 2-gram 切词 + 同义词归一 + 标题权重 + 主题一致性校验手写检索链路；
> 只在已收录资料中检索证据并标注来源，无依据时明确拒答、**不调用模型**。
> 单文件前端（双击即用、零构建）+ 可选零依赖 Node 服务端（scrypt 口令哈希 + HMAC token、
> 越权在序列化前过滤、追加式审计日志 + 哈希链可检出篡改、客户端上报按来源分层）。
> 演示作品，非生产级系统 —— 与生产环境的差距清单见 `docs/企业级差距评估.md`。
>
> `118 条离线评测`　`10 套测试 / 356 断言`　`7 份工程文档`　`零运行时依赖`

**[CrewAI 多智能体学习助手](https://github.com/fanchuanxun/crewai-study-assistant)** — 多格式文档自动转知识库

> 基于 CrewAI 拆分 6 个角色 Agent（解析 / 问答 / 学习规划 / 知识总结 / 出题 / 写作），
> 以 Process.sequential 编排「解析 → 抽取 → 生成问答对 → 检索作答」端到端链路。
>
> 实测：单份资料平均 **9.4s**（6.6 ~ 14.2s），来源支撑率 **93.3%**（14/15，二次 LLM 判定）

**[技术笔记](https://github.com/fanchuanxun/tech-notes)** — 技术笔记与文章

---

#### 📱 体验「向晚问思」

微信扫描下方小程序码即可体验（个人主体未认证版本，暂不支持微信内搜索）：

<img src="qrcode.jpg" width="220" alt="向晚问思小程序码" />

---

#### 📫 联系

- 邮箱：fanchuanxun@163.com
- 求职意向：AI 应用开发 / 大模型应用开发（2027 届）
