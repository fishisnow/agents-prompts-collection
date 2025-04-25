中文 | [English](README_en.md)

# Agents Chat Collection

这是一个用于收集开源 AI Agent 与用户交互对话过程的仓库，专注于记录和展示各种agent与AI交互的实例，帮助开发者学习和了解 AI Agent的工作原理。

🌐 [在线浏览所有对话示例](https://fishisnow.github.io/agents-chat-collection/)

## 项目介绍

Agents Chat Collection 仅作为一个学习资源，收集了各种开源 agent 与 AI 交互的对话过程。通过研究这些对话，开发者可以直观地了解不同agent的运作方式和交互流程，从而获得对AI对话系统的深入理解。

## 收集的Agent

### openai-agents

[openai-agents - MCP Filesystem 示例](https://fishisnow.github.io/agents-chat-collection/openai_agents/conversation_filesystem_mcp.html) - 展示AI代理如何基于文件系统的 mcp server 完成用户任务的过程。

### browser_use

[browser_use - 添加待办事项对话](https://fishisnow.github.io/agents-chat-collection/browser_use/conversation_add_todo.html) - 展示了AI如何通过浏览器接口与网络交互的过程。

### OpenManus

[OpenManus - 添加待办事项对话](https://fishisnow.github.io/agents-chat-collection/OpenManus/conversation_add_todo.html) - 展示了AI如何自动完成待办事项的添加，体验智能化的任务处理流程。

### MidScene

[MidScene - 智能任务规划(Dom树)](https://fishisnow.github.io/agents-chat-collection/midscene/conversation_plan_by_domtree.html) - 根据截图和页面 Dom 树的智能任务分析与执行规划。

[MidScene - 智能任务规划(视觉)](https://fishisnow.github.io/agents-chat-collection/midscene/conversation_plan_by_vision.html) - 基于界面元素视觉定位的智能任务分析与执行规划。

[MidScene - DOM智能识别](https://fishisnow.github.io/agents-chat-collection/midscene/conversation_inspect_by_domtree.html) - 根据截图和页面 Dom 树，精确识别页面元素的 ID。

[MidScene - 视觉智能定位](https://fishisnow.github.io/agents-chat-collection/midscene/conversation_inspect_by_vision.html) - 基于界面元素视觉定位，返回元素的坐标（需使用支持视觉定位的大模型）

### openui

[openui - 创建个人主页示例](https://fishisnow.github.io/agents-chat-collection/openui/conversation_create_homepage.html) - 展示AI代理如何创建个人主页的网站页面。

## 如何使用

你可以：
1. 直接访问 [在线演示页面](https://fishisnow.github.io/agents-chat-collection/) 查看所有对话示例
2. 克隆本仓库后在本地浏览器中打开HTML文件查看对话过程

## 如何收集

简单几行代码，快速收集 agent 与 gpt 的对话过程
👉 [ai_chat_html_exporter](https://github.com/fishisnow/ai_chat_html_exporter)

## 贡献指南

欢迎贡献更多的agent对话示例！如果你有优质的agent与AI交互的对话过程，可以通过Pull Request提交。

## 许可证

MIT
