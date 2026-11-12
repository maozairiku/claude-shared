# NVDA 進場・離場分析（2026-11-12）

> 執行者：Maozai（Claude Code 整理）／資料時間：2026-11-12 美股盤中〜收盤前後
> 這是條件分析，不是買賣建議。

## 結論
- **前提修正**：CEO 問題造成的是**下跌**，不是上漲。10 月初高點到 11/11 已跌約 27%，11/12 黃仁勳辭任報導後再跌約 10%，創 52 週新低
- `CLAUDE.md` 的風險規則（集中度・停損）**尚未填寫** → 無法逐條檢查 ✅/❌
- 現價（約 $151–156，未確認收盤）位於下方估值區間「偏低〜合理」，但 **5 天內有財報（11/17）＋國會非公開聽證（11/18）**，事件風險非常高
- 「買了永遠不賣」= 沒有離場條件，與本工作區規則（必須有停損與檢討條件）衝突

## 最新事件（近 3 個月）
| 日期 | 事件 | 出處 |
|---|---|---|
| 2026-08-26 | Q2 FY27：營收 $96.2B（YoY +106%）、資料中心 $89.0B（+117%）、毛利率 75.0%；Q3 指引 $108B ±2%（不含中國資料中心） | [NVIDIA IR](https://investor.nvidia.com/news/press-release-details/2026/NVIDIA-Announces-Financial-Results-for-Second-Quarter-Fiscal-2027/) |
| 2026-11-09 | 與被情報機關指為中國間諜的女性有關的報導，股價 −4% | [CNBC](https://www.cnbc.com/2026/11/09/nvidia-jensen-huang-chinese-spy-investigation.html) |
| 2026-11-11 | 董事會調查；收盤時距 10 月初高點 −27% | [CNN](https://edition.cnn.com/2026/11/11/investing/nvidia-stock-jensen-huang) |
| 2026-11-12 | 黃仁勳辭任 CEO 與董事，CFO Colette Kress 為暫代 CEO；股價約 −10%，市值跌破 $4T | [CNBC](https://www.cnbc.com/2026/11/12/nvidia-nvda-jensen-huang-second-affair.html)、[CNN live](https://www.cnn.com/2026/11/11/business/live-news/nvidia-jensen-huang-investigation-fallout) |
| 2026-11-17 | 財報（盤後），公司表示照常 | 同上 |
| 2026-11-18 | 眾議院三位委員長要求黃仁勳出席非公開會議 | 同上 |

※ 辭任消息：CNBC・CNN 報導；8-K 原文**未直接確認**。

## 股價・技術面（僅供參考）
| 項目 | 數值 | 出處・日期 |
|---|---|---|
| 11/11 收盤 | $173.73 | [Yahoo Finance](https://finance.yahoo.com/markets/stocks/articles/wsj-says-nvidia-preparing-oust-124700050.html), 11/12 |
| 11/12 盤中 | 低至約 $151（−13%） | [TokenPost](https://www.tokenpost.com/news/investing/55512) |
| 11/12 收盤 | $155.87（**未確認**，僅資料頁） | [Trading212](https://www.trading212.com/trading-instruments/invest/NVDA.US) |
| 52 週高 / 舊低點 | $243.37 / $164.27（已跌破） | [Investing.com](https://www.investing.com/equities/nvidia-corp), 11/11 |
| 200 日均線 | 約 $212.65 | [Investing.com](https://www.investing.com/equities/nvidia-corp-technical) |
| 50 日均線 | 未確認 | |

- 壓力：$164（舊 52 週低點，跌破後轉為壓力）、$174（事件前收盤）、$205–213（200 日線）
- 支撐：$151 前後（11/12 盤中低點）；再往下無明確參考

## 估值
- Trailing P/E 21.8x（[Investing.com](https://www.investing.com/equities/nvidia-corp)，11/11 價格基準；單一來源）
- 粗估年化 EPS：Q2 non-GAAP $2.22 × 4 ≈ $8.9（另有來源寫 GAAP $2.46，數字有分歧）
- 過去 5 年 P/E 區間、同業（AMD・Broadcom）P/E：**未確認**

| 區間 | 計算 | 價格 |
|---|---|---|
| 偏低 | 8.9 × 14x（領導層折價＋成長放緩） | 約 $125 |
| 合理 | 8.9 × 18–22x | 約 $160–196 |
| 偏高 | 8.9 × 25x 以上 | $220 以上 |

→ 現價 $151–156 在「偏低〜合理下緣」。但若 11/17 指引下修，EPS 本身會變，區間跟著下移。

## 分析師（他人的意見）
- MarketBeat（11/12）：Moderate Buy，平均目標 $298.18；Buy/Strong Buy 46、Hold 9 — [來源](https://www.marketbeat.com/instant-alerts/price-nvidia-nasdaq-nvda-reaches-new-1-year-low-following-analyst-downgrade-2026-11-12/)
- 其他彙整：$318.85（[DailyPolitical](https://www.dailypolitical.com/2026/11/09/nvidia-corporation-nasdaqnvda-stock-has-consensus-price-target-of-318-85.html), 11/09）、$240.11（[Nemo](https://explore.nemo.money/en/stocks/NVDA)，日期不明）
- **正在下修**：Bernstein $400 → $200、Cantor $350 → $250（11/12）
- 判讀：平均值多半還沒反映辭任事件，接下來幾天可能大幅下修；分歧大

## 情境表
| 情境 | 價格區間 | 需要發生的條件 |
|---|---|---|
| 樂觀 | $195–213 | 財報達標且 Q4 指引續增、接任 CEO 人選明確、間諜疑雲沒有波及出口許可或政府合作 |
| 基準 | $150–180 | 財報不差，但領導層不確定性折價持續數月 |
| 悲觀 | $120–150 | 指引下修或客戶延後採購、國安調查擴大（出口限制・政府合約）、關鍵人才流失 |

## 離場參考
- 獲利了結：基準上緣 $180、200 日線 $205–213；分析師平均 $298 目前可信度低
- 停損：進場價 −15%（範例規則，**請填入自己的規則**）；例 $155 進場 → 約 $132
- 重新檢討觸發：Q4 指引低於 Q3 實績、資料中心營收 QoQ 轉負、接任者遲未決定、美國政府對 NVIDIA 本身的調查或出口限制

## 匯率
- 以日圓投資時，報酬 = 股價變動 × USD/JPY 變動。日圓升值 10% 會吃掉約 10% 的美元報酬
- 目前 USD/JPY：**未確認**

## 主要風險 3 點
1. **事件集中**：11/17 財報＋11/18 聽證，短期波動可能很大
2. **關鍵人物＋國安疑雲**：不只是醜聞，涉及「中國間諜」可能影響出口許可・政府關係
3. **AI 資本支出循環**：營收 9 成以上來自資料中心，大客戶減少 capex 時衝擊直接

## 未確認
- 11/12 正式收盤價、8-K 原文、50 日均線、5 年 P/E 區間、同業估值、USD/JPY、forward P/E

以上是條件分析，最後判斷請自行決定。
