# Lawrence Bai

海大資工所碩士生。做手語辨識與語音系統，從資料前處理、模型訓練到部署都自己走一遍。

> 這個頁面是倉庫索引。多數倉庫的 GitHub description 欄位是空的或跟倉庫名重複，
> 所以每個專案實際在做什麼，寫在這裡。

## 研究主線

| 倉庫 | 說明 |
| --- | --- |
| [SignAR](https://github.com/NextBai/SignAR) | 手語影片識別與翻譯服務。上傳手語影片，經 MediaPipe 裁切、ResNet + 骨架特徵滑動窗口、BiGRU 推論，再由 LLM 組句並翻譯。15 詞詞彙，已部署上線。 |
| [Multi_SignView](https://github.com/NextBai/Multi_SignView) | Rokid 眼鏡上的多模態手語識別**設計文件與特徵資料**。目前是技術構想與前置資料，尚無可執行程式。 |
| [AFAD_Age_Gender_Identify](https://github.com/NextBai/AFAD_Age_Gender_Identify) | 用 MobileNet_V3 在 AFAD 亞洲人臉資料集上做年齡估計與性別分類。注意：`dataset.zip` 只有 Git LFS 指標，物件不在 GitHub 上，複製後需自行取得 AFAD 原始資料。 |
| [2026_AIoT](https://github.com/NextBai/2026_AIoT) | ECAPA-TDNN 聲紋辨識搭配 IoTtalk 邊緣聯動，含雙門檻 VAD 與頻譜減法降噪的消融實驗。 |

## 作品與演示

| 倉庫 | 說明 |
| --- | --- |
| [realtime-translator-avatar-live](https://github.com/NextBai/realtime-translator-avatar-live) | 按住說話的即時翻譯介面，橋接瀏覽器麥克風與 Gemini Live API，多語言角色以音量驅動口型同步。 |
| [neonsynth](https://github.com/NextBai/neonsynth) | 單檔 HTML 的 Web Audio 合成器加 16 步鼓機，無構建流程、無相依套件。 |
| [health_tracker](https://github.com/NextBai/health_tracker) | Flask 姿態與血壓追蹤網站，含 MediaPipe Pose 擷取與一個查詢用 MCP server。尚在早期，沒有 README。 |
| [messengerbot](https://github.com/NextBai/messengerbot) | 部署到 Render 的 Facebook Messenger Bot 最小範例模板。 |
| [BloomWareApp](https://github.com/NextBai/BloomWareApp) | 語音助理「小花」：聲紋登入、情感分析、MCP 生活功能、Firestore 長期記憶。銘傳大學「槓上開發」**團隊**專題，授權歸屬待團隊確認。 |

## 課程

| 倉庫 | 說明 |
| --- | --- |
| [genai-w9-ai-ledger](https://github.com/NextBai/genai-w9-ai-ledger) | 生成式 AI 課程第九週：純前端記帳網站，含 `AGENTS.md` 協作規則。 |
| [genai-w9-llm-wiki-site](https://github.com/NextBai/genai-w9-llm-wiki-site) | 生成式 AI 課程第九週：LLM Wiki 入門互動靜態網站，含論文筆記與自我測驗。 |
| [genai-w10-llm-wiki](https://github.com/NextBai/genai-w10-llm-wiki) | 生成式 AI 課程第十週：五篇 agent 論文的知識庫與教學簡報。 |
| [2025_Introduction_to_Interaction](https://github.com/NextBai/2025_Introduction_to_Interaction) | 互動概論選修：Arduino 與 Processing 的逐週練習程式。 |
| [2024graphicsb](https://github.com/NextBai/2024graphicsb) | 2024 電腦圖學二乙組 OpenGL / GLUT 分週程式，含課程提供之程式骨架。 |
| [2022cce](https://github.com/NextBai/2022cce) | 2022 C 語言課程的逐週課堂範例與操作筆記，內容含授課材料，非個人原創。 |

## 授權

- 純個人程式碼的專案採 **MIT**。
- 含第三方資料或他人音影像的倉庫（`SignAR`、`Multi_SignView`、`AFAD_Age_Gender_Identify`、`2026_AIoT`）採
  **程式碼 MIT、資料與權重不在授權範圍**的寫法。
- 課程倉庫未加授權：作業與課堂材料可能不屬於單一著作人。
- 另有進行中的私有倉庫，不在此列。
