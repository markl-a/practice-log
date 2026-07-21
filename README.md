# practice-log — 每日刷題打卡（可驗證版）

公開頁面：**https://markl-a.github.io/practice-log/**

## 每日額度

- LeetCode **背 2 題**（當天首解＋隔天盲寫）
- Codility 1 題、HackerRank 1 題

## 每天三個動作

1. 解題，拿到平台的**提交連結**（LeetCode submission / Codility 證書 / HackerRank submission——都有時間戳，造不了假）
2. 在 `log.json` 的 `days` 加一筆（格式照現有範例）：
   - `kind`：`首解`｜`盲寫`｜`複習`
   - `notes`：三行心法（不變量／複雜度／我會錯的點）——盲寫時要能默出來
3. `git add -A && git commit -m "d0722: LC206 首解18min + Codility L4" && git push`

## 驗證機制（給抽查的前同事）

- **平台連結**＝當天真的有解（平台時間戳）
- **commit 時間軸**＝頁面下方自動抓 GitHub API，首解與盲寫差一天、時間變短，偽造成本比誠實做還高
- **每週抽查**：隨機挑一題已標 ✅盲寫 的題，視訊 15 分鐘現場盲寫＋講三行心法
