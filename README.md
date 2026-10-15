# The Superpower of Kindness — 英語讀者劇場語音示範網頁

《The Superpower of Kindness》英語讀者劇場（Reader's Theater）的互動語音示範網頁：
分角色、分場景聆聽老師聲音示範，學生可錄音／上傳音檔並與示範逐字比對，錯誤單字自動高亮。

## 檔案結構

| 路徑 | 內容 |
|---|---|
| `index.html` | **精簡版**（73 句、全劇約 4 分 20 秒）— 主要使用版本 |
| `full/index.html` | 完整版（90 句、約 5 分 20 秒） |
| `docs/The_Superpower_of_Kindness_精簡版劇本.docx` | 精簡版劇本 Word（刪減處紅色刪除線標記） |

## 功能

- 首頁 Scene 1–4 按鈕：分幕聆聽
- 「播放全劇」按鈕：四幕連續播放
- 每幕的角色按鈕：只聽該角色台詞（9 個角色各配不同聲音）
- 點任一句台詞：重複聽該句；速度選單 0.75x–1.1x
- 我的練習：麥克風錄音或上傳音檔（mp3 / m4a / wav / webm）
- 比對有兩種模式：**快速比對**（Chrome 內建語音辨識，免下載，按錄音朗讀後自動比對）與**精確比對**（下載約 40MB AI 引擎，含逐字速度分析、支援上傳音檔；可先按「先下載比對引擎」課前備妥）
- 開始比對：AI 逐字比對學生與示範音檔 —
  🟠 發音待加強、🟡 速度偏慢、🔴 聽不清楚／漏讀，點單字可從該字重播示範

## 發佈到 GitHub Pages（約 2 分鐘）

1. 在 GitHub 建立新倉庫（公開 Public，Pages 免費方案需要）
2. 選「uploading an existing file」，把本專案**解壓縮後的資料夾內容**全部拖入（含 `full/` 與 `docs/` 資料夾），Commit
3. 倉庫 Settings → Pages → Source 選「Deploy from a branch」→ Branch 選 `main` / `(root)` → Save
4. 約 1 分鐘後網頁上線：`https://<你的帳號>.github.io/<倉庫名>/`
   （完整版在 `/full/`，例如 `https://<你的帳號>.github.io/<倉庫名>/full/`）

## 使用提醒

- 建議使用 **Chrome** 開啟（比對功能效果最好）
- 第一次按「開始比對」會下載 AI 語音辨識引擎（約 40 MB，需連網），之後會快取在瀏覽器
- 示範音為 AI 合成（ElevenLabs TTS），非真人錄音；比對結果是輔助參考，腔調評估建議仍由老師把關
- 每一幕可用網址深連結直接開啟：`index.html#scene-1` 到 `#scene-4`
