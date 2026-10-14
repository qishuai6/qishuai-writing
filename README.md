# qishuai-writing

七帅的文章与书稿写作技能（ZCode / Claude Code 等 Agent 通用 Skill）。

一个入口，四个二次选项，一张声音底色：

| 选项 | 用途 |
|---|---|
| ①书稿·忠实整理 | 贴口述稿/转写原稿，保真整理成书稿章节 |
| ②书稿·风格生成 | 给真实经历素材，按「帅哥体」写自传体长文 |
| ③公众号·写稿 | 给选题，按注意力写作八步流程出可发布成稿 |
| ④公众号·体检 | 发已有文章，逐项检查并输出改后全文 |

四选项共用「声音档案」横切层（第一人称、真实数字、口头禅保留、结尾软收）。

## 安装

复制到 Agent 的 skills 目录：

```bash
# ZCode
cp -R . ~/.zcode/skills/qishuai-writing

# 通用 agents 目录（多 Agent 共享）
cp -R . ~/.agents/skills/qishuai-writing
```

## 使用

对 Agent 说触发词即可自动路由：

- 「整理一下」「放进书里」→ 选项一
- 「按我的风格写」→ 选项二
- 「写篇公众号」→ 选项三
- 「体检这篇文章」→ 选项四

## 说明

- 声音档案与金句库（`references/`）是按七帅本人写作样本定制的，换人使用需替换 `voice-profile.md` 与 `golden-lines.md`
- 短视频口播稿不在本技能范围，走独立的 `short-video-coach`

## 更新日志

- **2026-10-13** 项目发布：四合一写作技能——书稿忠实整理 / 帅哥体风格生成 / 公众号写稿 / 公众号体检，四选项共用「七帅声音档案」横切层（合并原 book、write-book-skill、qishuai-writing-style、spenser-writing 四个技能）。
