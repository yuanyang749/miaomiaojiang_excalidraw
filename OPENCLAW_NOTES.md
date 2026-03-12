# OpenClaw Integration Notes

This skill is installed for local OpenClaw use.

## Intended triggers
- 用户说“画图 / 画一个 Excalidraw / 生成架构图 / 生成流程图 / 生成时序图 / 生成对比图”
- slash-style prompts in chat, such as:
  - `/excalidraw ...`
  - `/diagram ...`
  - `/draw ...`
- Telegram 对话里直接发自然语言图表需求
- 用户不指定图类型，只说一句业务或技术场景，比如：
  - “用合适的图表帮我梳理一下支付链路”
  - “帮我把这个 Agent 架构讲清楚”
  - “把 OpenClaw 和 OpenViking 的关系画一下”
  - “给这篇文章配一张能说明问题的图”

## Default inference policy
- 优先自动推断最合适的图类型，而不是先追问一长串表单
- 默认支持的高频类型：业务流程图、系统架构图、时序图、对比图、脑图/概念图、一页讲解图
- 只有在“图类型差异会明显影响结果”或“技术事实缺失会导致画错”时，才追问关键澄清问题

## Local path
- Workspace skill directory: `/Users/wangyuanyang/.openclaw/workspace/skills/miaomiaojiang_excalidraw`

## Renderer setup
From this skill directory:
- `cd references`
- `uv sync`
- `uv run playwright install chromium`
