# GitHub Profile Editor & Contribution Generator

A high-fidelity, interactive single-page HTML application that replicates the GitHub user profile page. This tool allows users to customize their profile details, upload an avatar, and "paint" a fake contribution graph to visualize their ideal year in code.

## 🚀 Features

### 1. Realistic UI Replica
- **Pixel-perfect design**: Matches GitHub's dark mode aesthetic, typography, and layout.
- **Responsive**: Works on desktop and mobile devices.
- **Sticky Navigation**: Functional header with search bar and navigation links.

### 2. Profile Customization
- **Avatar Upload**: Click on the profile picture (or the header avatar) to upload a custom image.
- **Editable Details**: Click on the **Name** or **Bio** to edit text directly.
- **Social Links**: Edit location, website, GitHub handle, company, Instagram, and Twitter/X handles by clicking on them.
- **Smart Links**: Automatically detects if a website URL is missing `https://` and adds it for the clickable link.

### 3. The "Secret" Contribution Editor
The contribution graph is fully interactive, but the controls are hidden by default to maintain the clean profile look.

- **Toggle Controls**: Click the **contribution count number** (e.g., "0" in "0 contributions") to reveal the editor toolbar.
- **Paint Levels**:
  - Level 0: No contributions (Gray)
  - Level 1: 1-9 contributions (Light Green)
  - Level 2: 10-19 contributions (Medium Green)
  - Level 3: 20-29 contributions (Dark Green)
  - Level 4: 30+ contributions (Bright Green)
- **Brush Sizes**:
  - **1x1**: Paint single days.
  - **2x2**: Paint a larger area.
  - **3x3**: Paint large blocks for "productive" months.
- **Interactions**:
  - **Left Click**: Paint with the selected level.
  - **Right Click**: Erase (sets level to 0).
  - **Click & Drag**: Paint continuously across multiple days.
- **Quick Actions**:
  - **Random**: Generates a random realistic contribution pattern.
  - **Clear**: Resets the entire year to zero.
  - **Max**: Fills the entire year with maximum contributions.

### 4. Date Management
- Change the year (2024-2026) to generate graphs for different time periods.
- Automatic month labels positioning.

## 🛠️ Tech Stack

- **HTML5**: Semantic structure.
- **CSS3**: Custom properties (variables), Flexbox, Grid, and responsive media queries. No external CSS frameworks.
- **Vanilla JavaScript**: DOM manipulation, event handling, and state management. No jQuery or frameworks.

## 📦 How to Use

1.  **Download** the `index.html` file.
2.  **Open** it in any modern web browser (Chrome, Firefox, Safari, Edge).
3.  **Customize**:
    - Click the avatar to change your picture.
    - Click your name or bio to edit.
    - Click the "0" contribution count to open the editor.
4.  **Create**: Paint your dream contribution graph.
5.  **Screenshot**: Take a screenshot to share your "achievements"!

## 📸 Screenshotting Tips

For the best results when capturing your creation:
1. Open your browser's Developer Tools (F12).
2. Toggle the device toolbar (Ctrl+Shift+M or Cmd+Shift+M).
3. Set the resolution to **1280px width** or higher for the full desktop experience.
4. Hide the editor toolbar (click the contribution number again) before taking the screenshot for authenticity.

## ⚖️ Disclaimer

This project is intended for **educational purposes** and **fun** only. It is a static simulation and does not interact with GitHub's servers or API in any way. Please do not use fake screenshots to mislead employers or the community.

## 📄 License

MIT License. Feel free to modify and distribute.
```
