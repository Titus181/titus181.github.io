# titus181.github.io

《巷口大店長》的店景拜訪連結：`https://titus181.github.io/v/<拜訪碼>`。

- `404.html`：GitHub Pages 對所有找不到的路徑都會回這一頁，所以 `/v/<碼>` 由這一頁在瀏覽器裡讀 `GET https://aislerise-prod.fly.dev/v1/visits/<碼>`，顯示店名、等級和招牌字。
- `.well-known/apple-app-site-association`：讓裝了 App 的 iPhone 直接用 App 打開 `/v/*`（App 端在下一版加 Associated Domains）。
- `.nojekyll`：讓 `.well-known` 資料夾照常發布。
- 隱私權政策和聯絡方式仍在 https://titus181.github.io/aislerise-site/ 。

規格：AisleRise repo 的 `docs/design/specifications/store-visit-link-r1.md` §3 階段 2。
