## Week 1

2026.06.04

* 看完了阮一峰周刊的两篇文章: 压缩和中央极限定理
    * 中央极限定理: 无论原始数据如何分布, 大量独立随机变量的和(或者均值)最终会趋于正态分布。
    * 压缩: 大型语言模型本质上是其训练数据的有损压缩；而训练数据本身，又只是世界全部信息的一个有损采样
    * 大数定律: 随着实验次数的增加, 大量独立随机时间的结果最终会趋于均值

* 新增表字段 SQL: `alter table xxx add column xxx int`
* `orchestrate` 这个单子怎么都记不住怎么拼, 怎么读, 然后一问 ChatGPT, `ch` 是希腊语的词根, 类似 `chaos`, `echo`, `character` 的读音, 我一下子就明白了
* Linux 查看目录下是否有文件: `find -name 文件名`

2026.06.05

* 成功订阅了 OpenAI 的 Plus 套餐, 开始了 Vibe Coding 之路

## Week 2

2026.06.09

* 成功在电脑里安装了 **Claude Code**, 利用 **CC Switch** 接入了第三方 API, 会用基本的 CC Switch 的功能: 配置第三方API和模型, Claude Code 跳过初始化配置以及通过配置设置默认权限模式
* 了解了一些基本的前端生态: npm, pnpm 以及项目启动脚本是如何跟 package.json 联动的, 比如为什么 package.json 中写一个 dev: xxx 就可以直接使用 `npm run dev` `pnpm dev` 或者 `pnpm run dev` 来运行
* 了解了一些 CodeX 的基本工作原理: 1. 利用符号 `/` `@` `$` 2. 归档对话和删除对话只是对对话的索引进行操作, 不会操作本地存储对话文件夹产出的目录。
* 在工作中在编写电检需求的时候, 第一次使用了 trae 的 spec 模式和 plan 模式, 编写了单元测试, 在开发的时候比较顺利的完成了需求, 并且修改了单元测试, 最终输出了若干 markdown 文档。


2026.06.10

* 工作中编写代码的时候, 再一次使用了 trae 的 spec 模式和 plan 模式, 清晰的编写了 specs/spec, specs/task, specs/checklist 三个文档, 然后在后面的对话中也比较快速迅速的完成了我希望完成的报表
* 在 CodeX 中生动的体验了 **Skill**, 包括金谷园Skill和傲娇反击技能, 第一次手动创建了一个 skill, 并且对比验证了显式触发和隐式触发它们的效果, 简单了解了 skill 的工作原理: **按需加载和渐进式披露**, 在大模型的上下文中, 会把 skill 的 metadata 加载进去, 如果符合某一个描述, 才会加载具体的 skill 内容。更深刻的体会了 AGENTS.md, skill, rule, spec, plan 这几个文档的用法
* 第一次使用了 `git cherry-pick`, 把功能分支的某一个commit合并到了 dev

2026.06.11

* 清理了一些 Tab 页和未读, 看了几个 Claude Code 的 skill 相关视频
* 重新写了五年计划, 制定了一个半年的 Agent 学习求职计划, 专门建立了一个项目, 莫名触发了 CodeX 的 goal 模式, 尝试让 CodeX 在这段旅程中帮助我。

2026.06.12

* 自己尝试了一些 ppt-skills, 瞬间把五个小时的 Token 额度用光了
* 用 ChatGPT 尝试 ChatGPT Images 2.0 这个模型, 尝试了一些官方博文上的提示词, 也自己做了一些小狗小猫的, 不同风格的, 还根据下午实际发生的事做了一个哆啦A梦的漫画, 体验很真实很震撼
* 看完了李宏毅的 Self Improving part 1


## Week 3

2026.06.20

* 新的一周五天都没有学习, 终于重拾了 hello-agent, 把第七章看完了
* 看完了李宏毅的 Self Improving part 2

2026.06.21

* 今天上午用了2个小时, 下午用了三个小时, 重读厚读了一遍 hello-agent 的第八章, 记忆系统, 四种记忆: 工作记忆, 情景记忆, 语义记忆, 感知记忆; 以及 RAG 系统
* 体会了 CodeX 的功能: Subagent 


## Week 4

2026.06.23

* 比较效率不高的看完了 hello-agent 的上下文工程, 对于一些源码细节和演示代码的效果还没有一个很好的体会。

