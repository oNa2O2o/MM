# MM — MiraiMind 买量素材创作 Skill

MiraiMind AI陪伴产品短视频买量素材全流程创作工具。

**当前版本**：v1.2.0

---

## 安装

将 `skill.md` 复制到你的 Claude Code skills 目录：

```bash
# 克隆仓库
git clone https://github.com/oNa2O2o/MM.git

# 复制 skill 文件
cp MM/skill.md ~/.claude/skills/MM/skill.md
```

Windows：
```powershell
git clone https://github.com/oNa2O2o/MM.git
copy MM\skill.md %USERPROFILE%\.claude\skills\MM\skill.md
```

---

## 更新

```bash
cd MM && git pull
cp skill.md ~/.claude/skills/MM/skill.md
```

Windows：
```powershell
cd MM && git pull
copy skill.md %USERPROFILE%\.claude\skills\MM\skill.md
```

---

## 使用

在 Claude Code 中输入：

```
/MM
```

或触发词：`做MiraiMind素材`、`帮我做买量视频`

---

## 依赖 Skills

本 skill 会自动调用以下 skills（需同步安装）：

- `hook-audit` — 开头钩子审核
- `dialogue-check` — 台词AI味检测  
- `seedance-prompt-zh` — Seedance提示词生成

---

## Changelog

### v1.2.0
- T10：提示词明确写入角色年龄30+成熟，禁止幼态
- T11：身材描述须具体化，禁止模糊词
- T2：更新，明确写入"禁止POV角色出镜"
- S8（新增）：男性向标题以男性用户为主视角

### v1.1.0
- 初始版本，23条通用审核规则
- 支持KR/EN双市场，男性向/女性向
