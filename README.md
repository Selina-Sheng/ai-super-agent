# AI Super Agent 智能超级智能体
基于 Spring AI + RAG + Agent 构建的企业级 AI 应用系统，支持私有知识库问答、多轮对话、工具调用、MCP 服务集成与自主任务规划，可快速落地为智能助手、知识问答、场景化交互等多种商用场景解决方案。

## 核心功能
- 多轮对话与记忆持久化
- 基于 RAG 的私有知识库问答
- 工具调用（联网搜索、文件操作、PDF 生成等）
- MCP 服务集成（如图片搜索服务）
- 基于 ReAct 模式的自主规划智能体
- SSE 流式输出，提升用户体验

## 技术栈
- 后端：Java 21 + Spring Boot 3 + Spring AI
- AI 框架：LangChain4j、Spring AI
- 数据库：PGvector（向量库）、PostgreSQL
- 工具：Ollama、MCP、SSE
- 部署：Docker、Serverless
