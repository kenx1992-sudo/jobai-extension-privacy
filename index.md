---
title: JobAI - Save Job Listings — Privacy Policy
description: Privacy policy for the JobAI Chrome extension
---

# JobAI – Save Job Listings — Privacy Policy / 私隱政策

_Last updated: 2026-08-07 · Extension version 2.1.2_

## English

**JobAI – Save Job Listings** ("the Extension") does one thing: it moves job data between the job page you are looking at and **your own JobAI account** (`job-ai-leap.base44.app`), so you do not have to retype it.

There is no JobAI-operated analytics, no advertising, and no third-party data sharing of any kind.

---

### 1. Saving a job listing

**What is read.** When you are on a job detail page on `linkedin.com`, `jobsdb.com`, `ctgoodjobs.com` or `ctgoodjobs.hk`, and **only at the moment you click "Save to JobAI"**, the Extension reads the job details visible on that page: job title, company, location, salary, job description, and the page URL.

**Where it goes.** Those details are sent directly to the JobAI backend (`app.base44.com`) and stored as a job record **under your own JobAI account**, exactly as if you had typed it into the JobAI app yourself. Nothing is sent anywhere else.

**What is not read.** The Extension does not read pages on any other website, does not record which pages you visit, and does not run in the background collecting anything.

### 2. Autofilling an application form

**What is read.** When you click **"自動填申請表" / "Autofill application form"** in the Extension's popup — and only then — the Extension fetches **your own** profile from your JobAI account: your name, email address, phone number, city/location, current job title, current employer, and skills.

**Where it goes.** Those values are written into **empty** input fields on the tab you are currently looking at, matched by the field's label, placeholder, name or id. The data goes from your JobAI account into the form in front of you and nowhere else — it is not sent to us or to any third party.

**Limits.** The Extension only ever touches the one tab that is active when you click. It never fills a field that already has a value, never fills password, payment, file-upload, checkbox or radio fields, and **never submits a form** — you always review and submit it yourself.

### 3. Your JobAI login

The Extension does not ask for your password and does not use any shared API key. A small script on `job-ai-leap.base44.app` reads the session token of the JobAI account **you are already signed in to**, and stores it locally in your browser (`chrome.storage.local`).

That token is used for one purpose: to authenticate requests to your own JobAI backend as you. It never leaves your browser except as the standard `Authorization` header sent to `app.base44.com`.

### 4. Data we collect, and why

| Data | Purpose | Sent to |
|---|---|---|
| Job title, company, location, salary, description, page URL | Save the listing to your account | Your JobAI account (`app.base44.com`) |
| Your name, email, phone, city, job title, employer, skills | Fill an application form you opened | The form on your active tab only |
| Your JobAI session token | Authenticate as you | `app.base44.com` (Authorization header); stored locally |

We do **not** collect health data, financial or payment data, personal communications, device location, browsing history, keystrokes, or mouse/scroll activity. We do **not** sell or transfer any of this data to third parties, and we do not use it for advertising, creditworthiness or lending.

### 5. Retention and deletion

Saved jobs and your profile live in your JobAI account — delete them any time inside the JobAI app. The Extension itself stores only the session token on your device; uninstalling the Extension deletes it.

### 6. Contact

Questions or a data request: contact us through the JobAI app at https://job-ai-leap.base44.app.

---

## 中文

**JobAI – Save Job Listings**（「本擴充功能」）淨係做一件事：喺你眼前嗰個職位頁同**你自己嘅 JobAI 帳戶**（`job-ai-leap.base44.app`）之間搬資料，等你唔使重複打字。

冇任何分析追蹤、冇廣告、亦冇任何形式嘅第三方資料分享。

---

### 1. 儲存職位

**讀咩。** 當你喺 `linkedin.com`、`jobsdb.com`、`ctgoodjobs.com` 或 `ctgoodjobs.hk` 嘅職位詳情頁，**而且淨係喺你撳「Save to JobAI」嗰一刻**，本擴充功能會讀取該頁可見嘅職位資料：職位名、公司、地點、薪酬、職位描述、網址。

**去邊。** 呢啲資料直接送去 JobAI 後端（`app.base44.com`），以**你自己嘅帳戶**存低，同你喺 JobAI app 入面自己打一次完全一樣。唔會送去其他任何地方。

**唔會讀咩。** 唔會讀其他網站嘅頁面、唔會記錄你去過邊啲網頁、亦唔會喺背景不斷收集任何嘢。

### 2. 自動填申請表

**讀咩。** 當你喺 extension 彈窗撳**「自動填申請表」**——亦淨係嗰一刻——本擴充功能會由你自己嘅 JobAI 帳戶攞返**你自己嘅**檔案：姓名、電郵、電話、城市／地區、現職職位、現職公司、技能。

**去邊。** 呢啲值會填入你**當前分頁**嗰個表格入面**仲係空白**嘅輸入欄（按欄位嘅 label、placeholder、name 或 id 配對）。資料由你嘅 JobAI 帳戶去到你面前嗰張表，唔會去第二度——唔會送俾我哋，亦唔會送俾任何第三方。

**限制。** 只會掂你撳嗰陣個 active 分頁；已經有內容嘅欄位唔會覆蓋；密碼、付款、檔案上載、checkbox、radio 一律唔掂；**永遠唔會幫你㩒交表**——一定係你自己睇完再交。

### 3. 你嘅 JobAI 登入

本擴充功能唔會問你攞密碼，亦冇用任何共用 API key。喺 `job-ai-leap.base44.app` 上有一段小 script，讀取**你已經登入緊**嗰個 JobAI 帳戶嘅 session token，存喺你瀏覽器本機（`chrome.storage.local`）。

呢個 token 只有一個用途：以你嘅身分向你自己嘅 JobAI 後端認證。除咗作為標準 `Authorization` 標頭送去 `app.base44.com`，唔會離開你部瀏覽器。

### 4. 我哋收集乜、點解

| 資料 | 用途 | 送去邊 |
|---|---|---|
| 職位名、公司、地點、薪酬、描述、網址 | 將職位存入你帳戶 | 你嘅 JobAI 帳戶（`app.base44.com`） |
| 你嘅姓名、電郵、電話、城市、職位、公司、技能 | 填你自己打開嗰張申請表 | 只限你當前分頁嗰張表 |
| 你嘅 JobAI session token | 以你身分認證 | `app.base44.com`（Authorization 標頭）；本機儲存 |

我哋**唔會**收集健康資料、財務或付款資料、私人通訊、裝置位置、瀏覽紀錄、按鍵紀錄或滑鼠／捲動行為。我哋**唔會**將任何資料出售或轉交第三方，亦唔會用嚟做廣告、信用評估或借貸用途。

### 5. 保留同刪除

已儲存嘅職位同你嘅個人檔案都喺你嘅 JobAI 帳戶入面，隨時喺 JobAI app 自己刪除。本擴充功能本身只喺你部機存住個 session token；移除 extension 就會一併刪走。

### 6. 聯絡

查詢或資料要求：透過 JobAI app 聯絡我哋 https://job-ai-leap.base44.app。
