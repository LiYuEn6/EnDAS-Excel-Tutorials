# EnDAS Excel Tutorials：環境數據處理實戰教學

[![Status: Active](https://img.shields.io/badge/Status-Active-brightgreen.svg)]()
[![Target: Environmental Engineering](https://img.shields.io/badge/Domain-Environmental%20Engineering-blue.svg)]()

## 專案簡介
本儲存庫包含「**環境數據 Excel 實作教學**」系列文章的官方範例檔案 (`.ods`) 與原始開源數據集 (`.csv`)。

在環境工程與環評顧問領域中，數據清理 (Data Cleaning) 往往佔據了 80% 的工作時間。本專案旨在提供一系列具備高度實用性的 Excel 模板與操作 SOP，協助從業人員快速解決常見的資料正規化痛點，如：格式錯位、ND 值處理、異質數據對齊等。

> **核心理念**：拒絕垃圾進、垃圾出 (Garbage in, garbage out)。在進行任何環境統計與繪圖前，建立嚴謹的 QA/QC 資料盤點標準。

---

## 📂 教學系列地圖 (Roadmap)

本專案對應於 Dev.to 與 Instagram 發布的教學系列，建議搭配文章服用以取得最佳學習效果。

* **主題一：如何一秒揪出環境檢測數據中的缺值與異常代碼**
    * 📝 [Dev.to 文章連結](#) | 📱 [IG 貼文連結](#)
    * 📁 範例檔：`Excel01_CODiS數據原始檔案.csv`、`Excel01_環境部水質數據原始檔案.ods` (包含中央氣象署 CODiS 與環境部水質 OpenData )
* **主題二：別讓「<0.05」毀了你的統計圖表，ND 值的 Excel 轉換技巧**
    * 📝 [Dev.to 文章連結](#) | 📱 [IG 貼文連結](#)
    * 📁 範例檔：`Excel02_環境部水質數據原始檔案.xlsx`
* **主題三：政府公開資料的惡夢，民國年與季別格式的自動轉換術**
    * 📝 [Dev.to 文章連結](#) | 📱 [IG 貼文連結](#)
    * 📁 範例檔：`Demo_Topic3.xlsx`
* **主題四：保持資料潔癖，感測器極端突波與重複數據的清理法**
    * 📝 [Dev.to 文章連結](#) | 📱 [IG 貼文連結](#)
    * 📁 範例檔：`Demo_Topic4.xlsx`
* **主題五：高頻感測器 vs 人工採樣，如何完美對齊異質時間軸？**
    * 📝 [Dev.to 文章連結](#) | 📱 [IG 貼文連結](#)
    * 📁 範例檔：`Demo_Topic5.xlsx`
* **主題六：角度還是方位？找出最頻風向！**
    * 📝 [Dev.to 文章連結](#) | 📱 [IG 貼文連結](#)
    * 📁 範例檔：`Demo_Topic6.xlsx`

*(註：文章連結將隨著教學發布逐步更新)*

---

## 🚀 如何使用本專案檔案

1.  點擊上方列表中對應的 `.ods` 或 `.csv` 檔案。
2.  在檔案預覽頁面右上方，點擊 **「Download raw file」** (向下箭頭圖示) 即可下載原始檔案。
3.  **環境需求**：建議使用 Microsoft Excel 2016 或 Microsoft 365 版本，以確保所有公式 (如 `FILTER`, `XLOOKUP`) 能正常執行。

---

## 🛠 關於 EnDAS (Environmental Data Analysis System)

雖然本系列教學以 Excel 作為切入點，但當處理十萬筆等級的高頻微型感測器數據或 CEMS 連續監測資料時，Excel 常面臨效能崩潰與缺乏資料可稽核性 (Auditability) 的極限。

**EnDAS** 是一款正在開發中的環境數據自動化清理 Web App (基於 Python/Pandas/Streamlit)。它旨在取代耗時的傳統 Excel 手工清理流程，提供一鍵式的數據轉換、品質過濾與標準化報告產出。

如果你對自動化處理環境數據感興趣，歡迎追蹤我的社群平台獲取最新開發進度。

## 聯絡與追蹤
* **Instagram**: [@arne.env](https://www.instagram.com/arne.env/)
* **Dev.to**: [阿恩 Arne｜ Environmental Enginee](https://dev.to/arne_env)
