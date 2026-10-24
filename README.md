# claude-shared（Maozai ＋ 家人 共享）

## 第一次設定（家人）
1. 接受 GitHub 的邀請信
2. clone 並建立自己的設定：

```powershell
cd $HOME
git clone https://github.com/<Maozai的帳號>/claude-shared.git
cd claude-shared
copy CLAUDE.local.md.example CLAUDE.local.md
notepad CLAUDE.local.md
```

## 使用方式
```powershell
cd $HOME\claude-shared\investing      # 或 side-business
claude
```

- 開始時、結束時都說 **「同步」**
- 需要 Maozai 判斷的事 → 請 Claude 寫進 `TODO-review.md`
- 不要放：帳號密碼、證券帳號、My Number、證件

| 資料夾 | 可以做的事 |
|---|---|
| `investing/` | `/stock-research` 個股研究、`/portfolio-review` 月度檢討 |
| `side-business/` | `/coconara-proposal` 案件評估・提案草稿、`/delivery-check` 交付前檢查 |
