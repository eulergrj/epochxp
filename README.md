# EpochXP  
*A 3.3.5 port of RestedXP (for the Epoch server)*  

## Overview  
EpochXP is a **recreation of the RestedXP leveling addon**, rebuilt from the ground up to work on **World of Warcraft 3.3.5 servers**.  

The original RestedXP addon relies heavily on modern APIs and logic that simply aren’t compatible with 3.3.5. This project rewrites the internals while keeping the overall experience close to the original.  


I originally created EpochXP for **my own personal use**, but a few friends asked me to share it. I reached out to the **RestedXP team**, and they were kind enough to give me the green light to use their guides in this project and to share them.  

👉 If you like the guides themselves and want to support the amazing people behind them, please check out [RestedXP](https://www.restedxp.com/).  

---

## Requirements  
- **[TomTom](https://www.wowinterface.com/downloads/info7032-TomTom.html)** (required for waypoints).  
- WoW 3.3.5 client.  

---

## Installation  
1. Download the latest release of EpochXP.  
2. Extract the folder into your `Interface/AddOns/` directory.  
3. Install [TomTom](https://www.wowinterface.com/downloads/info7032-TomTom.html) as well.  
4. Restart WoW and enable EpochXP in your AddOns menu.  


---

## Supporting the Project  
If you find EpochXP useful and would like to support me, you can:  

[![Ko-fi](https://img.shields.io/badge/Support%20me%20on-Ko--fi-ff5f5f?style=for-the-badge&logo=ko-fi&logoColor=white)](https://ko-fi.com/eulergrj)  

Your support helps motivate me to continue improving and maintaining the addon.  

---

## Known Issues  
- ⚠️ **Some steps won’t auto-complete** and must be marked complete manually.  
- ⚠️ **Not all guides have been fully tested.** If you encounter issues, please raise them under *Issues* in Github, and I’ll get to them when I can.  
- ⚠️ **Waypoints may sometimes not generate correctly.** If that happens, click the minimap icon to hide/show the window, this will recreate them.  
- ⚠️ **New zones introduced for Epoch** (such as the updated Stormwind, Goldshire, etc.) do not have correct waypoints, since the original guides were written for Classic-era maps.  
- The addon is a **work-in-progress**, there may be rough edges until more polish is added.  

---

## Troubleshooting  
If you run into problems, here are some quick things to try:  

- 🔄 **Reload your UI** with the `/reload` command — this fixes many display issues.  
- 🗺️ **Waypoints missing or wrong?** Toggle the window by clicking the minimap icon to regenerate them.  
- 🧹 **Addon settings corrupted?** Close WoW and delete the file:  


WTF/Account/<*YourAccountName*>/SavedVariables/EpochXP.lua

This will reset EpochXP to defaults.  
- 🧩 **TomTom not working?** Make sure you have installed the correct version of [TomTom for 3.3.5](https://www.wowinterface.com/downloads/info7032-TomTom.html).  

If none of the above helps, please raise an *Issue* in GIT with as much detail as possible (steps to reproduce, screenshots, error messages, etc.).  

---

## Credits  
- **RestedXP** for their guides and support in allowing this project to exist.  
- **TomTom** addon for waypoint functionality.  
- The WoW private server community for testing and feedback.  

---

## Disclaimer  
- This addon is **not officially affiliated with RestedXP**. It is a fan-made project.  
- Please support the original RestedXP team if you enjoy their guides.  
