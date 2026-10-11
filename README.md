<!--
  ============================================================
  GitHub Profile README — satya-no17
  Full dark-mode · terminal UI · crazy animations

  SETUP
  1. Copy this entire file into: satya-no17/satya-no17/README.md
  2. Copy terminal.svg into the same repo (root)
  3. Commit & push — your profile updates instantly
  ============================================================
-->

<div align="center">

<!-- ========== TERMINAL BOOT BANNER ========== -->
<img src="./terminal.svg" alt="satya@no17 dark terminal boot sequence" width="920" />

<br/>

<!-- Typing animation (dark phosphor green) -->
[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=2800&pause=900&color=39FF14&center=true&vCenter=true&multiline=true&width=680&height=80&lines=full-stack+builder+in+the+void_;shipping+ideas+faster+than+npm+install;hackathons+%C2%B7+APIs+%C2%B7+pixel+pushing)](https://git.io/typing-svg)

<p>
  <img src="https://img.shields.io/badge/mode-DARK-0d1117?style=for-the-badge&labelColor=39ff14&color=0d1117" alt="dark mode"/>
  <img src="https://img.shields.io/badge/shell-zsh-0d1117?style=for-the-badge&labelColor=58a6ff&color=0d1117" alt="zsh"/>
  <img src="https://img.shields.io/badge/status-ONLINE-0d1117?style=for-the-badge&labelColor=7ee787&color=0d1117" alt="online"/>
  <img src="https://img.shields.io/github/followers/satya-no17?style=for-the-badge&label=followers&labelColor=0d1117&color=39ff14" alt="followers"/>
</p>

</div>

---

<div align="center">

## `~/whoami`

```bash
$ cat ~/satya/identity.json
{
  "name": "Satyam Kumar",
  "handle": "satya-no17",
  "role": "Full-stack developer · Hackathon builder",
  "vibe": "ship in the dark, debug in neon",
  "currently": ["Next.js", "Node/Express", "MongoDB", "Redis", "AI toys"],
  "fun_fact": "I named half my repos after myself. Branding."
}
```

</div>

---

<div align="center">

## `~/sys/stats`

<!-- Dark terminal-style stats (tokyonight / dark) -->
<img height="165" src="https://github-readme-stats.vercel.app/api?username=satya-no17&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=39ff14&icon_color=58a6ff&text_color=c9d1d9&ring_color=39ff14" alt="GitHub stats"/>
<img height="165" src="https://github-readme-streak-stats.herokuapp.com/?user=satya-no17&theme=tokyonight&hide_border=true&background=0d1117&ring=39ff14&fire=ffa657&currStreakLabel=39ff14" alt="GitHub streak"/>

<br/>

<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=satya-no17&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=39ff14&text_color=c9d1d9" alt="Top languages"/>

<!-- Activity graph — full dark -->
<img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=satya-no17&theme=github-dark&bg_color=0d1117&color=39ff14&line=58a6ff&point=7ee787&area=true&hide_border=true" alt="Contribution activity graph"/>

</div>

---

<div align="center">

## `~/bin/toolkit`

<!-- skillicons — dark-friendly -->
<img src="https://skillicons.dev/icons?i=js,ts,react,nextjs,nodejs,express,mongodb,redis,python,cpp,html,css,tailwind,git,github,linux,vercel,vscode&theme=dark&perline=9" alt="Tech stack"/>

<br/><br/>

| Layer | Tools |
|:-----:|:------|
| **frontend** | `React` · `Next.js` · `TypeScript` · `Tailwind` |
| **backend**  | `Node` · `Express` · `MongoDB` · `Redis` |
| **systems**  | `C++` · `Python` · `Linux` · `Git` |
| **ship**     | `Vercel` · `hackathons` · `late-night commits` |

</div>

---

<div align="center">

## `~/projects --featured`

<a href="https://github.com/satya-no17/satpat">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=satya-no17&repo=satpat&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=39ff14&icon_color=58a6ff&text_color=c9d1d9" alt="satpat"/>
</a>
<a href="https://github.com/satya-no17/Sat_short">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=satya-no17&repo=Sat_short&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=39ff14&icon_color=58a6ff&text_color=c9d1d9" alt="Sat_short"/>
</a>
<br/>
<a href="https://github.com/satya-no17/sat-draw">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=satya-no17&repo=sat-draw&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=39ff14&icon_color=58a6ff&text_color=c9d1d9" alt="sat-draw"/>
</a>
<a href="https://github.com/satya-no17/Profile-Io">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=satya-no17&repo=Profile-Io&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=39ff14&icon_color=58a6ff&text_color=c9d1d9" alt="Profile-Io"/>
</a>

</div>

---

<div align="center">

## `~/snake --eat-commits`

<!-- Contribution snake (dark / green). Needs the snake Action once — see note below. -->
<img src="https://raw.githubusercontent.com/satya-no17/satya-no17/output/github-contribution-grid-snake-dark.svg" alt="snake eating contributions" />

<details>
<summary><code>// enable the snake animation (one-time)</code></summary>

<br/>

Create `.github/workflows/snake.yml` in this profile repo:

```yaml
name: Generate Snake
on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:
jobs:
  build:
    runs-on: ubuntu-latest
    permissions:
      contents: write
    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: satya-no17
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark
      - uses: crazy-max/ghaction-github-pages@v3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

Then run the workflow once from the Actions tab (`workflow_dispatch`).

</details>

</div>

---

<div align="center">

## `~/tty --live`

```text
┌────────────────────────────────────────────────────────────┐
│  satya@no17  ~  dark-session                               │
├────────────────────────────────────────────────────────────┤
│  > currently building   AI site builders · short links     │
│  > currently learning   sharper systems · cleaner UX       │
│  > open to              hackathons · collabs · weird ideas │
│  > contact              open an issue on any of my repos   │
└────────────────────────────────────────────────────────────┘
```

<p>
  <a href="https://github.com/satya-no17?tab=repositories">
    <img src="https://img.shields.io/badge/repos-browse-0d1117?style=for-the-badge&logo=github&logoColor=39ff14&labelColor=161b22&color=39ff14" alt="repos"/>
  </a>
  <a href="mailto:satyarajbarnwal2008@gmail.com">
    <img src="https://img.shields.io/badge/mail-ping_me-0d1117?style=for-the-badge&logo=gmail&logoColor=58a6ff&labelColor=161b22&color=58a6ff" alt="email"/>
  </a>
</p>

<br/>

<img src="https://komarev.com/ghpvc/?username=satya-no17&label=profile%20views&color=39ff14&style=for-the-badge" alt="profile views"/>

<br/><br/>

```diff
+ session saved.
+ logout successful.
# thanks for scrolling this far, human.
```

</div>


<!--
**satya-no17/satya-no17** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
