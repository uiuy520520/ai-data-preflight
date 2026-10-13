# AI Data Preflight 隱私權政策 / Privacy Policy

最後更新 / Last updated：2026-10-13

## 繁體中文

### 1. 這是什麼

AI Data Preflight 是在你的電腦上，由 AI 助理（例如 Claude Code）呼叫的 skill。它在你把檔案、圖片、截圖或文字送到雲端 AI、第三方工具或其他外部對象之前，先辨識其中可識別真人的個資，並協助遮蔽。

### 2. 我們不蒐集你的內容

- 作者不蒐集、不儲存、不傳送你檢查的任何檔案、圖片或文字。
- 文字比對、OCR，以及臉孔、簽名、車牌的偵測，都在你的電腦本機執行。
- 作者沒有架設任何接收你資料的伺服器，也不使用分析或追蹤工具。
- 作者不會知道你是否使用、使用了多少次，或處理了什麼內容。

### 3. 首次使用時會連網下載的項目

為了在本機運作，下列元件會在需要時從公開來源下載。下載過程不會附上你的內容：

- Python 套件與語言模型（spaCy 模型，來自 GitHub 發行頁）
- Tesseract OCR 語言字庫（來自 GitHub `tesseract-ocr/tessdata`）
- 臉孔、車牌、簽名偵測模型（來自 GitHub 與 Hugging Face，下載後以 sha256 驗證）

這些來源各自有自己的隱私政策，連線時它們可能看到你的 IP 位址等一般連線資訊。下載後的檔案會快取在你的電腦上。

### 4. 本機產生的檔案

遮蔽後的輸出檔，以及你選擇產生的檢查報告，會寫在你指定的位置。報告可能含有被辨識出的個資片段，請自行妥善保管，用完後刪除。

### 5. 與 AI 助理及其服務商的關係

這個 skill 由 AI 助理呼叫。你在對話中提供給助理的內容，依你所使用的 AI 服務（例如 Anthropic）自己的隱私政策處理，不在本政策範圍內。這個 skill 的目的，就是在內容送出之前讓你先看過並確認。

### 6. 兒童

本 skill 不針對 13 歲以下兒童，也不蒐集任何使用者資料。

### 7. 政策變更

政策更新時，會修改頁首的日期，並保留在此倉庫的版本紀錄中。

### 8. 聯絡方式

對本政策有疑問，請到此倉庫開 Issue：<https://github.com/uiuy520520/ai-data-preflight/issues>

---

## English

### 1. What this is

AI Data Preflight is a skill that runs on your own computer, invoked by an AI assistant (such as Claude Code). Before you send a file, image, screenshot, or text to a cloud AI, a third-party tool, or anyone outside your control, it identifies information that can identify a real person and helps you redact it.

### 2. We do not collect your content

- The author does not collect, store, or transmit any file, image, or text you check.
- Text matching, OCR, and face, signature, and license-plate detection all run locally on your computer.
- The author operates no server that receives your data and uses no analytics or tracking tools.
- The author cannot tell whether you use the skill, how often, or what you process.

### 3. Downloads on first use

To work locally, the following components are downloaded from public sources when needed. Your content is not included in these downloads:

- Python packages and language models (spaCy models from GitHub releases)
- Tesseract OCR language data (from GitHub `tesseract-ocr/tessdata`)
- Face, license-plate, and signature detection models (from GitHub and Hugging Face, verified by sha256 after download)

These providers have their own privacy policies and may see ordinary connection information such as your IP address. Downloaded files are cached on your computer.

### 4. Files created locally

Redacted output files, and any report you choose to generate, are written where you specify. A report may contain fragments of the personal data that was detected. Please store it carefully and delete it when you are done.

### 5. AI assistants and their providers

This skill is invoked by an AI assistant. Content you give the assistant in conversation is handled under the privacy policy of the AI service you use (for example, Anthropic) and is outside the scope of this policy. The purpose of this skill is to let you review and confirm content before it leaves your control.

### 6. Children

This skill is not directed at children under 13 and collects no user data.

### 7. Changes

When this policy changes, the date above is updated and the change is kept in this repository's history.

### 8. Contact

For questions about this policy, open an issue: <https://github.com/uiuy520520/ai-data-preflight/issues>
