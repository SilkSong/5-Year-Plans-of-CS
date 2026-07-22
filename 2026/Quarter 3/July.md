## Week 2

2026.07.06

* 看完了hello-agent 第十二章, 智能体综合评估, 对 BFCL, GAIA 有了一个大概的认知, 对于框架的实现这些细节还没有仔细看, 我认为现阶段先学会使用即可
* 简单了解了 Bun 是什么
* 对于 CI/CD 有了一个基本的概念, 持续集成和持续交付

2026.07.07

* 再次看完了 hello-agent 的记忆与检索章节, 更加注重功能和架构设计
* 阅读了 OpenAI 的 Dreaming 博客

2026.07.08

* 再次粗看完了 hello-agent 的上下文工程章节

2026.07.09

* 再次粗看完了 hello-agent 的 MCP 章节, 运行体验了一下赛博小镇和深度研究助手两个项目

2026.07.10

* 周五, 读了 Lil Wang 的 Scaling Law Careful 和 Harness 两篇比较硬核的 Blog, 看了李宏毅老师生成式AI导论的大语言模型的训练过程

2026.07.11

* 看完了生成式AI导论的第七章, Pre-train -> SFT -> RLHF 三阶段早就知道, 但看完这节课才对每个阶段的作用以及意义有了更清晰的认识, 例子非常的生动
* hello-agent 对于记忆系统中 Qdrant, Neo4j 和 SQLite 的存储有了更深入的理解, 对于 RAG pipline 的工作流, MarkItDown后分块然后词嵌入然后索引到原文的流水线也有了更深入的理解

## Week 3

2026.07.14

* 重看了 hello-agent 的上下文工程, 本质上还是一种系统工程, 随着 LLM 能力 (上下文窗口, 推理能力) 的增强, 如何组织各种内容填充上下文窗口让模型可以产生更好的回答, 这些内容来自 1. 用户提问 2. 系统提示词 3. 记忆 4. 外部知识库, MCP, Skill 等等, 如何结构化他们, 形成的一套最佳实践的方法论
* 文章中的上下文工程包括 GSSC 流水线, NoteTool 和 TerminalTool


2026.07.18

* 开始看 learn-claude-code 这个仓库, 第一次接触到了 Anthropic API, OpenAI chat completion 和 response API, 通过单步调试 Debug, 对 agent loop 有了更深刻的理解, 对 tool call 有了更深入的理解, 看完了 registry, permission, hook 到了第四章。

## Week 4

2026.07.20

* 看learn-claude-code仓库, 看完了todo(计划), subagent, skill 和 compact 四个章节, subagent 和 skill 都是比较直觉的, todo 也很好理解, 新增提示词, 更新 todo, compact 比较复杂, 还需要再理解一下

2026.07.21

* 看 learn-claude-code仓库, 认真的把 compact, memory, system_prompt 三节看完了, compact 是四级压缩管线和兜底调用, memory 是按需加载, 每次调用前加载, 调用后更新记忆和巩固, system_prompt 是根据上下文灵活加载, 都认真的把整个流程看明白了