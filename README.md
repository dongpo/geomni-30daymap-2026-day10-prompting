# Day 10 — Prompting only：一份提示詞，三個地圖實作

[公開入口：地圖與可複製提示詞](https://dongpo.github.io/geomni-30daymap-2026-day10-prompting/)

[完整讀者測試提示詞](PROMPT.md)

| 來源 | 原始HTML |
|---|---|
| Gemini（使用者提供） | [map_gemini.html](map_gemini.html) |
| Claude（使用者提供） | [map_claude.html](map_claude.html) |
| ChatGPT（本聊天製作版本） | [map_chatgpt.html](map_chatgpt.html) |

下載所選 HTML，使用瀏覽器開啟並保持網路連線。GitHub 檔案頁顯示原碼，不是執行地圖；已啟用 GitHub Pages，可由上方公開入口直接操作三張地圖。

## 來源與比較範圍

Gemini、Claude 檔案由使用者提供，按原始位元組保存；ChatGPT 版亦原樣保存。SHA256SUMS.json 記錄三份原檔校驗碼。沒有替任何模型修正程式。

PROMPT.md 是本聊天最後提供、讓使用者拿去測試的完整提示詞。ChatGPT 地圖在這份整理後的提示詞之前已經製作並經工具驗收，不能當成三個模型在相同條件下的一次生成評測。Gemini、Claude 的確切模型版本、生成過程及修訂次數未取得；本次上傳不代表已驗收它們的功能或正確性。

PROMPT.html 現指向入口頁的完整提示詞，確保 ChatGPT 原檔中的連結仍可使用；早期頁保留為 PROMPT-early.html。PROMPT.md 為讀者測試完整版本。map.html 是 ChatGPT 原檔副本。

三份地圖使用動態網路資料；讀取時間不同，筆數與內容可能不同。來源 USGS 地震 GeoJSON、Natural Earth 簡化陸地輪廓。資料供應方的條款與限制依各原始來源；不將陸地資料的 public-domain 聲明延伸為整個儲存庫的軟體授權。

- https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php
- https://www.naturalearthdata.com/about/terms-of-use/

這是地圖製作與讀者測試紀錄，不是地震預測、警報或風險評估。
