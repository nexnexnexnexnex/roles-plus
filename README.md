# 🤫 RolesPlus

An Among Us mod that adds a ton of exciting new roles to the game!

---

## ✅ Current Roles

* **Venter** *(Hide in vents to catch impostors | Vent access)*
* **Ghost** *(Die instantly | Can fly through walls | Suggested to set this to a low chance or disable entirely to avoid bored players)*
* **Loner** *(Neutral Killer | Vent access | Sabotage access)*
* **Slaughterer** *(5s Kill Cooldown | No Venting | No Sabotages)*
*  **Time Bomb** *(Complete all tasks in 5 minutes or you'll die | Vent access | Longer task list)*

📅 **Updates:** 2 new roles are added sometime every week!!

---

## ⚠️ Important Notice

> [!IMPORTANT]
> **RolesPlus should NOT cause any antivirus detections!** > It is **NOT** a virus and does not download anything additional to your computer. 
> 
> Please ensure you download this mod **ONLY** from this official GitHub repository. Any other websites or GitHub pages distributing this `.dll` are not maintained or owned by the creator (me).

---

## 🛠️ Installation Guide

I don't know how to properly set up BepInEx for R+, so follow these steps carefully and it should work:

1. **Download EHR:** Get Endless Host Roles from the [Official Website](https://ehr.gurge44.eu) or the [GitHub Releases Page](https://github.com/Gurge44/EndlessHostRoles/releases/).
2. **Select your Platform:** Choose the correct `.zip` file for your Among Us platform (e.g., `EHR.vX.X.X_Steam.zip` if you play on Steam).
3. **Extract:** Extract the contents of the `.zip` folder onto your desktop.
4. **Copy Files:** Copy all the extracted files and paste them directly into your main **Among Us** directory.
5. **Initial Boot:** Launch Among Us. A black console window should appear—this means BepInEx is working its magic! Close the game once it loads.
6. **Clean Up EHR Files:** * Go to `BepInEx\plugins\` and delete `EHR.dll` and `MiniRegionInfo.dll`.
   * Delete the `EHR_Logs` from your desktop and `Language` from your Among Us directory *(Note: You can keep all of this if you want, but I'm not sure if it conflicts with R+).*
7. **Install RolesPlus:** Copy your downloaded `RolesPlus.dll` and paste it into the `BepInEx\plugins\` folder.
8. **Download MiraAPI:** Download the latest version of MiraAPI from [here](https://github.com/All-Of-Us-Mods/MiraAPI/releases/)
   * Move it into `BepInEx\plugins\`
9. **Download Reactor:** Download the latest version of Reactor from [here](https://github.com/NuclearPowered/Reactor/releases/)
    * Move it into `BepInEx\plugins\`
11. **Launch & Play:** Launch Among Us, host or find a lobby, and enjoy!

---

## 📝 Critical Compatibility Notes

> [!WARNING]
> **This mod is NOT host-only!** > If you are hosting a game, **all players** in the lobby must have the exact same `Roles Plus.dll` version in their `plugins` folder. Any player who attempts to join without the `.dll` will be automatically kicked. `(Host is missing: Roles+ (X.X.X), MiraAPI (X.X.X)`

### 🌐 Recommended Regions
For the best experience, we highly recommend playing on custom modded regions:
* `Niko-NA` | `Niko-EU` | `Niko-AS` | `Niko-CN`
* `MNA` | `MAS`
