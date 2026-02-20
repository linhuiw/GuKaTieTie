# CLAUDE.md — GuKaTieTie 法律文件仓库

本仓库托管咕卡贴贴（GuKa TieTie）的对外法律文件，通过 GitHub Pages 公开访问，用于 App Store 提交。

---

## 公开访问 URL

| 文件 | 公开 URL |
|------|---------|
| 首页 | https://linhuiw.github.io/GuKaTieTie/ |
| 隐私政策 | https://linhuiw.github.io/GuKaTieTie/privacy.html |
| 用户协议 | https://linhuiw.github.io/GuKaTieTie/terms.html |

> App Store Connect 填写时，将上方 URL 分别填入「隐私政策网址」和「用户协议网址」字段。

---

## 仓库结构

```
GuKaTieTie/
├── CLAUDE.md          # 本文件（项目说明）
├── README.md          # 仓库说明
├── 用户协议.md         # 用户协议（Markdown 源文件）
├── 隐私政策.md         # 隐私政策（Markdown 源文件）
└── [gh-pages 分支]
    ├── index.html     # 落地页（链接至两份法律文件）
    ├── privacy.html   # 隐私政策（HTML 网页版）
    └── terms.html     # 用户协议（HTML 网页版）
```

---

## 分支说明

| 分支 | 用途 |
|------|------|
| `master` | Markdown 源文件（用户协议.md、隐私政策.md） |
| `gh-pages` | GitHub Pages 部署文件（HTML 网页，对外公开） |

---

## 更新流程

修改法律文件时，需同时更新两个分支：

1. **更新 master**：编辑 `用户协议.md` / `隐私政策.md`，commit 并 push
2. **更新 gh-pages**：对应修改 `terms.html` / `privacy.html`，push 到 `gh-pages` 分支
3. GitHub Pages 通常在 1-2 分钟内自动生效

---

## 关联主项目

主应用代码仓库：`/Users/linhuiw/Code/GuKa-Sticker`（私有）
