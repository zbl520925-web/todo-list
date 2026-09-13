# ChatGPT + Codex 协作方式

GitHub Issue 是网页版 ChatGPT 与 Codex 之间的任务单。

## 在网页版 ChatGPT 中

连接 GitHub 后发送：

> 读取 `zbl520925-web/todo-list` 的 `main` 分支。根据我的需求创建一个简短的“Codex 开发任务”Issue，只填写功能目标、交互方式、验收标准和必要限制，不要粘贴代码。我的需求是：……

网页版 ChatGPT 应只整理需求，不修改代码。新 Issue 会自动带上 `codex-ready` 标签。

## 在 Codex 中

发送：

> 处理 `zbl520925-web/todo-list` 最新的 `codex-ready` Issue。

Codex 将核对仓库、实现需求、测试、推送分支，并报告分支名和提交号。

