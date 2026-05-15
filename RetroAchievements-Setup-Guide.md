![retroachievements-games-emulation-notigv](https://github.com/user-attachments/assets/41fec4a5-89ea-4194-8ada-d77d73b79b92)

# RetroAchievements: The Complete Setup Guide (RetroArch, PCSX2, DuckStation & More)
**By ThatGVguy**

A fast, no-nonsense guide to setting up RetroAchievements on all major emulators. Stop guessing and start unlocking trophies! :D

**Includes:**
* Step-by-step setup for RetroArch, DuckStation, PCSX2 (Qt), PPSSPP and Dolphin.
* How to get the CORRECT ROMs (No-Intro/Redump) so achievements actually work.
* Troubleshooting tips for common login errors.

Let's get those achievements!! :D

---

## 📝 Step 1: Creating Your Account
First things first! We need to create an account so the emulators know where to send your trophies. 

1. Go to **[RetroAchievements.org](https://retroachievements.org/)**.

<img width="3440" height="1107" alt="ThatGVguy - RA - Step 1" src="https://github.com/user-attachments/assets/e97d7be6-35dd-4ef6-8e0f-3b69b9bf0b44" />

<img width="2956" height="1204" alt="ThatGVguy - RA - Step 1 (2)" src="https://github.com/user-attachments/assets/e762315f-1cde-4913-ab05-b30fff343b51" />

<img width="2911" height="1238" alt="ThatGVguy - RA - Step 1 (3)" src="https://github.com/user-attachments/assets/f27607f7-e1a9-4353-9ebd-5e3a3164185e" />

2. Click on **Sign Up** in the top right corner and fill in your details.

<img width="121" height="46" alt="ThatGVguy - RA - Step 1 (4)" src="https://github.com/user-attachments/assets/736e8cde-f861-4a2d-a48e-3133fcaf2beb" />

<img width="1986" height="728" alt="ThatGVguy - RA - Step 1 (5)" src="https://github.com/user-attachments/assets/70e571bb-cff8-4f21-bb06-4f783d8f19e6" />

<img width="1996" height="666" alt="ThatGVguy - RA - Step 1 (6)" src="https://github.com/user-attachments/assets/f1ab32eb-d3ad-49e6-8f30-4cc5a7b36160" />

<img width="1983" height="683" alt="ThatGVguy - RA - Step 1 (7)" src="https://github.com/user-attachments/assets/cce4f869-4864-480a-8534-492165465db9" />

<img width="146" height="46" alt="ThatGVguy - RA - Step 1 (8)" src="https://github.com/user-attachments/assets/6e5806cc-1953-45ca-b254-8b2a044b3856" />

3. **Important:** You will receive an email instantly. Go to your inbox and click **Verify my email**. Your account won't work without this!

<img width="1060" height="55" alt="ThatGVguy - RA - Step 1 (9)" src="https://github.com/user-attachments/assets/23b0be05-4360-47c1-8651-ecce401caab2" />

<img width="2914" height="958" alt="ThatGVguy - RA - Step 1 (10)" src="https://github.com/user-attachments/assets/31c3ed75-ab97-4add-8c72-c450569e1df6" />

4. Head back to the site, click **Sign In**, and log in.

<img width="2911" height="1238" alt="ThatGVguy - RA - Step 1 (11)" src="https://github.com/user-attachments/assets/bca04344-e24f-445e-8d0a-58a035ec025c" />

<img width="119" height="39" alt="ThatGVguy - RA - Step 1 (12)" src="https://github.com/user-attachments/assets/abc397af-0765-441b-8441-42db3a0f0b7f" />

<img width="2024" height="865" alt="ThatGVguy - RA - Step 1 (13)" src="https://github.com/user-attachments/assets/1a4d53a1-222b-4c31-8684-d1e7e463e7c4" />

<img width="2004" height="1257" alt="ThatGVguy - RA - Step 1 (14)" src="https://github.com/user-attachments/assets/f3dec6a3-0ce0-47af-b837-b582d77abf8e" />

---

## ⚠️ Hardcore vs Softcore Mode (Read This!)
Before we configure the emulators, you need to decide how you want to play. RetroAchievements has two modes, and choosing the wrong one might frustrate you!

### Hardcore Mode (Enabled by Default)
This is the pure experience. Just like playing on the original console.
* **Pros:** You get double points (2x) and a special badge on your profile.
* **Cons:** You CANNOT use Save States, Rewind, Slow Motion, or Cheats.
* *Warning: If you accidentally load a Save State, Hardcore Mode will disable itself for that session!*

<img width="376" height="56" alt="ThatGVguy - RA - Hardcore vs Softcore (1)" src="https://github.com/user-attachments/assets/e839af1a-35ca-4c3c-a9c8-52539fa31177" />

<img width="364" height="80" alt="ThatGVguy - RA - Hardcore vs Softcore (2)" src="https://github.com/user-attachments/assets/a832c0f7-59f5-4665-9e9b-ff6d041b8cd2" />

### Softcore Mode
For a more relaxed experience.
* **Pros:** You can use Save States, Rewind and play however you like.
* **Cons:** You get standard points, and they don't count for the competitive leaderboard.

<img width="264" height="73" alt="ThatGVguy - RA - Hardcore vs Softcore (3)" src="https://github.com/user-attachments/assets/220a302d-52b5-4c88-8888-123ebe7ecc2e" />

<img width="376" height="56" alt="ThatGVguy - RA - Hardcore vs Softcore (4)" src="https://github.com/user-attachments/assets/012cbbec-762a-4951-a85d-639289810031" />

**How to switch (Disable Hardcore):**
* **RetroArch:** Settings -> Achievements -> Toggle Hardcore Mode to OFF.
* **DuckStation / PCSX2:** Settings -> Achievements -> Uncheck Hardcore Mode.
* **PPSSPP:** Settings -> Tools -> RetroAchievements -> Uncheck Hardcore Mode.
* **Dolphin:** Tools -> Achievements -> Uncheck Hardcore Mode.

---

## 👾 Step 2: RetroArch Setup
RetroArch is unique because it runs many consoles inside one app using "Cores".

1. Go to **Settings** -> **Achievements**.
2. Toggle the option to **ON**.
3. Enter your Username and Password.
4. **CRITICAL STEP (Saving Your Config):** Go back to the **Main Menu** -> **Configuration File** -> **Save Current Configuration**. If you don't do this, you will lose your login when you close the app!

### Quick Tip: Which Cores Should I Use?
RetroArch has hundreds of cores, but not all of them work perfectly with achievements. Download these specific cores for the main systems:

| System | Recommended Core |
| :--- | :--- |
| **NES** | Mesen / FCEUmm |
| **SNES** | Snes9x (Current) |
| **Genesis / Mega Drive** | Genesis Plus GX |
| **Game Boy / Color** | Gambatte |
| **Game Boy Advance** | mGBA |
| **Nintendo DS** | melonDS |
| **Nintendo 64** | Mupen64Plus-Next |
| **Virtual Boy** | Beetle VB |
| **Arcade** | FinalBurn Neo |
| **PlayStation 1** | SwanStation / Beetle PSX HW |

---

## 💿 The Golden Rule: ROM Compatibility
If you started the game and nothing happened (no "Logged in" message, no achievements), the problem is your game file. RetroAchievements requires specific, clean versions of the game files. 

* **Cartridges (SNES, GBA, Genesis):** Look for **"No-Intro"** sets.
* **Disc Games (PS1, GameCube):** Look for **"Redump"** sets.

### How to Check Your Game Hash
Sometimes a file is named correctly but the data inside is wrong (Bad Dump). Here is how to check it inside RetroArch:
1. Load the game and open the **Quick Menu** (F1 on Keyboard, Guide Button on Controller, or L3+R3 on Handhelds).
2. Scroll down to **Information**.
3. Look for the line that says **RetroAchievements Hash**. That long code is your game's ID.
4. Go to the game's page on RetroAchievements.org, click on **"Supported Game Files"**, and compare your Hash. If it's not there, your ROM is invalid!

---

## 🦆 Step 3: DuckStation (PlayStation 1)
1. Open DuckStation and go to **Settings**.
2. Look for the **Achievements** tab on the left side.
3. Click on the **Login** button.
4. Enter your RetroAchievements Username and Password and click Login again.

---

## 🌌 Step 4: PCSX2 (PlayStation 2)
1. Open PCSX2 and go to **Settings**.
2. Select the **Achievements** tab on the left list.
3. Enable the checkbox that says **Enable Achievements**.
4. Click the **Login** button, enter your credentials, and click Login again.

---

## 🔵 Step 5: PPSSPP (PSP)
1. Open PPSSPP and go to **Settings**.
2. Scroll down to **Tools** on the side menu and click on **RetroAchievements**.
3. Check the box for **Enable Achievements**.
4. Enter your Username and Password and click **Log in**.

---

## 🐬 Step 6: Dolphin (GameCube / Wii)
1. Open Dolphin and look at the top menu bar.
2. Click on **Tools** -> **Achievements**.
3. Check the box that says **Enable RetroAchievements Integration**.
4. Enter your Username and Password and click **Log In**.

---

## 📝 Author's Note :D
If you made it this far, you are officially ready to turn your nostalgia into trophies! I hope this "Fast Setup" guide helps you focus on playing rather than configuring. I'd love to hear which game you are planning to master first or which console brings back the best memories in the comments below.

Happy hunting, and see you on the leaderboards!! :D

---

## 📖 Read the Full Guide
If you prefer to read this guide with rich formatting, see the step-by-step screenshots, or want to drop a comment to the community, check out the official Steam version right here:

**[Read and Favorite the Official Steam Guide Here](https://steamcommunity.com/sharedfiles/filedetails/?id=3648028210)**

---

>***Disclaimer & Acknowledgments:*** *The technical details, core recommendations, and compatibility notes in this guide were referenced from the official documentation and community resources available at RetroAchievements.org. 
>
> ***Technical Note:*** This guide is for educational purposes only. It explains how to configure open-source emulation software to connect with the RetroAchievements platform. It does not provide, host, or link to copyrighted game files (ROMs/ISOs). Users are responsible for dumping their own legally owned games.
>
> ***Credits:*** A massive thank you to the emulator developers and the achievement creators (devs) who spend countless hours designing challenges to breathe new life into our favorite classics. 
>
> ***Editing Process:*** Digital creation and language assistance tools were utilized during the final proofreading of this guide to ensure clear, concise, and accurate technical instructions.
