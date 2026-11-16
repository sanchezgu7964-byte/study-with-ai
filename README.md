# study-with-ai

與 AI 一起學習的協議集合。每個 skill 都來自一次實際有效的學習記錄，並設計成可以隨後續經驗擴展。

## Skills

| Skill | 用途 |
|---|---|
| [slide-study-companion](skills/slide-study-companion/SKILL.md) | 逐頁陪讀課件／PDF：使用者主導節奏，AI 先翻譯、再檢驗使用者自己提出的模型 |

## 安裝

- **Claude Code**：把 `skills/<name>/` 複製到 `~/.claude/skills/`（個人）或專案的 `.claude/skills/`。
- **Codex**：把 `skills/<name>/` 複製到 `~/.codex/skills/`，或把 SKILL.md 的「核心協議」貼進 `AGENTS.md`。
- **Claude.ai**：在 skill 設定中上傳 `SKILL.md`。

## 擴展規則

每個 SKILL.md 分成三層：

1. **核心協議**：只收錄已驗證有效的做法。
2. **擴展區／可選工具**：只在使用者需要時才用的手段。
3. **擴展區／學科筆記與觀察記錄**：按學科累積課件慣例和跨章伏筆；只出現過一兩次的現象記在「觀察記錄」，標上日期和樣本數。

**升格條件**：同一現象出現三次以上，而且使用者認可，才從觀察記錄移進核心協議。樣本不足的東西不要寫成規則。
