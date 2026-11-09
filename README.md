# prompts-chat-zh

prompts.chat 提示词库中文版 — 全球最大开源 AI 提示词库，带中文翻译。

来源：[f/prompts.chat](https://github.com/f/prompts.chat)（原 Awesome ChatGPT Prompts，17.6 万 Star），每 3 天自动同步上游更新。

## 文件

| 文件 | 说明 |
| --- | --- |
| [prompts.csv](prompts.csv) | 上游原版提示词数据（英文，2,925 条） |
| [PROMPTS.md](PROMPTS.md) | 上游原版提示词 Markdown 版 |
| [prompts_zh.json](prompts_zh.json) | 中文版：每条含中文标题 `act_zh`、中文一句话说明 `desc_zh`，提示词正文保留英文原文（贴给 AI 用英文效果更好） |

## 怎么用

- 在 `prompts_zh.json` 里按中文标题/说明搜索，找到想要的提示词。
- 把对应条目的 `prompt`（英文原文）复制给 Claude / ChatGPT / DeepSeek 等模型使用。
- 想要某条提示词的中文全文，告诉我，我单独给你翻。

## 同步

每 3 天自动检查上游 f/prompts.chat 的更新，有新增/改动就同步到这里，并带上中文翻译。
