# 足球轉播看板

網址：<https://ryan81127.github.io/football-board/football/>

原本放在 `amway-life-game` 專案的 `football/`，2026-11 搬到這個獨立專案，和 Amway 遊戲完全分開。

- `football/`：看板本體
- `shared/`：看板共用元件（球衣、口播、跟播、單區模式）
- `tools/probe.js`、`.github/workflows/probe.yml`：手動查 ESPN 賽程
- `.github/workflows/snapshot.yml`：每 10 分鐘把賽前預測與滾球快照存到 `snap` 分支
- 推上 `main` 會自動部署到 GitHub Pages
