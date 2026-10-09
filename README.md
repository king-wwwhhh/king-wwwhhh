# Hi, I'm king-wwwhhh 👋

**Java 后端 · AI 应用开发 · RAG · 多 Agent 协作**

把 AI 接入具体的业务流程：从学习资料问答、复习计划，到本地生活服务和招聘邮件整理。这里记录项目实践、工程实现与开源社区参与。

Building practical AI applications with Java, Spring and retrieval-augmented generation.

## 项目精选

### 📚 [StudyBuddy AI · 期末速成助手](https://github.com/king-wwwhhh/studybuddy-ai)

基于 Spring AI Alibaba 的多 Agent 学习助手，围绕「资料 → 问答 → 计划 → 打卡 → 测验」组织学习流程。

- 文档解析、向量检索与重排构成 RAG 知识库。
- Supervisor 路由协调答疑、计划、测验与教练 Agent。
- 使用 Milvus、SQLite 和 SSE 实现知识检索、进度持久化与流式对话。

`Java 17` · `Spring Boot` · `Spring AI Alibaba` · `Milvus` · `SQLite`

### 🛍️ [Dianping Agent · 本地生活服务与智能助手](https://github.com/king-wwwhhh/dianpingagent)

Java 后端学习实践：将店铺、优惠券和秒杀业务接入对话式工具调用。

- 意图识别与会话上下文驱动店铺查询、优惠券查询和秒杀工具。
- Redis / Lua、Redisson 与 Kafka 用于秒杀校验、并发控制和异步订单处理。
- Agent 对话入口包含登录校验、限流与规则回复兜底。

`Java` · `Spring Boot` · `MySQL` · `Redis` · `Kafka` · `MyBatis-Plus`

### 🎯 [秋招管家 · Recruitment Manager](https://github.com/king-wwwhhh/FRM-Fall-Recruitment-Manager)

Electron 桌面应用：通过 IMAP 获取招聘邮件，调用配置的模型服务解析事件，集中管理笔试、测评、面试和投递进度。

- 招聘事件分类、日历视图与投递记录联动。
- 支持增量拉取、历史邮件重扫和模型输出解析。
- 配置与事件记录存储在本机；AI 解析会把邮件内容发送至用户配置的模型服务。

`Electron` · `JavaScript` · `IMAP` · `LLM API`

更多 Java / Agent 实践：[learnagentpro](https://github.com/king-wwwhhh/learnagentpro)。

## 社区参与

- [LangChain4j PR #6628](https://github.com/langchain4j/langchain4j/pull/6628)：修正重复的 TTS 文档，补充音频转写用法；示例通过 Java 17 编译，文档站构建通过。

- [DockerDesktop-CN PR #86](https://github.com/asxez/DockerDesktop-CN/pull/86)：根据 [#82](https://github.com/asxez/DockerDesktop-CN/issues/82) 的实际使用反馈，补充 Windows 每用户安装路径与文件定位说明。
- [WSL #41407](https://github.com/microsoft/WSL/issues/41407)：分享 Windows / WSL2 启动故障的排障过程。

## 关注方向

Agent 工具调用与会话管理、RAG 检索流程、Java 后端工程，以及可复现的安装与排障文档。

欢迎通过项目 Issues 交流使用反馈与改进建议。
