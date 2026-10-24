---
name: sync
description: 和家人同步共享 repo（pull → 顯示對方的變更 → commit → push）。當我說「同步」「sync」「拉一下最新的」「把我改的推上去」時使用。
---

# 同步

## 步驟

1. 在 repo 根目錄（`CLAUDE.md` 和 `TODO-review.md` 所在的位置）執行 `git status`，確認有沒有自己尚未 commit 的變更
2. 有未 commit 的變更 → 先 commit（訊息用英文，寫清楚改了什麼，例：`investing: update research notes for 7974`）
3. `git pull --rebase`
   - 有衝突時**停下來**，用繁體中文說明哪個檔案、雙方各改了什麼，請我決定保留哪一邊，不要自己選
4. 用 `git log` 和 `git diff` 整理**對方新增的變更**，一行一項告訴我
5. 讀取 `TODO-review.md`，有給我的未確認事項就提醒我
6. `git push`
7. 回報：已同步 / 對方的變更摘要 / 待確認事項
