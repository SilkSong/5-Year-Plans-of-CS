## Week 2

2026.5.11

* 梳理了李宏毅老师的三节课的笔记, 以OpenClaw为例介绍了 Agent 运作原理, Context Engineering 和 Harness Engineering

2026.5.12

* 看了数字游牧人的 Clause Code 视频, 打算真的把 Claude Code 安装, 用起来
* MyBatisPlus 的 update 方法, SQL 动态拼接默认忽略 NULL, 具体由 FiledStrategy 的各种枚举值来控制, 默认是 NOT_NULL, 可以设置为 NULL
* 看了视频, 了解了一些高级的调试技巧, 以及快捷键, 还是要多用形成肌肉记忆

2026.5.13

* 开始了 hello-agents 的重新学习, 花了很久很久的时间配 API 以及调整学习习惯, 最终大致找回来当时的学习感觉, 准备利用空余时间把第一, 二, 三章快速看一遍, 第四章还剩一个 Reflection 模式没有看, 打算马上进入 Agent 框架的开发学习中去
* 总体来说 白天没有记录什么知识点, 只有一个 `git checkout abc1234` 来 detached HEAD 然后进行提交

2026.5.14

* 看完了 hello-agents 的第六章, 四个智能体框架: AutoGen, AgentScope, LangGraph 和 CAMEL, 并没有很细致的看代码, 找 API 把代码跑起来花了很多功夫, 明天开始看第七章, 搭建自己的智能体框架

2026.5.17

* 看完了 hello-agents 的第七章, 开始搭建自己的智能体框架

## Week 3

2026.5.20

* 开始看 hello-agents 的第八章, 经过一番折腾, 配好了 Qdrant, Neo4j, Embedding 模型, 开始跑基本的 Memory py 文件
* 看完了李宏毅老师的 加快语言模型生成速度: Flash Attention 一节, 本质上是通过洞察 GPU 搬运数据以及计算数据的方式,  直接计算了 output

2026.5.21

* 对 Flash Attention 中介绍的 HBM, SRAM 有了一定的了解
* 知道了 Mac 有一个 MPS (Metal Performance Shaders) 后端可以在 PyTorch 上进行 GPU 计算

2026.5.22

* 快速的看完了 hello-agent 的第八章记忆模块, 开始看第九章 上下文工程
* 看完了李宏毅老师的 加快语言模型生成速度: KV Cache 一节

2026.5.23

* 看完了李宏毅老师的 Positional Embedding 一节, 涉及大量数学矩阵公式推导, 只是加深了对位置编码的理解，以及知道了目前主流的模型架构都用 RoPE 来实现这个知识点
* 快速看完了 hello-agent 的上下文工程, Agentic-RL 两章, 简单过了一下综合案例进阶, 看了一些优秀的毕业设计作品。

## Week 3

2026.5.25

* 重读 hello-agent, 看完了第四章, 智能体经典范式, 把习题又重新温习了一遍
* 整理了一些零散知识: HBM (高带宽内存) SRAM (静态随机存储器) MPS
* 了解了一种词嵌入的算法 BM25, 比 TF-IDF 要更优秀
* MySQL 上所有 varchar 的总数不能超过 65535