<h1 align="center">Hi, I'm Mashrafi 👋</h1>

<p align="center">
  <em>Polished tools for the Linux desktop, web apps for teams, and deep learning for medical imaging.</em>
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

I'm a CSE student and developer who likes building things that feel finished: desktop plugins that fit right into the shell, web apps with real workflows, and research code that others can reuse.

- 🧩 Building **Omarchy shell plugins** in QML, Rust and Python: sidebars, clocks, local text-to-speech
- 🗂️ Shipping **[ScrumSpecter](https://github.com/MASH2RAFI/ScrumSpecter)**, a sprint planning app for small agile teams
- 🩺 Researching **kidney segmentation in CT scans** with transformer-based U-Nets for my final-year thesis
- 🎨 Theming Hyprland so colors follow the wallpaper and every app matches

---

## Projects

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

### 🌐 Web

**[ScrumSpecter](https://github.com/MASH2RAFI/ScrumSpecter)** · [live](https://scrumspecter.vercel.app)
Sprint planning and task tracking for small agile teams: workspaces, sprints, kanban, table and calendar views, weekly routines, five roles with change requests, push reminders, burndown and velocity analytics.
<sub>Next.js · TypeScript · Hono · TanStack Query · Drizzle · PostgreSQL · Tailwind · shadcn/ui · Vercel</sub>

### 🩺 Medical imaging research

**[converter-3D-to-2D](https://github.com/MASH2RAFI/converter-3D-to-2D)**
Extracts axial, coronal and sagittal PNG slices with class masks from 3D CT volumes (KiTS23 and a Zenodo kidney abnormality dataset), keeping only slices with labels. It prepares the data for my thesis work on kidney, tumor and cyst segmentation.
<sub>Python · NIfTI</sub>

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
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch" />
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
