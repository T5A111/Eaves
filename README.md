# Eaves 簷下

> 原名 **BetterNotch**，現已改名為 Eaves，功能與資料都會自動沿用。

把 MacBook 的瀏海變成好用的工具列：暫存檔案、剪貼簿、媒體控制、系統資訊、天氣、行事曆、計時器，
滑鼠移到瀏海或點一下就展開。基於 [NotchDrop](https://github.com/Lakr233/NotchDrop) 打造。

![macOS](https://img.shields.io/badge/macOS-14.0+-blue)
![Version](https://img.shields.io/github/v/release/T5A111/Eaves?label=Version&color=green)
![License](https://img.shields.io/badge/License-MIT-green)

<a href="https://buymeacoffee.com/t5a111"><img src="https://img.shields.io/badge/☕_買杯咖啡支持我-FFDD00?style=for-the-badge&logo=buymeacoffee&logoColor=black" alt="Buy Me a Coffee"></a>

## 📥 下載安裝

📦 **[下載最新版本](https://github.com/T5A111/Eaves/releases/latest)**（`Eaves-x.x.dmg`）

1. 開啟 `.dmg`，把 **Eaves** 拖到「應用程式」資料夾。
2. 打開 Eaves，依照新手引導開啟需要的權限（都可以之後再到「系統設定」調整）。

App 已經過 Apple 公證，可以直接打開，不需要到「隱私權與安全性」手動允許。
之後的新版本會在 App 內自動通知更新。

> 從 BetterNotch 1.0 升級：App 內會自動更新，不需要重新下載。
> 從更舊的版本（v2.0 以前）升級：舊版無法自動更新，請下載新版安裝，再把舊的 BetterNotch 移到垃圾桶。
> 暫存櫃、剪貼簿與分頁設定會自動沿用。

**系統需求**：macOS 14.0 以上，Intel 或 Apple Silicon。沒有瀏海的 Mac 和外接螢幕也能使用。

## ✨ 功能

| 分頁 | 內容 |
|---|---|
| 🗂️ 暫存櫃 | 把檔案拖進瀏海暫存，拖到 AirDrop / 分享直接傳送；⌘ / Shift 多選、空白鍵快速查看、到期自動清理 |
| 📋 剪貼簿 | 文字、連結、圖片、檔案、色碼分類，釘選常用項目，⌥⌘V 快速叫出 |
| 🎵 媒體播放 | Apple Music、Spotify、瀏覽器影片都能控制；同步歌詞、即時音波、播放速度、±15 秒、切換播放來源 |
| 💻 系統資訊 | CPU、記憶體壓力、溫度、電池（充電功率、剩餘時間、健康度）、網路速度、耗用最多的 App |
| 🌤️ 天氣 | Apple 天氣資料：逐時、7 天、空氣品質、紫外線、日出日落，快下雨時提醒 |
| 📅 行事曆 | 今天與明天的行程、線上會議一鍵加入、提醒事項直接勾選完成 |
| ⏱️ 計時器 | 滾輪設定時間、最近使用、結束音效；碼表與分圈 |

- **即時動態**：充電、計時器、即將開始的會議、降雨、耳機連線等，在收合的瀏海上顯示。
- **分頁可自訂**：在 ⋯ 選單或設定中隱藏不需要的分頁、調整順序。
- **手勢**：觸控板雙指左右滑動換頁、三指滑動開關瀏海。
- 支援「減少動態效果」、VoiceOver；介面提供繁中、簡中、英、日、德、法文。

## 🔒 權限與隱私

| 權限 | 用途 |
|---|---|
| 行事曆、提醒事項 | 顯示行程與待辦事項 |
| 定位 | 取得所在地區的天氣 |
| 系統音訊錄製 | 播放音樂時的即時音波（只分析音量，不錄音、不儲存） |
| 自動化 | 控制 Spotify / Apple Music 的進度與音量 |

所有資料都只存在你的 Mac 上（`~/Library/Application Support/Eaves`），不會上傳。
App 異常結束時會詢問是否回報，由你決定要不要開啟 GitHub 回報頁。

## 🐛 問題回報

請到 [Issues](https://github.com/T5A111/Eaves/issues) 回報，附上 macOS 版本與重現步驟。

## ☕ 支持開發

覺得好用的話，歡迎 [請我喝杯咖啡](https://buymeacoffee.com/t5a111)，這是我持續更新的動力！

## 📄 授權與致謝

MIT License。
- 原始專案：[NotchDrop](https://github.com/Lakr233/NotchDrop) © 2024 Lakr Aream
- Eaves（原 BetterNotch）：© 2025–2026 SAI T

天氣資料由 [Apple 天氣](https://weatherkit.apple.com/legal-attribution.html) 提供，空氣品質由 [Open-Meteo](https://open-meteo.com) 提供，
歌詞由 [LRCLIB](https://lrclib.net) 提供。
