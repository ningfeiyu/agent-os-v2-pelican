Title: Agent OS v2.0 实战：定义第一个 Validator 子代理
Date: 2026-08-13
Category: Multi-Agent

# Agent OS v2.0 实战：定义第一个 Validator 子代理

我们将��行 CONST-09（子代理隔离原则），构建第一个专职子代理：Validator。

## 为什么是 Validator？
它是架构中的“质量守门员”，负责复��任务产出，风险最低。

## ��行步��
1. 定义子代理配置：`agents/subagents/validator.md`。
2. 配置校验��环：接收产出 -> 对照清单 -> Approved/Error。

## 小结
通过这个 Validator，我们实现了“生成与校验分离”。