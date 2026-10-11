# PCDoctor user guide

**PCDoctor** is a free Windows app from [KnowledgeWala](https://knowledgewala.com/?utm_source=pcdoctor&utm_medium=github&utm_campaign=cross_promo). It tells you, in plain words, why your PC is slow, hot or full, and helps you fix it safely. Everything stays on your PC: no account, no tracking, no ads.

This guide has two parts. **Part 1** is for everyone and needs no technical knowledge. **Part 2** is for technical readers who want to know exactly what PCDoctor does.

**Contents**

- Part 1: using PCDoctor
  1. [Is PCDoctor for me?](#1-is-pcdoctor-for-me)
  2. [What you need](#2-what-you-need)
  3. [Install in 1 minute](#3-install-in-1-minute)
  4. [Your first 5 minutes](#4-your-first-5-minutes)
  5. [Every screen, explained](#5-every-screen-explained)
  6. [The AI assistant: on, off, or your own](#6-the-ai-assistant-on-off-or-your-own)
  7. [Fixes with Confirm, and Undo](#7-fixes-with-confirm-and-undo)
  8. [Thought for today](#8-thought-for-today)
  9. [Updating, and keeping your data](#9-updating-and-keeping-your-data)
  10. [Your privacy in one minute](#10-your-privacy-in-one-minute)
  11. [Questions and problems](#11-questions-and-problems)
  12. [Removing PCDoctor](#12-removing-pcdoctor)
- [Part 2: for technical readers](#part-2-for-technical-readers)
- [Feedback and contact](#feedback-and-contact)

---

# Part 1: using PCDoctor

## 1. Is PCDoctor for me?

Yes, if any of these sound familiar:

- "My laptop is slow and the fan is always loud."
- "Drive C: is full again and I don't know what to delete."
- "I have the same photos and PDFs in five places."
- "Lots of programs start when I switch on my PC."
- "I can never find that one PDF or video."

PCDoctor looks at your PC, explains what it finds in one simple sentence, and offers a safe fix. **It never changes anything until you press a button that says exactly what it will do**, and anything it removes goes to the Recycle Bin, so you can put it back.

## 2. What you need

| | |
|---|---|
| **Windows** | Windows 10 or Windows 11, 64-bit. Not available for Mac, Linux or phones yet. |
| **Space** | About 15 MB for PCDoctor. The optional built-in AI needs 1.3 to 5.6 GB more, depending on the size that fits your PC. |
| **Memory** | Any PC works. The optional built-in AI needs at least 6 GB of memory; PCDoctor picks a lighter or larger AI to suit your PC. |
| **Internet** | Only to download PCDoctor. Afterwards it works fully offline. |
| **Account** | None. No sign-up, no email, no password. |

## 3. Install in 1 minute

1. Open the **[Releases page](https://github.com/dharmsahu-hash/pcdoctor-releases/releases/latest)**.
2. Under **Assets**, click **`PCDoctor_0.9.0_x64-setup.exe`** (about 4 MB) to download it.
3. Double-click the downloaded file.
4. If Windows shows **"Windows protected your PC"**, click **More info**, then **Run anyway**. This message appears for new apps that are not yet code-signed; it is expected.
5. Click **Next**, **Install**, **Finish**. No administrator password is needed.

PCDoctor opens, and you will find it in the Start menu under **PCDoctor**.

## 4. Your first 5 minutes

1. **Dashboard** opens first. You will see a greeting with today's thought, and four tiles: **PC health**, **free space on C:**, **memory in use** and **processor busy**. If something needs attention, a coloured bar tells you what, with **See why and how to fix it**.
2. Click **Slow or hot?**, then **Check my PC**. You get a short list, worst problem first, each with a plain fix.
3. Click **Free up space**. PCDoctor lists what can be cleaned, with sizes. Tick what you want, press **Clean**, then **Yes, move … to the Recycle Bin**.
4. Click **Apps** to see apps worth removing or updating, and programs that start with Windows that you could stop.
5. Optional: in **Settings**, tick **Built-in AI** to ask questions like "Why is my PC slow?" in plain English or Hindi.

## 5. Every screen, explained

| Screen | What it does for you |
|---|---|
| **Dashboard** | Your PC at a glance: health, free space, memory and processor, every drive, the biggest programs right now, history charts, when a drive will be full at the current rate, what fills your disks, which programs crashed recently, and the **This week on your PC** summary. |
| **Slow or hot?** | Press **Check my PC** for the main causes in plain words, for example a program crashing in a loop, a nearly full drive, or memory under pressure. **Show details** reveals the technical part. |
| **Free up space** | Lists temporary files, old crash reports, graphics card cache, app download leftovers and old installers, with sizes. Tick and **Clean**: they go to the Recycle Bin. Cleaning carries on in the background, so you don't need to wait on this screen: it shows **Cleaning is in progress** with a count, and the result when it is done. |
| **Duplicates** | Finds files with exactly the same content. Under **Where to look**, press **Change** to add any folder or a whole drive (such as D:), remove one, or go back to the standard folders. Press **Find duplicates**; the search carries on in the background, and the last results show straight away next time. Tick the copies to delete yourself (Shift+click for a range), or let PCDoctor tick the extra copies in every group, keeping the suggested, newest or oldest one; then **Delete selected**. **The last copy can never be deleted.** |
| **My Library** | Every PDF, document, video, photo, music file, archive and installer on your drives in ready-made collections (or your own). Search, open, show in folder, or delete (to the Recycle Bin). Tick several files (Shift+click for a range) to delete them together. |
| **Apps** | Installed apps labelled **Remove**, **Update** or **Keep**, and programs that start with Windows labelled **Stop at startup** or **Keep**, each with a reason. Buttons open the right Windows Settings page. |
| **Activity** | Everything PCDoctor moved to the Recycle Bin or stopped starting with Windows in the last 90 days, with **Undo**. |
| **Your data** | Everything PCDoctor keeps on your PC (history, My Library list, activity log, duplicate fingerprints, AI conversation), how much and why, with a **Delete** for each part and **Keep my AI conversation**. Open it from the privacy line at the top of every screen. |
| **Settings** | The AI switches, Thought for today, Check for updates, privacy, and **Delete everything PCDoctor saved**. |
| **About** | Version, privacy policy, licence, feedback buttons and contact. |
| **Ask PCDoctor AI** | Ask questions about your PC in your own words (when the AI is on). |

**Explain** buttons appear beside findings, crashes, apps and startup items when the AI is on: press one to get that item explained in place.

## 6. The AI assistant: on, off, or your own

The AI is **optional and off until you switch it on**. PCDoctor works fully without it. You choose one of three ways, and you can change your mind at any time: the **AI on / AI off** button at the top of every screen switches the built-in AI in one click (its files are kept, so switching on again is instant), and **Settings → AI assistant** has all the options.

| Choice | How to choose it | What happens |
|---|---|---|
| **Off** (default) | Leave **Built-in AI** unticked, with **Built-in AI** selected under "Who answers your questions". | No AI, nothing downloaded. Every other screen works. |
| **Built-in AI** (private) | Tick **Built-in AI**, then **Download and switch on**. | A one-time download of the AI size that fits your PC (1.3 to 5.6 GB, see below). After that the AI runs on your PC only, even without internet, and **nothing you ask leaves the PC**. |
| **My own AI service** (smarter) | Under "Who answers your questions", choose **My own AI service**, pick a service (Anthropic Claude, OpenAI, Google Gemini, Groq, OpenRouter, or your own address), paste your key, tick the consent box, press **Save and test**. | Answers come from that service. Your questions and PCDoctor's notes about the PC go to it; folders, file contents, your Windows user name and email addresses never do. The service's own terms and charges apply; many have a free tier. |

**Switching off.** Untick **Built-in AI** and choose:

- **Switch off**: the AI stops, and its files stay so you can switch it on again instantly.
- **Switch off and delete AI files**: frees the AI's space (1.3 to 5.6 GB). Your conversation and your own-service choice are kept.

**Which AI size?** PCDoctor picks the size that runs well on your PC, from the lightest up, and you can change it in **Settings → AI assistant → How big an AI to use**:

| Size | Model | Download | Best for |
|---|---|---|---|
| **Light** | Qwen3.5 2B | 1.3 GB | PCs with 6 to 11 GB of memory: about twice as fast there |
| **Standard** | Qwen3.5 4B | 2.7 GB | 12 GB of memory, or a graphics card with 4 GB: better answers |
| **Large** | Qwen3.5 9B | 5.6 GB | a graphics card with 8 GB and 16 GB of memory: the best answers |

The one marked **Best for this PC** is the recommended choice; sizes too big for your PC are greyed out. Changing size downloads that model once and removes the old one.

To stop using your own service, choose **Built-in AI** under "Who answers your questions", or press **Remove key**, which deletes the key from Windows.

**Good questions to try:**

- "Why is my PC slow or hot?"
- "What can I safely clean?"
- "Which programs start with Windows, and should I stop any?"
- "Find my electricity bill" (searches file names in My Library)
- "What are my biggest videos?"
- "Which programs crashed this week?"
- "What is my IP address?" or "How much memory can this laptop take?"

AI answers are suggestions and can be wrong. The AI can never change your PC by itself (see the next section).

## 7. Fixes with Confirm, and Undo

**New in 0.8.0.** When cleaning, or stopping a program starting with Windows, would help, the AI can offer to do it for you. The offer appears under its answer as a card, for example:

> **Stop Docker Desktop starting with Windows**
> It stays installed and you can still open it yourself. Activity can switch it back on.
> **Confirm** · **No thanks**

- **Nothing happens until you press Confirm.** **No thanks** simply hides the card.
- When you press **Confirm**, PCDoctor checks everything again first. Cleaning moves files to the Recycle Bin. Stopping a program switches it off at startup the same way Windows Settings does; **the program is not uninstalled**.
- Afterwards the card says what was done, with a link to **Activity**.
- In **Activity**, press **Undo**: files go back where they were, or the program starts with Windows again.

PCDoctor can switch off programs that start for **your** Windows account. Programs set up for every user of the PC need an administrator, so for those the AI gives you the steps for Windows Settings instead.

## 8. Thought for today

**New in 0.8.0.** The Dashboard greets you with a short quote (from thinkers such as Swami Vivekananda, Rabindranath Tagore, Kabir, Mahatma Gandhi, the Buddha and Benjamin Franklin, and well-known proverbs) and a **Tip for today** for looking after your PC. Both change every day at midnight. They are built into the app; nothing is downloaded.

Don't want it? Untick **Settings → Dashboard → Thought for today**. Tick it again to bring it back.

## 9. Updating, and keeping your data

- **To update:** download the newest installer from the Releases page and run it over the old one. **Your history, My Library, AI files, conversation and settings are kept.**
- **Get told about updates (optional):** in **Settings → Updates**, switch on **Check for updates**. Once a day PCDoctor asks GitHub whether a newer version exists and shows a **Download** button. It never installs anything by itself.

## 10. Your privacy in one minute

**Everything PCDoctor learns about your PC stays on your PC.** To see exactly what it keeps, click the privacy line at the top of any screen (or **Settings → Your data**): each kind of data is listed with how much is kept and why, and each has its own **Delete**. Switch **Keep my AI conversation** off there (or on the Ask screen) and your questions to the AI are kept in memory only and forgotten when PCDoctor closes.

- PCDoctor reads how your PC is running (program names, memory, processor, disk space) and, for My Library, the names, sizes and dates of your files. **It never reads inside your files**, and never reads your browser, emails, chats or passwords.
- **No account, no tracking, no ads, no telemetry.** We cannot see how many people use PCDoctor.
- PCDoctor goes online only for things you switch on: the one-time AI download, the daily update check, and your own AI service if you set one up.
- **Settings → Delete everything PCDoctor saved** wipes its history, My Library list and AI conversation.
- The full privacy policy is in the app under **About**.

## 11. Questions and problems

**"Windows protected your PC" appears when installing.**
Click **More info**, then **Run anyway**. New apps show this until they are code-signed.

**The Built-in AI tick box is greyed out.**
Your PC has less than 6 GB of memory. Use **My own AI service** instead, or use PCDoctor without AI.

**The AI download stopped or failed.**
Check your internet connection, untick and tick **Built-in AI** again. Each file is checked against a fixed fingerprint, so a broken download is never used.

**The AI is slow on my PC.**
Open **Settings → AI assistant** and choose the size marked **Best for this PC** (on PCs with 6 to 11 GB of memory, that is **Light**, about twice as fast). Closing big programs such as many browser tabs also helps. For the fastest and smartest answers on any PC, use **My own AI service**.

**The first AI answer is slow.**
The AI loads when you ask the first question (a few seconds, longer without a graphics card). After that, answers usually start within a few seconds on a PC with a graphics card, and take longer on the processor alone. It frees its memory after 15 idle minutes.

**Cleaning or the duplicate search seems slow. Must I wait on the screen?**
No. Both carry on in the background while you use other screens; the screen says what is in progress and shows the result when you come back. The first duplicate search of a whole drive can take several minutes; later searches only read new or changed files and are much faster.

**Which folders does Duplicates search? Can I add drive D:?**
Yes. Open **Duplicates**, press **Change** under **Where to look**, then **Add drive D:** or **Add a folder…**. App data and, on whole drives, Windows' own folders (Windows, Program Files and similar) are always skipped, so nothing Windows needs is offered for deletion.

**I cleaned something by mistake.**
Open **Activity** and press **Undo**. This works as long as the files are still in the Recycle Bin (PCDoctor never empties it).

**Is PCDoctor free?** Yes, free to download and use.

**Does it work on Mac, Linux or phones?** Not yet. Tell us if you want it: [Suggest a feature](https://github.com/dharmsahu-hash/pcdoctor-releases/issues/new?template=feature-request.yml).

## 12. Removing PCDoctor

Open Windows **Settings → Apps → Installed apps**, find **PCDoctor**, press the three dots, choose **Uninstall**. To also remove what it saved, first use **Settings → Delete everything PCDoctor saved** in PCDoctor (or delete the folder `%LOCALAPPDATA%\com.knowledgewala.pcdoctor`).

---

# Part 2: for technical readers

**Architecture.** Tauri 2 desktop app: a Rust core and a React + TypeScript window (WebView2). Local SQLite database for history, My Library and the activity log. Per-user NSIS installer (`currentUser`, no elevation). If WebView2 is missing (rare on Windows 10, built into Windows 11), the installer fetches Microsoft's bootstrapper.

**Built-in AI.** Qwen3.5 4B (Apache 2.0, 4-bit GGUF) served by llama.cpp (MIT) as a local `llama-server` bound to `127.0.0.1` with a random per-run API token, context 6144, prompt caching on. A Vulkan build is used when an NVIDIA, AMD or Intel Arc graphics card is found. Downloads are pinned by size and SHA-256 and come only from github.com (llama.cpp releases) and huggingface.co. The engine stops after 15 idle minutes.

**Agent tools.** The model may call `search_files` (My Library index: names, kinds, sizes, dates, drive letters, never folder paths), `space_by_type`, `pc_history`, `crashes` (Windows event log, Application Error/Hang, Kernel-Power 41), and `suggest_fix`. At most 3 tool rounds per question.

**AI size (0.8.2).** `recommended(memory, graphics memory)`; graphics memory comes from Windows' display-adapter registry entry (`HardwareInformation.qwMemorySize`) before any download. All three models are pinned by size and SHA-256 (lmstudio-community Q4_K_M GGUF on huggingface.co, Apache 2.0). Answers pass two guards for every size: uninstall advice that names a running program, a browser or PCDoctor is replaced with safe steps, and a Confirm card only shows when the answer speaks of it.

**Background jobs (0.8.1).** Cleaning and the duplicate search run on their own thread, one of each at a time, and the window reads their state (step, count, result) whenever the screen is shown, so leaving a screen never stops or loses a job.

**Proposed fixes (0.8.0).** `suggest_fix` only builds a proposal (`kind` + `items`), which PCDoctor validates against the live PC before showing it. On **Confirm**, `apply_fix` re-validates from scratch: cleaning rescans the fixed Free up space folders (direct children only, symlinks never followed) and sends items to the Recycle Bin; startup switching writes Windows' own `StartupApproved` value (`03 00 00 00` + FILETIME for off, `02` + 11 zero bytes for on) under `HKCU\Software\Microsoft\Windows\CurrentVersion\Explorer\StartupApproved\{Run,StartupFolder}`, only for entries in `HKCU\...\Run` and the user's Startup folder. The Run entry itself is never touched. Every change is written to the activity log for Undo. If the model mentions Confirm without a valid proposal, that sentence is removed.

**Network.** The window's Content Security Policy allows no remote connections. The Rust core may connect only from three modules, each with a fixed host allow-list, and a build-time test (`network_guard`) fails the build if any other file uses a network library or names another host:

| Module | When | Hosts |
|---|---|---|
| AI download | After you switch the built-in AI on | github.com, huggingface.co |
| Update check | Only if **Check for updates** is on, at most daily, or **Check now** | api.github.com |
| Own AI service | Only after you choose it, add a key and consent | the service you chose (https), or http to this PC |

Links (KnowledgeWala, TeacherCircle, feedback, contact) open in your browser only when clicked, with `utm_source=pcdoctor` and nothing else.

**Data on disk.** `%LOCALAPPDATA%\com.knowledgewala.pcdoctor\`: `pcdoctor.db` (history every 5 minutes while open, kept 90 days; My Library index; duplicate-search fingerprints (path, size, date and a BLAKE3 hash, forgotten after 30 days unseen), chosen folders and last results; activity log, 90 days), `ai\` (engine, model, `conversation.json` with the last 100 messages, `pc-context.md`, `insight.json`, `online-ai.json`), `update.json`. Own-service keys are stored in Windows Credential Manager (service name "PCDoctor online AI"). Before anything reaches an AI, the Windows user name and email-like strings are masked.

**Quality.** Each release passes `npm audit`, TypeScript checks, 110 screen tests, 176 Rust unit tests and 4 network-guard tests, `cargo clippy -D warnings` and `cargo audit` in CI, plus real-PC tests on Windows 11 with the real AI, Recycle Bin and event log.

**Verify your download.** Compare the SHA-256 shown on the release page with:

```
certutil -hashfile PCDoctor_0.9.0_x64-setup.exe SHA256
```

**Licences.** PCDoctor is free to use under its licence agreement (shown in About). Third-party notices (Tauri, React, llama.cpp, Qwen and others) are listed in full in the app's About screen.

---

## Supporting PCDoctor

PCDoctor is free, with no ads and no tracking, and it always will be. If you would like to help keep it going, the **About** screen has **Buy us a coffee — no obligation**: a QR code to scan with PhonePe or another UPI app. Any amount helps pay for fixes, Windows updates and new features. It is entirely optional; every feature stays free either way.

## Feedback and contact

Your feedback decides what PCDoctor does next.

- **[Share feedback](https://github.com/dharmsahu-hash/pcdoctor-releases/issues/new?template=feedback.yml)**: what you like, what is confusing, or what went wrong
- **[Suggest a feature](https://github.com/dharmsahu-hash/pcdoctor-releases/issues/new?template=feature-request.yml)**
- Email: [dknitk@gmail.com](mailto:dknitk@gmail.com?subject=PCDoctor)

More from KnowledgeWala: **[KnowledgeWala](https://knowledgewala.com/?utm_source=pcdoctor&utm_medium=github&utm_campaign=cross_promo)** (learning resources and free tools) · **[TeacherCircle](https://teacherscircle.co.in/?utm_source=pcdoctor&utm_medium=github&utm_campaign=cross_promo)** (find a teacher near you in India).

© 2026 KnowledgeWala. All rights reserved.
