# 👋 个人介绍
Hi，我是一名持续成长的全栈向前端开发者。
**终身学习 · 热爱工程化 · 深耕 AI + 开发融合落地**
座右铭：无限进步 🚀
## 🧑‍💻 个人定位
主攻前端开发，熟悉 Node.js 后端开发，具备完整前后端联调、数据库设计、项目部署能力；擅长结合 AI 工具、RAG、大模型链路提升开发效率，追求可落地、高性能、规范的工程化项目。
## 🛠 技术栈
### 前端核心（深耕实战）
- 基础：HTML5 / CSS3（BEM规范） / Less / JavaScript(ES6+)，精通异步、闭包、原型链，熟练 Flex/Grid 响应式、语义化布局
- 框架：Vue2/3（路由、组件化、生命周期）、React、Angular
- 类型：TypeScript 类型约束与类型声明
- 样式工程：Tailwind CSS 原子化样式
- 网络优化：Axios 请求封装、SWR 缓存策略、请求去重、弱网重试
- 本地存储：localStorage / localforage（IndexedDB 大容量持久化）
- 工程化：Vite / Webpack 双构建、Vuex / Pinia 状态管理、MSW Mock、PWA、Vitest 单元测试
- 代码规范：ESLint + Prettier + Husky + commitlint 标准化 Git 提交
### 后端 & 服务端（可独立开发接口、联调）
- 运行时：Node.js + Express 4.x
- 鉴权：JWT 无状态登录认证、请求鉴权中间件
- 数据库：MySQL、PostgreSQL 建表、连接池、SQL 初始化脚本
- 基础语言：C（熟练，指针/内存管理）｜Java（基础，面向对象/IO/异常）｜Python（入门，简易自动化脚本）
- 版本控制：Git 分支管理、规范提交、lint-staged 校验
### AI 应用开发（特色加分项）
- 大模型链路：LangChain / LangGraph 任务编排、流式输出实现
- 知识库：RAG 向量检索、文档问答落地
- 开发提效：Claude / Codex 等 AI 工具辅助编码，MCP/Skill 优化 AI 开发流程
### 多媒体 & 其他工具
- 语音能力：百度 ASR 语音转文字、TTS 文本合成语音
- 部署上线：Vercel 静态/全栈项目部署、环境变量配置、线上项目发布
## 📦 实战项目
1. **星选商城——分层缓存全栈高性能移动端电商系统**
   - [我的星选商城项目](https://github.com/Guwen-yue/shop)
## 📫 联系方式
- 邮箱：[2606633761@qq.com](mailto:2606633761@qq.com)
---
# 💼 求职沟通
boss, 你好。
我是一位 AI Native 开发者，codex/claude codex 重度用户，熟悉 SDD 开发。
具备 react+ts, nextjs/nestjs 全栈开发能力，了解 python,fastapi 等后端框架。熟练掌握 docker, git, 项目部署。
擅长基于 langchain/langgraph/langsmith/deepagents 全栈 Agent 开发，有多个 ai coding 的项目经验，Agentic RAG 优化经验。
对贵公司的岗位挺感兴趣，能安排面试不？
期待加入团队，开发让用户尖叫的 AI Agent 产品。
---
# 🐳 Docker
- Docker
- Nginx（原文：nignx）
---
# 🛠 Tool / Zod / LangChain / Worker / Redis
- Tool
- Zod
- LangChain
- Worker
- Redis
---
# ⚛️ Next.js
- Link 用 prefetch 会预加载组件里面的内容，加上 DNS 就会预解析域名
- Turbopack：打包工具，可以增量计算，已经缓存过的可以不用再次打包
- React Compiler：三个性能优化 Hook 自动用
- App Router（原文：approter）
  - layout：这个是当前文件夹下面的
  - template：这个嵌套优先级低于 layout 且不会持久化数据（layout 的 child 是被 template 包住的 page）
## 渲染模式
- `#root` 挂载节点（跟渲染模式有关）
- SPA 也是 SEO：写 title、meta 更易被看到，与 GEO（AI 更容易拿来训练）
### ========================== CSR（客户端渲染）

- 客户端渲染
- 这个渲染出来的会是空壳 HTML
- 只有这个可以带交互的 Hook

### SSR（服务端渲染）

- 服务端渲染
- -> SSG
- 实时的服务端

### SEO 相关
- 这个带 SEO 的，用 `use client` 就是标记页面不会加 SEO
---
# 🚀 技术亮点
- autoTokenizer（transform 提供的）
- WebGPU
- 失败降级为 WebGL
- 单例设计模式
- `npm install -D @webgpu/types`
- 缺少依赖报错
- `??=` 空值合并运算符
- 懒加载和缓存
## 状态与进度管理
- 给函数为了获取最新状态
- 多个文件并发下载时进度回调频繁触发

```js
setProgressItems((prev) => [...prev, e.data]);
```
## WebGPU / dtype
- dtype：在 Web 端这样的格式，可以使用的显存更小
## SSE 流式生成
- SSE（Server Sent Events）
- 这个有时候不用缓存是为了保证实时性，开来 cache 可能会有问题时接收旧数据，接受的内容就会出问题
---
# 📦 JSON 格式化输出
- 利用 `JsonOutputParser` 输出解析器（这个利用正则提取里面的内容）
- 利用 `bindTool` 告诉大模型按照 `Zod Schema` 返回数据，而不是真调函数
---
# 🔌 WebSocket
- WebSocket：直连通道
---
# 🤖 Agent / AI 技术
- Agent
- LangGraph
- Agentic RAG
- LangSmith
- DeepAgents
- RunnableSequence
- OpenEvals
- QuickJS
- WASM
- dedent：自动识别非空行里面的共同的前置空格，适合写系统提示词
- MCP
- Events
---

# 🗄️ 数据库 & 相关工具

- Neo4j：图数据库
- SQLAlchemy
- Attu（Milvus 可视化窗口）
- Supabase
- Mem0
- Elasticsearch
- BM25
- ORM
- Drizzle
---
# 🔄 设计模式 & 响应式编程
- 观察者模式
- 发布-订阅者模式
- RxJS.js：观察订阅者模式
- Proxy
---
# 🧠 其他技术
- ONNX Runtime
- Kubernetes（K8s）
- OSS
- Tavily
- P5.js（手绘组件库）
---
# 💾 存储方案
- OSS
- MinIO
---
# 🏗️ NestJS
## 依赖注入与模块
- Inject 注入：被这个装饰了就可以导出给其他的 Service 模块使用
- Controller：这个模块就是负责路由以及指定要执行什么函数（这个函数真正具体的功能一般是在 Service 里面进行执行的）
- Module：是
---
# 🔐 安全
- XSS 攻击防范
---
# 🏢 企业级知识库项目
- RBAC 权限管理
