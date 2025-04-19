
# 🎮 GTA Vice City - Master Fix & Enhancement Plan

## 🔧 Problem:
**"Cannot find 640x480 video mode"** error when launching GTA Vice City on a modern laptop (Lenovo, Windows 11).

---

## ✅ Solution Summary

### 1. Delete Corrupt Settings
- Navigate to:
  ```
  C:\Users\<YourUsername>\Documents\GTA Vice City User Files
  ```
- Delete `gta_vc.set`

---

### 2. Compatibility Settings (Optional)
- Right-click `gta-vc.exe` → Properties → Compatibility Tab
  - ✅ Run in Compatibility mode for **Windows XP (SP2)**
  - ✅ Disable Fullscreen Optimizations
  - ✅ High DPI Settings → Override → **Application**
  - ✅ Run as Administrator

---

### 3. Use SilentPatch + Ultimate ASI Loader
#### 📦 Files Needed:
- **SilentPatch for GTA VC**: [Download from GitHub](https://github.com/CookiePLMonster/SilentPatch/releases)
- **Ultimate ASI Loader**: [Download from GitHub](https://github.com/ThirteenAG/Ultimate-ASI-Loader/releases)

#### 🧩 How to Install:
- Extract the following to your GTA VC folder:
  - From SilentPatch:
    - `SilentPatchVC.asi`
    - `SilentPatchVC.ini`
  - From ASI Loader:
    - `dinput8.dll` (From **Win32** column)

#### 📁 Game Path:
```
D:\NFS\GTA.Vice.City(GamingBeasts.com)\Grand Theft Auto - Vice City\
```

#### ✅ Launch `gta-vc.exe` — game should now run without error.

---

## 🌇 Enhancements & Mods

### 🎨 Visual Upgrades

1. **SkyGFX for VC**  
   PS2-style lighting, better color, reflections  
   🔗 [SkyGFX GitHub](https://github.com/aap/SkyGFX)

2. **Project2DFX**  
   Extends draw distance, makes city feel alive  
   🔗 [Project2DFX GitHub](https://github.com/ThirteenAG/III.VC.SA.IV.Project2DFX)

3. **HD Textures**  
   Search: *“Vice City HD Texture Pack”* on libertycity.net or moddb.com

4. **ENB Series / Reshade Preset**  
   Adds modern effects like bloom, ambient occlusion (optional)

---

### 🔥 Cheat Menu / Trainer

#### 🔧 Recommended:
- **VC Ultimate Trainer v2.0 or v3.0**  
  🔗 [Search on LibertyCity](https://libertycity.net/files/gta-vice-city/)

  - God mode, money, teleport, car spawn, mission select  
  - Just run alongside the game or drop `.asi` into game folder

---

### ⏩ Skip to Favorite Mission

#### 🗂 Method:
1. Download a save file:  
   🔗 [GTA VC Save Files - LibertyCity](https://libertycity.net/files/gta-vice-city/saves/)

2. Paste it into:
   ```
   C:\Users\<YourUsername>\Documents\GTA Vice City User Files
   ```

3. Load the save from in-game

Or use the trainer’s mission skip feature.

---

## 💾 Optional Mods

- Better Radios (higher quality)
- First-Person Mod
- Modern HUD / GPS
- Weapon & Vehicle Packs

---

## 🏁 You're Set!
Vice City is now:
- Working on your modern system 🧠
- Boosted with HD mods 🌇
- Powered up with cheat tools 🚀
- Ready to replay your childhood 💖

**Tommy Vercetti, welcome back.**
