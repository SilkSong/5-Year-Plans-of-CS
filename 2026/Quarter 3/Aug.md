## Week 3

2026.08.18

* 看完了 hello-agent 的第十三章, 智能旅行助手, 对于建模, 一整个智能体的前后端工程有了一个基本的了解

2026.08.19

* 对 FastAPI 的一个最小化接口进行了学习
* 对 pyproject.toml 有了初步了解, 它是现代 Python 项目的统一配置文件
* 对 python 的包模块运行模式有了初步了解  `python -m app.main`, 进一步对 Python 双下划线的特殊变量诸如 `__name__` `__package__` 在包模式和程序入口运行时不同的赋值有了初步了解
* 重新开始看 hello-agent, 从第四章开始看

2026.08.20

* 深度研究基本的 ReAct 框架, 并用 Anthropic API 重写了该流程, 理解了框架是如何让输出标准化的: 模型训练 trajectory, API Schema约束, 并且简单了解了 strict 参数的 grammar-constrained sampling 保证工具名称和参数符合 Schema
* 重新又看完了 hello-agent 的第四章: 三种基本范式和第七章:Agent框架, 对于比如说兼容 OpenAI 原生 function call 等部分现在都有了新的认知, 之前都不知道的
* 对于 Python 语法, @classmethod @abstractmethod 有了新的认知, 一个是修饰类方法, 一个是继承ABC类后定义的抽象方法, 强制子类实现才可以实例化

2026.08.21

* 看完了 hello-agent 的记忆系统

2026.08.23

* 看完了 hello-agent 的上下文工程


## Week 4

2026.08.24

* 重新开始看 learn-claude-code, 看完了 s01~s05, agent loop, tool use, permission, hook, todo-write, 受益良多