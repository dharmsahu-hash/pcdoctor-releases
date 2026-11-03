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
  9. [Running in the tray, and starting with Windows](#9-running-in-the-tray-and-starting-with-windows)
  - [Mini monitor and temperatures](#9b-mini-monitor-and-temperatures)
  - [Reminders and notifications](#9c-reminders-and-notifications)
  10. [Updating, and keeping your data](#10-updating-and-keeping-your-data)
  11. [Your privacy in one minute](#11-your-privacy-in-one-minute)
  12. [Questions and problems](#12-questions-and-problems)
  13. [Removing PCDoctor](#13-removing-pcdoctor)
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
2. Under **Assets**, click **`PCDoctor_0.19.0_x64-setup.exe`** (about 4 MB) to download it.
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
| **Dashboard** | Your PC at a glance: health, free space, memory and processor, the **Modes** card (Gaming, Work, Battery, Watching: switches the Windows power plan in one click, with Undo in Activity), every drive, the biggest programs right now (named as Task Manager names them, with their helpers and, for service hosts, the Windows services inside), history charts, when a drive will be full at the current rate, what fills your disks, which programs crashed recently, and the **This week on your PC** summary. **Open the mini monitor** (under the tiles) opens a small always-on-top window with processor, memory, graphics card and temperatures. |
| **Slow or hot?** | Press **Check my PC** for the main causes in plain words, for example a program crashing in a loop, a nearly full drive, or memory under pressure, or that the PC slowed itself down to stay cool for a long time today. **Show details** reveals the technical part. |
| **Free up space** | Lists temporary files, old crash reports, graphics card cache, app download leftovers and old installers, with sizes. Tick and **Clean**: they go to the Recycle Bin. Cleaning carries on in the background, so you don't need to wait on this screen: it shows **Cleaning is in progress** with a count, and the result when it is done. |
| **Duplicates** | Finds files with exactly the same content. Under **Where to look**, press **Change** to add any folder or a whole drive (such as D:), remove one, or go back to the standard folders. Press **Find duplicates**; the search carries on in the background, and the last results show straight away next time. Tick the copies to delete yourself (Shift+click for a range), or let PCDoctor tick the extra copies in every group, keeping the suggested, newest or oldest one; then **Delete selected**. **The last copy can never be deleted.** |
| **My Library** | Every PDF, document, video, photo, music file, archive and installer on your drives in ready-made collections (or your own). **Search inside files** (off until you switch it on) finds files by words inside them, using the index Windows already keeps. Search by name, open, show in folder, or delete (to the Recycle Bin). Tick several files (Shift+click for a range) to delete them together. In your own collections, **Bigger than (MB)** takes up to 10,000,000 MB and **Changed in the last (days)** up to 36,500 days, digits only. |
| **Apps** | **App updates** (off until you switch it on): lists apps with newer versions through Microsoft's winget, with **Update** after you confirm; an update cannot be undone. Installed apps labelled **Remove**, **Update** or **Keep**, and programs that start with Windows labelled **Stop at startup** or **Keep**, each with a reason. Buttons open the right Windows Settings page. |
| **Automation** | Your own cleanup rules for chosen folders: which files (name patterns, age, size, keep the newest few), when (every few hours, day, week or month, once, or only on **Run now**) and what happens (**Preview only**, **Recycle Bin**, **quarantine**, or **Delete permanently** once you allow it in **Automation settings**). Rules can take files or whole folders. **Preview** shows exactly which files a rule would move before it can move any. Each rule has a **History** with **Put them back** for quarantined files. See section 9d. |
| **Reminders** | Your own reminders (once, every day, week or month) with **Add reminder** at the top, and the PC care alerts with their switches. Also opens from the bell's **Reminder settings** and **Settings → Open Reminders**. |
| **Activity** | Everything PCDoctor moved to the Recycle Bin (including by an automation rule) or stopped starting with Windows in the last 90 days, and each time you switched **Start PCDoctor with Windows** on or off, with **Undo**. |
| **Your data** | Everything PCDoctor keeps on your PC (history, My Library list, activity log, automation history, duplicate fingerprints, reminders and notifications, AI conversation), how much and why, with a **Delete** for each part and **Keep my AI conversation**. Open it from the privacy line at the top of every screen. |
| **Settings** | The AI switches, Thought for today, **Reminders and notifications**, **Running in the background** (tray, Start with Windows, Pause readings), Check for updates, privacy, and **Delete everything PCDoctor saved**. |
| **About** | Version, privacy policy, licence, feedback buttons, contact, and all our free products: InsightGyan, TimeCraft, TeacherCircle, the SDLC Plugin, KnowledgeWala Software and the KnowledgeWala blog. |
| **Ask PCDoctor AI** | Ask questions about your PC in your own words (when the AI is on). |

The **bell** at the top of every screen shows your reminders and PC care alerts; see [Reminders and notifications](#9c-reminders-and-notifications).

**Help on every screen (new in 0.13.0).** Press **How this helps** next to any screen title for a short guide: what the screen does, when to use it, and a few tips. Point at the small **i** beside a section heading (or reach it with Tab) to read what that section shows. Point at a menu item for a one-line description.

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
- Activity checks the Recycle Bin when you open it (since 0.11.1). If it was emptied, the entry says **No longer in the Recycle Bin** and has no Undo button; if only some files are left, it says how many, for example *"12 of 34 files are still in the Recycle Bin"*.

PCDoctor can switch off programs that start for **your** Windows account. Programs set up for every user of the PC need an administrator, so for those the AI gives you the steps for Windows Settings instead.

## 8. Thought for today

**New in 0.8.0.** The Dashboard greets you with a short quote (from thinkers such as Swami Vivekananda, Rabindranath Tagore, Kabir, Mahatma Gandhi, the Buddha and Benjamin Franklin, and well-known proverbs) and a **Tip for today** for looking after your PC. Both change every day at midnight. They are built into the app; nothing is downloaded.

Don't want it? Untick **Settings → Dashboard → Thought for today**. Tick it again to bring it back.

## 9. Running in the tray, and starting with Windows

**New in 0.10.0.** PCDoctor can keep running quietly as a small icon in the **system tray**, the row of icons next to the clock (some hide under the **^** arrow). While it runs, it records how your PC is doing every 5 minutes, so the Dashboard charts and "At this rate, C: is full in…" have no gaps.

- **The first time you close the window**, PCDoctor asks **Keep PCDoctor running in the tray?** Choose **Keep running in the tray**, **Quit PCDoctor** (closes completely, as before) or **Cancel**. It asks only once.
- **Click the tray icon** to open PCDoctor again. **Point at it** to see the latest reading, for example "processor 12%, memory 38% used".
- **Right-click the tray icon** for **Open PCDoctor**, **Mini monitor**, **Pause readings** (or **Resume readings**) and **Quit PCDoctor**.
- **Very light:** in the tray the window and the AI are closed, so their memory goes back to your PC. On our test PC it used no measurable processor time and about 40 MB of memory.
- Opening PCDoctor from the Start menu while it is in the tray brings its window back; it never runs twice.

Change any of this in **Settings → Running in the background**:

- **Keep running in the tray when I close the window**: on or off.
- **Start PCDoctor with Windows**: **off** unless you switch it on. When on, PCDoctor opens quietly in the tray when you sign in. It shows on the **Apps** screen and in Windows' own **Startup apps** like any other startup program, and each change is listed in **Activity** with **Undo**.
- **Pause readings**: stops the 5-minute readings until you switch it off (the charts will have a gap for that time).

## 9b. Mini monitor and temperatures

**New in 0.11.0.** The **mini monitor** is a small window that stays on top of your other apps. Open it from the Dashboard (**Open the mini monitor**, under the tiles) or by right-clicking the PCDoctor icon next to the clock and choosing **Mini monitor**. Every 2 seconds it shows:

- **Processor**, **Memory** and **Graphics card**: how busy each one is, counted the way Task Manager counts it.
- **Graphics card temperature**: on PCs with an NVIDIA graphics card, from NVIDIA's own driver.
- **PC temperature**: from Windows' own temperature sensor, shown once PCDoctor has seen it change (some PCs report a fixed, made-up value there).
- **Slowing down to stay cool**: shown only while Windows is holding the PC back because it is too hot.

Where there is no real sensor it says **Not available on this PC**; PCDoctor never guesses a temperature and installs no extra driver to read one. Close the mini monitor with its **×**; PCDoctor keeps running.

**Overheating advice.** PCDoctor counts the minutes your PC slows itself down to stay cool. If that adds up to 10 minutes or more in the last 24 hours, **Slow or hot?** says so, for example *"Your PC slowed itself down to stay cool for 42 minutes in the last 24 hours"*, with simple steps: shut the PC down and blow the dust out of the vents and fan, use a laptop on a hard, flat surface, and have the fan checked if it keeps happening.

## 9c. Reminders and notifications

**New in 0.12.0.** PCDoctor can remind you to look after your PC, or of anything else you choose.

- **Add a reminder:** open **Reminders** in the menu (since 0.13.0; also from the bell's **Reminder settings**) and press **Add reminder**. Write what it is for (up to 80 characters), pick the date and time, and choose **Once**, **Every day**, **Every week** or **Every month**. The quick picks (**Free up space**, **Look for duplicate files**, **Back up important files**, **Restart your PC**) fill it in for you; the first two open the right screen when they come.
- **Ready-made:** a monthly **Free up space** reminder is there from the start. Delete it with its **×** if you don't want it.
- **The bell** at the top shows how many notifications are new. Click it to see them, newest first: **Open** goes to the right screen, **×** removes one. A new one also shows in the corner for a few seconds. The last 50 are kept, for up to 30 days.
- **While PCDoctor is in the tray** (or its window is minimised), Windows shows the reminder next to the clock. Switch this off with **Windows notifications**.
- **PC care alerts**, each with its own switch and at most once a day: a drive is almost full (less than 10% free), the PC slowed down to stay cool for 10 minutes or more today, or it has not restarted for 7 days.
- Reminders come only while PCDoctor is open or in the tray. A reminder that came due while PCDoctor was closed shows once when you open it again, not once for every day missed. If closing the window quits PCDoctor, the Reminders section says so and offers **Keep running in the tray**.

## 9d. Automation: folders that tidy themselves

**New in 0.18.0.** Make a rule once and PCDoctor keeps a folder tidy for you.

1. Open **Automation** in the menu and press **New rule**, or pick a ready-made one: **Old temporary files**, **Old log files**, **Old downloads**, **Keep the newest 10 backups**, **Large old files**.
2. **Folders:** press **Browse…** or type a path and press **Add**. Tick **Include subfolders** if you want them too.
3. **Which files:**
   - **File names** such as `*.log; *.tmp` (`*` stands for any letters, `?` for one; empty means every file).
   - **Never touch**: names such as `important*`, or paths inside the folder such as `keep\*`.
   - **Older than (days)**, counted since the file was last changed or since it was created.
   - **Size (MB)**, at least and at most.
   - **Keep the newest**: so many files in each folder are always kept, for example your last 10 backups.
4. **When:**
   - **Only when I press Run now**, **Every few hours**, **Every day**, **Every week**, **Every month** or **Once**, from the date and time you choose.
   - Rules run while PCDoctor is open or in the tray.
   - A run missed while the PC was off comes once, a couple of minutes after PCDoctor starts.
5. **What happens to the files:**
   - **Preview only** (every new rule starts here; nothing is touched).
   - **Move to the Recycle Bin**: **Undo** in Activity.
   - **Move to quarantine**: into PCDoctor's own folder; **Put them back** in the history.
6. Press **Preview**. You see how many files would go and how much space that frees, the files themselves (50 per page, the first 500 listed), and the files left alone with the reason. **A rule can move files only after you have previewed exactly those settings**; change the folders or filters and preview again.
7. **Tell me:** **Only when something goes wrong** (the default), **After every run**, or **Never**. Notices come under the bell and as Windows notifications.

Each rule has:
- **Run now**, **Pause**/**Resume**, edit, **Copy** (the copy is paused and set to Preview only), **History** and **Delete** (it asks first; the history stays).
- **Cancel** stops a running rule after the file it is on.
- **History** shows each run for 90 days: when and why it ran, what was moved and what was left (and why, for example a file in use), and the space freed.

**Delete permanently (new in 0.19.0):**
1. Under **Automation settings** (below your rules), switch on **Allow rules to delete permanently**, read the warning, and press **I understand, allow it**. It is off until you do.
2. In a rule, choose **Delete permanently**, press **Preview**, then type the rule's name to confirm and **Save rule**. You type it again whenever you change which files the rule takes.

Deleted files skip the Recycle Bin and **cannot be brought back**. They are listed in red in the rule's history, and in Activity as *Deleted for ever by an automation rule*, without Undo. Switch the setting off at any time to stop every such rule. Free up space, Duplicates and My Library still use the Recycle Bin.

**Whole folders, and folders left empty (new in 0.19.0):**
- Under **What to clean**, choose **Whole folders**. Names match folder names (`cache*`), the age is the newest file inside, and the size is everything inside. Folders go to the Recycle Bin or are deleted permanently, not to quarantine.
- A folder holding a link, a Windows system file, a read-only file or an online-only OneDrive file is always left. The folders you chose never go.
- For file rules, **Also remove folders left empty** removes folders with nothing inside after the run. **Undo** and **Put them back** make them again.

**Safe by design:**
- Windows, Program Files, ProgramData, your profile and AppData folders themselves, whole drives, network folders and links are refused, with the reason.
- Links and junctions are never followed.
- Windows system files, read-only files and online-only OneDrive files are left alone.
- Every file is checked again right before it moves; if it changed or is in use, it stays.
- **Nothing is deleted for ever** unless you allowed it and confirmed that rule.

## 10. Updating, and keeping your data

- **To update:** download the newest installer from the Releases page and run it over the old one. **Your history, My Library, AI files, conversation and settings are kept.**
- **Get told about updates (optional):** in **Settings → Updates**, switch on **Check for updates**. Once a day PCDoctor asks GitHub whether a newer version exists and shows a **Download** button. It never installs anything by itself.

## 11. Your privacy in one minute

**Everything PCDoctor learns about your PC stays on your PC.** To see exactly what it keeps, click the privacy line at the top of any screen (or **Settings → Your data**): each kind of data is listed with how much is kept and why, and each has its own **Delete**. Switch **Keep my AI conversation** off there (or on the Ask screen) and your questions to the AI are kept in memory only and forgotten when PCDoctor closes.

- PCDoctor reads how your PC is running (program names, memory, processor, disk space) and, for My Library, the names, sizes and dates of your files. **It never opens your files to read them** (Search inside files, if you switch it on, asks the index Windows already keeps, and its results stay on screen), and never reads your browser, emails, chats or passwords.
- **No account, no tracking, no ads, no telemetry.** We cannot see how many people use PCDoctor.
- PCDoctor goes online only for things you switch on: the one-time AI download, the daily update check, and your own AI service if you set one up.
- **Settings → Delete everything PCDoctor saved** wipes its history, My Library list and AI conversation.
- The full privacy policy is in the app under **About**.

## 12. Questions and problems

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
Open **Activity** and press **Undo**. This works as long as the files are still in the Recycle Bin (PCDoctor never empties it). If you emptied it, Activity says **No longer in the Recycle Bin** and those files cannot come back. Afterwards **Free up space** (or **Duplicates**) says the clean-up was undone; close any result message with its **×**.

**I closed PCDoctor but it is still running.**
You chose **Keep running in the tray**. Right-click the PCDoctor icon next to the clock and choose **Quit PCDoctor**, or switch off **Settings → Running in the background → Keep running in the tray when I close the window**.

**A reminder did not come.**
Reminders come only while PCDoctor is open or running in the tray. Check **Settings → Running in the background → Keep running in the tray when I close the window**, and switch on **Start PCDoctor with Windows** if you want reminders after a restart without opening PCDoctor. A reminder missed while PCDoctor was closed shows once when you open it.

**I don't want Windows notifications from PCDoctor.**
Switch off **Settings → Reminders and notifications → Windows notifications**. Reminders still appear under the bell.

**"Restart your PC" keeps coming although I shut down every evening.**
With Windows' Fast Startup, **Shut down** does not fully restart the PC. Choose **Restart** once.

**I can't see the tray icon.**
Click the **^** arrow next to the clock; Windows hides some icons there. You can drag the PCDoctor icon next to the clock to keep it visible.

**The mini monitor says "Not available on this PC" for a temperature.**
Your PC has no sensor PCDoctor can read safely. Graphics card temperature is read on NVIDIA cards only, and the PC temperature only when Windows reports a real, changing value. PCDoctor does not install the extra drivers other tools use, because Microsoft Defender flags them.

**A program on the Dashboard has a different name from Task Manager.**
PCDoctor uses the same source as Task Manager for most programs, but a few built-in Windows parts keep their file name (for example CHXSmartScreen.exe). Tell us which one with **Share feedback**.

**The Modes card only shows "Open Power settings".**
Your PC has only Windows' Balanced plan and uses the **Power mode** slider instead (most Windows 11 laptops). Windows lets only its own Settings change that slider: choose **Best performance** for games, **Balanced** for work and **Best power efficiency** on battery.

**App updates says winget is not on this PC, or asks me to accept an agreement.**
winget comes with Windows 11 and with **App Installer** from the Microsoft Store on Windows 10. The first time, winget may ask you to accept the Microsoft Store source agreement: open Command Prompt, type `winget upgrade`, read it and answer **Y**, then press **Check now**. PCDoctor never accepts it for you.

**Search inside files does not find a file I know is there.**
Windows only indexes some places (your user folders by default) and only the file types it has filters for; PDFs need a PDF filter, which most PCs have. If the panel says a folder is not indexed, press **Choose what Windows indexes** and add it; Windows needs a while to index new places.

**An automation rule left some files where they were.**
Open **Automation → History**, press **Files** next to the run, and read the reason beside each file. *In use by another program*: close that program and the next run takes it. *Changed since it was checked*: the file changed during the run, so it was left on purpose. Read-only, system and online-only OneDrive files are always left alone.

**An automation rule says "Could not run".**
Usually its folder is not there, for example a USB drive that is not plugged in. The rule tries again after an hour, up to three times, then waits for its next time.

**Can I get back files an automation rule deleted permanently?**
No. PCDoctor and the Recycle Bin cannot bring them back; only your own backup can. That is why the setting is off until you allow it, and each rule asks you to type its name.

**How do I get files back from an automation rule?**
For **Move to the Recycle Bin**, use **Undo** in Activity. For **Move to quarantine**, open **Automation → History**, press **Files** next to the run, then **Put them back**. A file goes back only if its folder still exists and no other file with its name is there.

**Is PCDoctor free?** Yes, free to download and use.

**Does it work on Mac, Linux or phones?** Not yet. Tell us if you want it: [Suggest a feature](https://github.com/dharmsahu-hash/pcdoctor-releases/issues/new?template=feature-request.yml).

## 13. Removing PCDoctor

If PCDoctor is in the tray, right-click its icon and choose **Quit PCDoctor** first. Then open Windows **Settings → Apps → Installed apps**, find **PCDoctor**, press the three dots, choose **Uninstall**. Uninstalling also removes **Start PCDoctor with Windows**. To also remove what it saved, first use **Settings → Delete everything PCDoctor saved** in PCDoctor (or delete the folder `%LOCALAPPDATA%\com.knowledgewala.pcdoctor`).

---

# Part 2: for technical readers

**Architecture.** Tauri 2 desktop app: a Rust core and a React + TypeScript window (WebView2). Local SQLite database for history, My Library and the activity log. Per-user NSIS installer (`currentUser`, no elevation). If WebView2 is missing (rare on Windows 10, built into Windows 11), the installer fetches Microsoft's bootstrapper.

**Built-in AI.** Qwen3.5 4B (Apache 2.0, 4-bit GGUF) served by llama.cpp (MIT) as a local `llama-server` bound to `127.0.0.1` with a random per-run API token, context 6144, prompt caching on. A Vulkan build is used when an NVIDIA, AMD or Intel Arc graphics card is found. Downloads are pinned by size and SHA-256 and come only from github.com (llama.cpp releases) and huggingface.co. The engine stops after 15 idle minutes.

**Agent tools.** The model may call `search_files` (My Library index: names, kinds, sizes, dates, drive letters, never folder paths), `space_by_type`, `pc_history`, `crashes` (Windows event log, Application Error/Hang, Kernel-Power 41), and `suggest_fix`. At most 3 tool rounds per question.

**AI size (0.8.2).** `recommended(memory, graphics memory)`; graphics memory comes from Windows' display-adapter registry entry (`HardwareInformation.qwMemorySize`) before any download. All three models are pinned by size and SHA-256 (lmstudio-community Q4_K_M GGUF on huggingface.co, Apache 2.0). Answers pass two guards for every size: uninstall advice that names a running program, a browser or PCDoctor is replaced with safe steps, and a Confirm card only shows when the answer speaks of it.

**Mini monitor and heat (0.11.0).** `monitor.rs` samples every 30 s, or every 2 s while the mini monitor is open, through pdh.dll: Processor Information `% Processor Utility`; `GPU Engine(*)\Utilization Percentage` summed per engine across processes, then the busiest engine per adapter and the busiest adapter (as Task Manager); Thermal Zone `High Precision Temperature` (tenths of a kelvin) and `% Passive Limit`. On NVIDIA cards `nvml.dll` is loaded from System32 only, for temperature and the software/hardware thermal slowdown reasons. A thermal zone counts once its value has changed and stays between 15 and 115 °C. Slowed time (passive limit below 100%, or NVML thermal slowdown) and maximum temperatures go into the `heat_reading` history table with each 5-minute reading; the advisor rule `heat:slowed` fires at 10 minutes in 24 hours. Measured with the release build on a Core i9-9880H with a GTX 1650 Max-Q: about 0.09% of the processor at the 2-second pace.

**Tray and Start with Windows (0.10.0).** Closing the window to the tray destroys it (not just hides it), so WebView2 and the AI engine release their memory; only the 5-minute reading thread and the 6-hourly My Library check keep running, and the window is rebuilt when opened. A single-instance lock (Tauri's official plugin) hands a second launch to the running copy. **Start PCDoctor with Windows** writes one value, `PCDoctor` = `"<install path>\pcdoctor.exe" --tray`, under `HKCU\Software\Microsoft\Windows\CurrentVersion\Run`; switching it off deletes that value and its `StartupApproved` note, and a real uninstall removes both (an update keeps them). Measured with the release build: 0% CPU over 30 s and 29–40 MB working set in the tray.

**Background jobs (0.8.1).** Cleaning and the duplicate search run on their own thread, one of each at a time, and the window reads their state (step, count, result) whenever the screen is shown, so leaving a screen never stops or loses a job.

**Help and links (0.13.0).** Screen help lives in `src/lib/help.ts`; title buttons use `aria-expanded`/`aria-controls`, section tips are buttons with `aria-describedby` pointing at a `role="tooltip"` element, and both sit beside the headings so heading names stay unchanged. New browser links (insightgyan.knowledgewala.com, software.knowledgewala.com, two GitHub pages) are in the fixed list in `links.rs` with `utm_source=pcdoctor`; the network guard checks the host list.

**Reminders and notifications (0.12.0).** `reminders.rs` stores each reminder's first local wall time and repeat; the next time is worked out with chrono in local time (month ends clamped to the last day, a time skipped by a clock change comes an hour later, a repeated one the first time). A thread checks every 30 s; a missed reminder fires once. Alerts reuse the Dashboard's drive rule and the `heat:slowed` advice, take Windows' uptime for the restart alert, start 1 minute after launch and are limited to once per 24 hours each. Notifications go to the window as an event and, when it is not shown, to Windows through Tauri's notification plugin (AppUserModelID of the installed app). Reminder text stays on this PC: never in reports, logs or anything given to the AI.

**Search inside files (0.17.0).** `contents.rs` runs one hidden PowerShell call per search that queries Windows Search's `SystemIndex` through the `Search.CollatorDSO` OLE DB provider (`CONTAINS(*, '"word*" AND …')`, top 100 by rank, files only). Words are reduced to letters, digits, `-`, `_` and `.` and passed in an environment variable, never pasted into the script. Nothing is asked while the switch is off (tested); files are never opened and no second index is built; results stay in memory, on screen only, never saved or given to the AI. One `SCOPE='file:<folder>'` probe per My Library folder names the folders Windows does not index. On the test PC: 36 files for one word in 0.6 s.

**Automation (0.18.0).**
- **Engine:** `automation.rs` keeps rules as JSON in SQLite (`auto_rule`, `auto_run`, `auto_file`). It walks folders with `walkdir` as a stream and never follows links; memory stays bounded by the largest single folder. Keep-newest-N is applied per folder.
- **Folder guard (`Guard`):** refuses Windows, Program Files, ProgramData and PCDoctor's folder, plus anything inside them; the profile, AppData, Local, Roaming, Public and Users folders themselves; drive roots; `..`; UNC paths and drives that Windows does not list as local; and reparse points anywhere in the path.
- **Final check before every move:** same size and date, real path still inside the folder, and the file can be opened for writing (it is not in use).
- **Preview gate:** saving a rule that moves files needs a preview of the same filters in this session. This is checked in Rust, not only on screen.
- **Where files go:** the Recycle Bin, noted in Activity as kind `automation`; or a quarantine folder under `%LOCALAPPDATA%\com.knowledgewala.pcdoctor\quarantine`, by rename, or by copy, size check and remove across drives.
- **Running:** one worker thread runs rules one at a time, and a rule is never queued twice. The schedule is checked every 30 s from 2 minutes after start, using the reminders' local-time code. A failed run is retried after an hour, up to three times.
- **Measured on the test PC:** a 100,000-file preview in 0.45 s, and 0.01% of the processor idle in the tray.
- **Delete permanently and folders (0.19.0):** `Action::Delete` needs lib_meta `auto_delete_allowed` and the typed rule name, both checked in Rust; a run with the setting off fails without retries. `What::Folders` measures each candidate folder without following links (files, bytes, newest file date; never one holding a link, system, read-only or online-only file) and measures it again right before deletion. Files are removed one by one, then folders bottom up. Activity kind `autoDelete` has no Undo. "Remove folders left empty" removes empty folders bottom up, never the chosen folders; Undo and Put back create them again.

**App updates (0.16.0).** `winget.rs` runs Microsoft's winget (the WindowsApps alias, hidden) only while **Check which apps have newer versions** is on; a test proves no winget process starts while it is off. Listing: `winget upgrade --disable-interactivity`, read by the positions of the heading words (any language). Updating one app from the last list, after Update and Confirm: `winget upgrade --id <Id> --exact --silent --disable-interactivity --accept-package-agreements`. PCDoctor never accepts winget's source agreement for you. Activity notes each update without Undo.

**Modes (0.15.0).** `power.rs` runs Windows' own `powercfg.exe` from System32 (`/list`, `/setactive <GUID>`), hidden and without administrator rights; plans are read by GUID, so any language works. Gaming → High performance (or Ultimate Performance), Work and Watching → Balanced, Battery → Power saver. It switches only to a plan the PC lists, checks Windows took it, and notes the previous plan in Activity for Undo. On PCs with only Balanced (the Windows 11 Power mode slider, which only Settings may change), the card explains and opens `ms-settings:powersleep`; no undocumented APIs.

**Program names and services (0.14.0).** `procnames.rs` reads each program's file description from version.dll, the running services per process from the Service Control Manager (`EnumServicesStatusExW`, enumerate right only, no administrator) and app package names from `AppxManifest.xml`; both DLLs come from System32 only, and with `monitor.rs` it is the only module with `unsafe` code (a test enforces it). Processes are grouped under their highest ancestor that is not a launcher (Explorer, services.exe, svchost.exe, shells), a parent must be older than its child, and each svchost is its own "Service Host: <service>" entry. The advice rules still use the groups by file name. No file paths leave the reader. Snapshot time on the test PC: 0.9 s for the first, then about 0.4 s.

**My Library refresh (0.12.0).** The folder walk runs outside any transaction and files are saved 2,000 at a time in short transactions; files no longer found are removed only after a complete walk. Before, one transaction covered the whole walk, so other saves could fail with "database is locked" (on our test PC with 151,000 files: 592 of 595 saves failed during a refresh; after the fix 0 of 121, longest wait 11 ms).

**Collection rules (0.11.2).** Size and age limits are computed with saturating arithmetic, clamped to `i64::MAX`, so a huge size matches no file (before 0.11.2, `(mb * 1 MiB) as i64` could wrap negative and match every file). The form accepts digits only and disables Save above 10,000,000 MB or 36,500 days.

**Activity and the Recycle Bin (0.11.1).** When the Activity screen opens, `activity_list` reads the Recycle Bin once and counts, per entry, the files still there with the same matching as Undo (same original place, deleted within 15 minutes of the logged time; indexed by folder and name, 2,000 items in about 3 ms). An Undo that brings nothing back no longer marks the entry undone. 0.11.1 also updates rustls to 0.23.46 (RUSTSEC-2026-0346 to 0349).

**Proposed fixes (0.8.0).** `suggest_fix` only builds a proposal (`kind` + `items`), which PCDoctor validates against the live PC before showing it. On **Confirm**, `apply_fix` re-validates from scratch: cleaning rescans the fixed Free up space folders (direct children only, symlinks never followed) and sends items to the Recycle Bin; startup switching writes Windows' own `StartupApproved` value (`03 00 00 00` + FILETIME for off, `02` + 11 zero bytes for on) under `HKCU\Software\Microsoft\Windows\CurrentVersion\Explorer\StartupApproved\{Run,StartupFolder}`, only for entries in `HKCU\...\Run` and the user's Startup folder. The Run entry itself is never touched. Every change is written to the activity log for Undo. If the model mentions Confirm without a valid proposal, that sentence is removed.

**Network.** The window's Content Security Policy allows no remote connections. The Rust core may connect only from three modules, each with a fixed host allow-list, and a build-time test (`network_guard`) fails the build if any other file uses a network library or names another host:

| Module | When | Hosts |
|---|---|---|
| AI download | After you switch the built-in AI on | github.com, huggingface.co |
| Update check | Only if **Check for updates** is on, at most daily, or **Check now** | api.github.com |
| Own AI service | Only after you choose it, add a key and consent | the service you chose (https), or http to this PC |

Links (KnowledgeWala, TeacherCircle, feedback, contact) open in your browser only when clicked, with `utm_source=pcdoctor` and nothing else.

**Data on disk.** `%LOCALAPPDATA%\com.knowledgewala.pcdoctor\`: `pcdoctor.db` (reminders and the last 50 notifications; history every 5 minutes while open or in the tray, including graphics card use, temperatures and minutes slowed down to stay cool, kept 90 days; My Library index; duplicate-search fingerprints (path, size, date and a BLAKE3 hash, forgotten after 30 days unseen), chosen folders and last results; activity log, 90 days), `ai\` (engine, model, `conversation.json` with the last 100 messages, `pc-context.md`, `insight.json`, `online-ai.json`), `update.json`. Own-service keys are stored in Windows Credential Manager (service name "PCDoctor online AI"). Before anything reaches an AI, the Windows user name and email-like strings are masked.

**Quality.** Each release passes `npm audit`, TypeScript checks, 189 screen tests, 258 Rust unit tests and 4 network-guard tests, `cargo clippy -D warnings` and `cargo audit` in CI, plus real-PC tests on Windows 11 with the real AI, Recycle Bin and event log.

**Verify your download.** Compare the SHA-256 shown on the release page with:

```
certutil -hashfile PCDoctor_0.19.0_x64-setup.exe SHA256
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
