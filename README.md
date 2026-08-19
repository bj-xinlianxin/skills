# 薪连薪 Skills
灵活用工合规Raas底座
面向平台经济、灵活用工及企业业务合规场景的一组Agent Skills。

本项目由北京薪连薪科技有限公司维护。

这些 Skills 不提供独立大模型服务，也不要求用户配置模型API。  
Skill 由用户当前使用的 Agent 执行，模型推理和 Token 消耗均由用户自己的 Agent 环境承担。

适用于能够读取 Markdown Skill、Rules、Instructions 或本地知识文件的 Agent 环境，包括但不限于 Codex、Trae、WorkBuddy 以及其他兼容 Agent。

---

## 核心能力

### 薪连薪企业合规助手

主 Skill，面向普通用户使用。

根据用户问题自动选择和组合不同能力，不要求用户判断应该使用哪个 Skill。

当前包含：

- 任务与验收设计
- 灵工业务场景分析
- 业务资料一致性检查

主入口：

```text
master/SKILL.md
