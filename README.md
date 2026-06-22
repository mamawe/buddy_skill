# buddy_skill

Alex 的 WorkBuddy Skills 公开仓库。每个 skill 有自己的独立展示页。

---

## 可用 Skills

| Skill | 简介 | 独立展示页 |
|--------|------|-------------|
| **seed-more** | 复刻得到大脑「发芽」功能，跨域关联知识库生成 Aha 金句 | [查看详情 →](skills/seed-more/README.md) |
| **NoFluff** | 拒绝 AI 水文，评估文章各章节的实际阅读价值 | [查看详情 →](skills/NoFluff/README.md) |

---

## 安装方式

```bash
# 安装 seed-more
npx skills add mamawe/buddy_skill --skill seed-more

# 安装 NoFluff
npx skills add mamawe/buddy_skill --skill NoFluff
```

适用：WorkBuddy · Claude Code · Cursor · 任何支持 Agent Skills 的 AI

---

## 如何添加新 Skill

1. Fork 本仓库
2. 在 `skills/` 下创建新目录，放入 `SKILL.md`
3. 在新目录下创建 `README.md`（独立展示页）
4. 更新根目录 `README.md` 的表格
5. 提交 PR

---

## 许可证

MIT —— 所有 skill 均可免费使用、修改、分发。
