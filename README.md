## 📂 **Fortnite 11.31 AI's**
- This Repo includes the DLL AND Source Code that allows you to play with AI's in Fortnite Chapter 2 Season 1, This DLL has been gatekept by Modders since 2023 so I'm leaking it to piss them off because gatekeeping a file is stupid :)

- I also saw a video of Milxnor Showcasing his Mod he created for Chapter 2 Season 2 and I saw LOTS of comments of people asking for a release (to which he rightfully said no due to it being a personal project) and it reminded me I have a DLL that does something similar so why not release it?

---

## ✨ Features
- Allows you to play with AI's in Chapter 2 Season 1
- Works as a Game Server!

---

## 📋 Requirements
- Windows 10/11
- Visual Studio 2019/2022 with **Desktop development with C++** workload (for building from source)
- Project Reboot Launcher: [GitHub](https://github.com/Milxnor/Project-Reboot-3.0)
- LawinServer backend: [GitHub](https://github.com/Lawin0129/LawinServer)
- Fortnite 11.31 client files: [GitHub](https://github.com/n6617x/Fortnitebuilds)

---

## 🛠️ Compiling from Source (Optional, Recommended)

If you want to build your own DLL from the Source Code, follow these steps:

1. Open `11.31.sln` with **Visual Studio 2022**.
2. Change the **Configuration** from `Debug` → `Release`.
3. Set the **Platform** to `x64`.
4. Go to **Build → Build Solution**.
5. After the build completes, your compiled DLL will be located in: `\11.31\x64\Release\11.31.dll`

---

## 🚀 Installation

1. **Download Project Reboot Launcher**  
   [Project Reboot 3.0](https://github.com/Milxnor/Project-Reboot-3.0)

2. **Download LawinServer**  
   [LawinServer](https://github.com/Lawin0129/LawinServer)  
   - Run `install_packages.bat` to install dependencies.  
   - Run `start.bat` to launch the server backend.

3. **Download Fortnite 11.31**  
   [Fortnite builds](https://github.com/n6617x/Fortnitebuilds) and extract them to a folder of your choice.

4. **Configure Project Reboot Launcher**  
   - Open Project Reboot and Click `Play` then `Fortnite Version`  
   - Import the Build you Extracted, make sure its 11.31
   - go to Backend settings and set **Backend** from `embedded` to `Local`.  
   - Go to **Settings → Game Server** → **Type: Custom**.  
   - Click on **Game Server** and point it to your `11.31.dll` (replacing the `reboot.dll`)

5. **Launch Fortnite 11.31**  
   - Open the console in-game by pressing the `` ` `` (backtick) key.  
   - Type the following command and press Enter:
     ```
     open 127.0.0.1
     ```
   - The game should connect to your Local Server. (Hosted using LawinServer)

6. **Start the match**  
   - The Battle Bus will start automatically once 100 players are connected.

---

## 💻 Reboot Commands
Reboot V3 Script: [Pastebin](https://pastebin.com/4pmMgegz)

---

### ⚙️ Getting SHA256 Hash
1. Open the folder containing `11.31.dll`.  
2. Shift‑right click → **Open PowerShell window here** (or open Windows Terminal and `cd` to the folder).  
3. Run:
```powershell
Get-FileHash -Algorithm SHA256 .\11.31.dll | Format-List
```
```bash
SHA256: B4C2A4DBFBBC3E0F82D989570985996CBBB540E4C1DA9F60386D84435A1BD55E
```

Made with ❤️ by fraudian