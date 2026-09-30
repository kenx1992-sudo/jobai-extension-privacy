---
title: JobAI - Jobby 求職助手 — Privacy Policy
description: Privacy policy for the JobAI Chrome extension
---

# JobAI – Jobby 求職助手 — Privacy Policy / 私隱政策

_Last updated: 2026-09-30 · Extension version 3.0.0_

## English

**JobAI – Jobby 求職助手** ("the Extension") is a side panel that moves data between the job page you are looking at and **your own JobAI account** (`jobai.hk`), so you do not have to retype it.

There is no JobAI-operated analytics, no advertising, and no third-party data sharing of any kind.

---

### 1. Connecting to your JobAI account (pairing)

The Extension never sees your JobAI password or your JobAI login session. Instead, you get a one-time **pairing code** on `jobai.hk` ("Connect device") and type it into the side panel. The Extension exchanges that code for a **device credential** that is stored locally in your browser (`chrome.storage.local`).

That credential is not your login. It can only do three things: read the profile fields used for form filling, save a job to your account, and handle the application tasks you queued. It expires on its own and you can revoke it at any time on `jobai.hk`; "Unpair on this computer" in the side panel deletes the local copy. It is only ever sent to `jobai.hk` as the standard `Authorization` header.

### 2. Knowing which page you are on

While the side panel is open, the Extension looks at the address of your **active tab** so it can show which site you are on and whether one of your queued applications belongs to that page. This check happens inside your browser. The address is not recorded and is not sent anywhere, except in the two cases below where you click a button.

### 3. Saving a job listing

**What is read.** On a job detail page on `linkedin.com`, `jobsdb.com`, `ctgoodjobs.com` or `ctgoodjobs.hk`, and **only when you click "Save to JobAI" / "存呢份工入 JobAI"**, the Extension reads the job details visible on that page: job title, company, location, salary, job description, and the page URL.

**Where it goes.** Those details are sent to your JobAI account on `jobai.hk` and stored as a job record **under your own account**. Nothing is sent anywhere else.

### 4. Filling an application form

**What is read.** When you click **"幫我填呢頁嘅申請表" / "Fill this application form"** — and only then — the Extension fetches **your own** profile fields from `jobai.hk`: name, email address, phone number, current job title, current employer and skills.

**Site access.** Before filling a site for the first time, Chrome asks you to allow the Extension on that site. You can remove that access at any time in Chrome's extension settings.

**Where it goes.** Those values are written into **empty** input fields on the tab you are looking at. They go from your JobAI account into the form in front of you and nowhere else.

**Limits.** The Extension only touches the active tab when you click. It never overwrites a field that already has a value, never fills password, payment, file-upload, checkbox, radio or drop-down fields, leaves sensitive questions (for example ID number, date of birth, gender or expected salary) for you, and **never submits a form**. You always review and submit it yourself.

### 5. Recording a confirmation page

After **you** have submitted an application, you can click **"我已提交，記錄確認頁" / "I've submitted, record the confirmation page"**. Only then does the Extension read the text of that confirmation page. If it finds a confirmation message (for example "Thank you for applying"), it sends up to 1,000 characters around that message, together with the page address, to your JobAI account as a record of that application. It is marked as your own device's observation, not as a verified result.

### 6. Data we collect, and why

| Data | Purpose | Sent to |
|---|---|---|
| Job title, company, location, salary, description, page URL | Save the listing to your account | Your JobAI account (`jobai.hk`) |
| Your name, email, phone, job title, employer, skills | Fill an application form you opened | The form on your active tab only |
| Confirmation page text (up to 1,000 characters) and address | Record that you submitted an application | Your JobAI account (`jobai.hk`) |
| Device credential | Authenticate this browser | `jobai.hk` (Authorization header); stored locally |
| Active tab address | Show the current site and match your queued applications | Not sent; checked inside your browser |

We do **not** collect health data, financial or payment data, personal communications, device location, browsing history, keystrokes, or mouse/scroll activity. We do **not** sell or transfer any of this data to third parties, and we do not use it for advertising, creditworthiness or lending.

### 7. Retention and deletion

Saved jobs, application records and your profile live in your JobAI account; delete them any time on `jobai.hk`. The Extension itself stores only the device credential on your computer; unpairing or uninstalling the Extension deletes it.

### 8. Contact

Questions or a data request: contact us at https://jobai.hk/contact.

---

## 中文

**JobAI – Jobby 求職助手**（「本擴充功能」）係一個側邊欄，喺你眼前嗰個職位頁同**你自己嘅 JobAI 帳戶**（`jobai.hk`）之間搬資料，等你唔使重複打字。

冇任何分析追蹤、冇廣告、亦冇任何形式嘅第三方資料分享。

---

### 1. 連接你嘅 JobAI 帳戶（配對）

本擴充功能永遠唔會見到你嘅 JobAI 密碼或者登入狀態。你喺 `jobai.hk`「連接電腦」攞一個一次性**配對碼**，打入側邊欄；本擴充功能用佢換一個**裝置憑證**，存喺你瀏覽器本機（`chrome.storage.local`）。

呢個憑證唔係你嘅登入，只做得到三件事：讀填表用嘅個人資料、將職位存入你帳戶、處理你自己排嘅投遞工作。佢會自己過期，你亦可以隨時喺 `jobai.hk` 撤銷；側邊欄嘅「喺呢部電腦取消配對」會刪走本機副本。佢只會作為標準 `Authorization` 標頭送去 `jobai.hk`。

### 2. 知道你喺邊一頁

側邊欄打開嗰陣，本擴充功能會睇你**當前分頁**嘅網址，用嚟顯示你喺邊個網站，同埋對返你排咗嘅投遞工作係咪屬於呢一頁。呢個比對喺你瀏覽器入面做，網址唔會被記錄，亦唔會送去任何地方，除咗下面兩個要你親手撳掣嘅情況。

### 3. 儲存職位

**讀咩。** 喺 `linkedin.com`、`jobsdb.com`、`ctgoodjobs.com` 或 `ctgoodjobs.hk` 嘅職位詳情頁，**淨係喺你撳「Save to JobAI」或者「存呢份工入 JobAI」嗰一刻**，本擴充功能會讀取該頁可見嘅職位資料：職位名、公司、地點、薪酬、職位描述、網址。

**去邊。** 呢啲資料送去你喺 `jobai.hk` 嘅 JobAI 帳戶，以**你自己嘅帳戶**存低。唔會送去其他任何地方。

### 4. 幫你填申請表

**讀咩。** 當你撳**「幫我填呢頁嘅申請表」**，亦淨係嗰一刻，本擴充功能會由 `jobai.hk` 攞返**你自己嘅**資料：姓名、電郵、電話、現職職位、現職公司、技能。

**網站權限。** 第一次喺某個網站填表之前，Chrome 會問你准唔准本擴充功能用嗰個網站。你隨時可以喺 Chrome 擴充功能設定度收返。

**去邊。** 呢啲值會填入你眼前嗰個分頁入面**仲係空白**嘅輸入欄。資料由你嘅 JobAI 帳戶去到你面前嗰張表，唔會去第二度。

**限制。** 只會掂你撳嗰陣個當前分頁；已經有內容嘅欄位唔會覆蓋；密碼、付款、檔案上載、剔選格、單選、下拉選單一律唔掂；敏感問題（例如身分證號碼、出生日期、性別、期望薪金）留返畀你自己填；**永遠唔會幫你㩒交表**，一定係你自己睇完再交。

### 5. 記錄確認頁

**你自己**交咗申請之後，可以撳**「我已提交，記錄確認頁」**。淨係嗰一刻，本擴充功能先會讀嗰個確認頁嘅文字。如果搵到確認字眼（例如「Thank you for applying」），會將嗰段字前後最多 1,000 個字元，連同頁面網址，送去你嘅 JobAI 帳戶做呢份申請嘅紀錄。紀錄會標明係你部機觀察到，唔係經平台核實嘅結果。

### 6. 我哋收集乜、點解

| 資料 | 用途 | 送去邊 |
|---|---|---|
| 職位名、公司、地點、薪酬、描述、網址 | 將職位存入你帳戶 | 你嘅 JobAI 帳戶（`jobai.hk`） |
| 你嘅姓名、電郵、電話、職位、公司、技能 | 填你自己打開嗰張申請表 | 只限你當前分頁嗰張表 |
| 確認頁文字（最多 1,000 字元）同網址 | 記錄你交咗申請 | 你嘅 JobAI 帳戶（`jobai.hk`） |
| 裝置憑證 | 認證呢個瀏覽器 | `jobai.hk`（Authorization 標頭）；本機儲存 |
| 當前分頁網址 | 顯示你喺邊個網站、對返你排咗嘅投遞工作 | 唔會送出；只喺你瀏覽器入面比對 |

我哋**唔會**收集健康資料、財務或付款資料、私人通訊、裝置位置、瀏覽紀錄、按鍵紀錄或滑鼠／捲動行為。我哋**唔會**將任何資料出售或轉交第三方，亦唔會用嚟做廣告、信用評估或借貸用途。

### 7. 保留同刪除

已儲存嘅職位、申請紀錄同你嘅個人檔案都喺你嘅 JobAI 帳戶入面，隨時喺 `jobai.hk` 自己刪除。本擴充功能本身只喺你部機存住個裝置憑證；取消配對或者移除本擴充功能就會一併刪走。

### 8. 聯絡

查詢或資料要求：https://jobai.hk/contact
