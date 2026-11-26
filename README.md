# 運動轉播看板（足球、籃球）

- 足球：<https://ryan81127.github.io/football-board/football/>
- 籃球：<https://ryan81127.github.io/football-board/basketball/>

原本放在 `amway-life-game` 專案的 `football/`，2026-11 搬到這個獨立專案，和 Amway 遊戲完全分開。

- `football/`：足球看板
- `basketball/`：籃球看板（NBA、韓籃甲、日本 B 聯賽、澳女聯、FIBA），2026-11 從 amway-life-game 的歷史版本復原
- `shared/`：看板共用元件（球衣、口播、跟播、單區模式）
- `tools/probe.js`、`.github/workflows/probe.yml`：手動查 ESPN 賽程
- `.github/workflows/snapshot.yml`：每 10 分鐘把足球（`snap/`）與籃球（`bsnap/`）的賽前預測與滾球快照存到 `snap` 分支
- 推上 `main` 會自動部署到 GitHub Pages
