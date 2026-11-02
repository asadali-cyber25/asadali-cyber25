# Repository & Workflows Overview

This is the special profile repository for **`asadali-cyber25`**. Contents in `README.md` are automatically featured on your GitHub profile page (`https://github.com/asadali-cyber25`).

---

## ⚡ Active Animation Workflows

### 1. 🐍 Contribution Snake Animation (`.github/workflows/snake.yml`)
- **Action:** `Platane/snk@v3`
- **Output:** Generates animated SVG and GIF files of a snake consuming your GitHub contribution activity.
- **Branch:** Deployed automatically to the `output` branch.
- **Triggers:** Runs automatically every 12 hours, on every push to `main`, or manually via GitHub Actions tab (*workflow_dispatch*).
- **Styling:** Custom Obsidian and Cyber Red palette (`#e8212b`).

### 2. 🌐 3D Isometric Contribution Calendar (`.github/workflows/profile-3d.yml`)
- **Action:** `yoshi389111/github-profile-3d-contrib@latest`
- **Output:** Generates isometric 3D contribution graphs under `profile-3d-contrib/`.
- **Triggers:** Runs daily at 18:00 UTC, on push to `main`, or manually via GitHub Actions tab.

---

## ⚙️ Repository Permissions
- GitHub Actions workflow permissions have been set to **Read and write permissions** (`GITHUB_TOKEN` write access) to allow automated deployment of animations to the repository and the `output` branch.
