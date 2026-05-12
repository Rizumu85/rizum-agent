# Rizum Skills

[English](#rizum-skills) | [中文](#rizum-skills-1)

A bilingual communication guideline for AI coding agents: English in files, Chinese in chat summaries.

The installable skill is called `bilingual-guideline`.

## Install

### Claude Plugin

Add this marketplace in Claude:

```text
https://github.com/Rizumu85/rizum-skills
```

Then use `/bilingual-guideline` to activate.

### Codex Skill

```bash
python3 ~/.codex/skills/.system/skill-installer/scripts/install-skill-from-github.py \
  --url https://github.com/Rizumu85/rizum-skills/tree/main/skills/bilingual-guideline
```

### Manual

Copy `CLAUDE.md` or `AGENTS.md` into your project or global config directory.

## Files

```text
rizum-skills/
├── AGENTS.md
├── CLAUDE.md
├── README.md
├── .claude-plugin/
└── skills/bilingual-guideline/SKILL.md
```

## License

MIT

---

# Rizum Skills

[English](#rizum-skills) | [中文](#rizum-skills-1)

给 AI 编程助手用的双语沟通规则：文件用英文，聊天总结用中文。

可安装的 skill 名字是 `bilingual-guideline`。

## 安装

### Claude 插件

在 Claude 里添加这个 marketplace：

```text
https://github.com/Rizumu85/rizum-skills
```

然后用 `/bilingual-guideline` 激活。

### Codex Skill

```bash
python3 ~/.codex/skills/.system/skill-installer/scripts/install-skill-from-github.py \
  --url https://github.com/Rizumu85/rizum-skills/tree/main/skills/bilingual-guideline
```

### 手动安装

把 `CLAUDE.md` 或 `AGENTS.md` 复制到项目根目录或全局配置目录。

## 文件结构

```text
rizum-skills/
├── AGENTS.md
├── CLAUDE.md
├── README.md
├── .claude-plugin/
└── skills/bilingual-guideline/SKILL.md
```

## License

MIT
