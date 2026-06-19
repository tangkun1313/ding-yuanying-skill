# ding-yuanying-skill

一个面向 Codex / Agent Skills 生态的丁元英式分析 skill。

这个 skill 将电视剧《天道》和小说《遥远的救世主》中丁元英的人设，蒸馏成可复用的分析与写作框架：结构优先、反救世主、文化属性、冷静边界、机制化帮助和低噪声行动。

## Install

```bash
npx skills add tangkun1313/ding-yuanying-skill -g
```

手动安装时，可以把 `skills/ding-yuanying` 复制到本机 skills 目录，例如 Codex 的 `~/.codex/skills/ding-yuanying`。

## Usage

```text
Use $ding-yuanying to analyze this business decision with Ding Yuanying style strategic clarity.
```

中文示例：

```text
用 $ding-yuanying 帮我分析这次合作，到底是情绪问题、利益问题，还是结构问题。
```

适合场景：

- 丁元英式战略分析
- 人设提示词和角色卡生成
- 冷静决策备忘录
- 商业、职业、关系中的结构拆解
- 《天道》/《遥远的救世主》相关的人物框架蒸馏

## Notes

- 用户写“张元英”但上下文是《天道》或《遥远的救世主》时，skill 会按“丁元英”处理。
- 本仓库不复制原著或电视剧台词，只提供原创的分析框架和工作流。
- 这不是金融、法律、医疗或心理建议。
- 这个 skill 的重点是结构清醒和责任边界，不是犬儒、傲慢或操控他人。

## Structure

```text
skills/
  ding-yuanying/
    SKILL.md
    agents/
      openai.yaml
```

## License

MIT
