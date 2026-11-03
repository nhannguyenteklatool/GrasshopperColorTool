# Grasshopper Color & Nickname Tool

A lightweight, productivity-boosting plugin for **Rhino Grasshopper** (Rhino 7 & Rhino 8 on Windows).  
Easily customize colors, opacity, and batch-rename **Nodes**, **Panels**, and **Groups** directly from the Canvas Toolbar without cluttering your canvas with extra definition components!

---
## 📥 Installation Guide

### Step 1: Unblock the File (Critical for Windows)
When downloading `.gha` or `.zip` files from the internet, Windows automatically blocks them for security:
1. Right-click on `GrasshopperColorTool.gha` (or the downloaded `.zip` before unzipping).
2. Select **Properties**.
3. In the **General** tab, check the **Unblock** checkbox at the bottom.
4. Click **Apply** $\rightarrow$ **OK**.

### Step 2: Copy to Grasshopper Libraries
Copy `GrasshopperColorTool.gha` into your Grasshopper Libraries folder:
```
%APPDATA%\Grasshopper\Libraries\
```
*(Full typical path: `C:\Users\<YourUsername>\AppData\Roaming\Grasshopper\Libraries\`)*

> **Tip:** You can quickly open this folder from Grasshopper by going to:  
> **File $\rightarrow$ Special Folders $\rightarrow$ Components Folder**.

### Step 3: Restart Rhino & Grasshopper
Restart Rhino and launch Grasshopper. You will see the new **Color Wheel button** appear on the Canvas Toolbar right above your canvas!

---

## ✨ Features

- **12-Segment Vivid Color Wheel**:
  - Intuitive donut color wheel featuring 12 high-saturation, high-brightness colors (based on the standard color wheel clockwise from Yellow at 12 o'clock).
  - Center hole shows real-time color + transparency preview.
  - Live preview mode automatically updates canvas selection as you drag or click.

- **Precision Opacity / Transparency (0 – 100%)**:
  - Smooth slider controlling alpha channel from 0 (completely transparent) to 100% (fully opaque).

- **Batch Nickname Renaming**:
  - Supports batch-renaming for:
    - **Nodes / Components / Parameters** (Point, Curve, Sliders, Math components, etc.)
    - **Panels**
    - **Groups**
  - Component capsules automatically resize dynamically to fit new names.

- **Strict Selection Conflict Prevention**:
  - Enforces single-category selection: select multiple Nodes, multiple Panels, or multiple Groups.
  - Automatically disables controls and warns if mixed types are selected, preventing accidental formatting errors.

- **Smart Copy & Paste Style**:
  - **Copy from Selected**: Captures both color and nickname into internal clipboard.
  - **Color**: Paste only the color to target Panels or Groups.
  - **Nickname**: Paste only the nickname across multiple target objects.
  - **Paste All**: Simultaneously apply both color and nickname in one click.

- **Native Canvas Integration (No Canvas Nodes Needed)**:
  - Accessible via a dedicated **Color Wheel icon on the Canvas Toolbar** (the top toolbar above the canvas).
  - Main menu integration: **Edit $\rightarrow$ Color & Nickname Tool...**
  - Global shortcut: **`Ctrl + Shift + C`**.
  - Attached directly to Grasshopper's editor window (`TopMost = false`): it floats above Grasshopper without getting in the way when you switch to other applications.

---

## 💻 Compatibility

| Platform | Supported Versions | Notes |
| :--- | :--- | :--- |
| **Windows** | **Rhino 7** | Native (.NET Framework 4.8) |
| **Windows** | **Rhino 8** | Fully supported via backwards compatibility |
| **macOS** | Not supported | Windows Forms / GDI+ architecture |

---


## 🎮 How to Use

1. Click the **Color Wheel icon** on the Canvas Toolbar (or press **`Ctrl + Shift + C`**).
2. Select any object(s) on canvas:
   - Select multiple **Nodes** to batch-rename their nicknames.
   - Select multiple **Panels** or **Groups** to change both color and nickname.
3. Use **Copy from Selected** and **Paste** buttons to transfer styles between objects effortlessly.
4. When finished, simply click the toolbar button again or press `[X]` to close the window.

---
# Grasshopper Color & Nickname Tool

[⬇️ Download GrasshopperColorTool_v1.0.0.zip](https://github.com/nhannguyenteklatool/GrasshopperColorTool/releases/download/v1.0.0/GrasshopperColorTool_v1.0.0.zip)

[![Downloads](https://img.shields.io/github/downloads/nhannguyenteklatool/GrasshopperColorTool/total)](https://github.com/nhannguyenteklatool/GrasshopperColorTool/releases)
[![Release](https://img.shields.io/github/v/release/nhannguyenteklatool/GrasshopperColorTool)](https://github.com/nhannguyenteklatool/GrasshopperColorTool/releases/latest)

A lightweight, productivity-boosting plugin for **Rhino Grasshopper** (Rhino 7 & Rhino 8 on Windows)...

---

## 📄 License
This project is released under the **MIT License**. Free for personal and commercial use.
