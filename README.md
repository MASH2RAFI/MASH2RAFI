<h1 align="center">Hi, I'm Mashrafi 👋</h1>

<p align="center">
  <em>Polished tools for the Linux desktop and web apps that help teams ship.</em>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/OS-Arch%20Linux-1793D1?style=for-the-badge&logo=arch-linux&logoColor=white" alt="Arch Linux" />
  <img src="https://img.shields.io/badge/Desktop-Hyprland%20%2B%20Omarchy-89b4fa?style=for-the-badge&logo=hyprland&logoColor=white" alt="Hyprland + Omarchy" />
  <a href="https://scrumspecter.vercel.app">
    <img src="https://img.shields.io/badge/Live-ScrumSpecter-7aa2f7?style=for-the-badge&logo=vercel&logoColor=white" alt="ScrumSpecter live" />
  </a>
</p>

---

## About me

I'm a CSE student and developer who likes building things that feel finished: desktop plugins that fit right into the shell, and web apps with real workflows behind them.

- 🧩 Also building **Omarchy shell plugins** in QML, Rust and Python: sidebars, clocks, local text-to-speech
- 🗂️ Shipping **[ScrumSpecter](https://github.com/MASH2RAFI/ScrumSpecter)**, a full sprint-planning platform for small agile teams ([live](https://scrumspecter.vercel.app))
- 🎨 Theming Hyprland so colors follow the wallpaper and every app matches

---

## Projects

### ⭐ Featured: [ScrumSpecter](https://github.com/MASH2RAFI/ScrumSpecter)

<p align="center">
  <a href="https://scrumspecter.vercel.app">
    <img src="https://raw.githubusercontent.com/MASH2RAFI/ScrumSpecter/main/docs/screenshots/desktop/kanban-light.png" alt="ScrumSpecter kanban board" width="820" />
  </a>
</p>

**Sprint planning and task tracking for small agile teams.** It's built for teams that want Jira-level structure without the weight.

- 🗂️ **Table, kanban and calendar** views with drag and drop, undo and bulk edit
- 👥 **Five roles** (Admin → Viewer) with **change requests**, so everyone can suggest and leads approve
- 🔁 **Routines** that generate weekly tasks through the sprint and skip holidays and days off
- 🔔 **Push reminders**: tomorrow's tasks at 6 PM, and a nudge 30 minutes before a task ends
- 🤖 **Bulk input with an AI prompt**, so you can paste in a whole sprint in seconds
- 📈 **Burndown, velocity, capacity** and one-click Markdown sprint reports
- 📱 Installable **PWA**, dark mode, Ctrl/⌘ K quick jump, and an end-to-end Playwright test suite

<p>
  <a href="https://scrumspecter.vercel.app"><img src="https://img.shields.io/badge/▶%20Try%20it-scrumspecter.vercel.app-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Try ScrumSpecter" /></a>
  <a href="https://github.com/MASH2RAFI/ScrumSpecter"><img src="https://img.shields.io/badge/Source-GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="ScrumSpecter source" /></a>
</p>

<sub>Next.js 14 · TypeScript · Hono · TanStack Query · Drizzle ORM · PostgreSQL 17 · Tailwind + shadcn/ui · Motion · Playwright · Vercel</sub>

### 🖥️ Linux desktop and Omarchy

| Project | What it does | Stack |
| --- | --- | --- |
| **[Omablade](https://github.com/MASH2RAFI/omablade)** | IDE-like sidebars for Omarchy: browse, search and manage files, see Git status, drag files and use a quick-action wheel. Extensible with your own panes. | Rust · QML |
| **[Kronos](https://github.com/MASH2RAFI/omarchy-kronos)** | A large, customizable desktop clock on the wallpaper: bold hour numeral with orbital minute and second rings, saved layouts, multi-monitor and bar-aware placement. | QML · JavaScript |
| **[Kokoro TTS](https://github.com/MASH2RAFI/kokoro-tts-omarchy)** | Local text-to-speech for the Omarchy shell, powered by Kokoro-82M. Picks the right PyTorch build for NVIDIA, AMD, Intel or CPU. | QML · Python |
| **[Midnight Glass](https://github.com/MASH2RAFI/midnight-glass)** | Wallpaper-adaptive Omarchy theme with frosted-glass Hyprland decoration, Waybar islands and matching terminals, Nautilus and Qt apps. Every change is reversible. | Shell · Python |

```bash
# Install the plugins with Omarchy's plugin manager
omarchy plugin add https://github.com/MASH2RAFI/omablade.git --enable
omarchy plugin add https://github.com/MASH2RAFI/omarchy-kronos.git --enable
omarchy plugin add https://github.com/MASH2RAFI/kokoro-tts-omarchy
```

---

## Tech & tools

<p>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" alt="Rust" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/QML%20%2F%20Qt-41CD52?style=flat-square&logo=qt&logoColor=white" alt="QML / Qt" />
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white" alt="Bash" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat-square&logo=tailwind-css&logoColor=white" alt="Tailwind CSS" />
  <img src="https://img.shields.io/badge/Hyprland-89b4fa?style=flat-square&logo=hyprland&logoColor=white" alt="Hyprland" />
  <img src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white" alt="Vercel" />
  <img src="https://img.shields.io/badge/Neovim-57A143?style=flat-square&logo=neovim&logoColor=white" alt="Neovim" />
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git" />
</p>

---

## GitHub activity

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=MASH2RAFI&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=7aa2f7&text_color=c9d1d9&icon_color=89b4fa" alt="GitHub stats" height="165" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=MASH2RAFI&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=7aa2f7&text_color=c9d1d9" alt="Top languages" height="165" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=MASH2RAFI&theme=tokyonight&hide_border=true&background=0D1117&ring=7aa2f7&fire=bb9af7&currStreakLabel=89b4fa" alt="GitHub streak" />
</p>

---

## Connect

<p align="center">
  <a href="https://github.com/MASH2RAFI">
    <img src="https://img.shields.io/badge/GitHub-MASH2RAFI-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=MASH2RAFI&color=7aa2f7&style=flat-square&label=Profile+views" alt="Profile views" />
</p>
