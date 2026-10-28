<p align="center">
  <img src="assets/frotart-banner.svg" alt="Frotart — AI and Knowledge Systems, Automation, Business Software" width="100%" />
</p>

### Hi, I'm Rashad 👋

I'm a business student in Colombo who builds the software side of a family
glass & aluminium business. That means taking a real shop, with its showroom,
fabrication, stock and paperwork, and modernizing it one practical system at a
time: retail and accounting software, automation, hiring workflows, and the
infrastructure underneath.

Along the way I've become obsessed with one problem: **how do you keep years of
decisions and project knowledge usable across several AI assistants without
trusting any one of them to remember?** My answer is a private, version-controlled
knowledge repository that ChatGPT, Claude and Gemini all work from, with every
claim labelled by how well it's verified.

### Currently building

| | Project | Status |
| --- | --- | --- |
| 🧠 | **AI knowledge continuity system** — GitHub as the knowledge repository, Google Drive as the data repository, evidence labels (`VERIFIED` · `OWNER DECISION` · `PROPOSED` · `UNVERIFIED`) and a project register that any assistant can resume from | Private · public template coming |
| 🏪 | **Retail & accounting platform** — replacing a legacy point-of-sale and accounting setup, starting with a local ERPNext pilot | Private · in pilot |
| 🔍 | **[Folder Change Auditor](https://github.com/Frotart/folder-change-auditor)** — find added, removed and modified files with SHA-256 snapshots, fully offline | Public · Python · MIT |

### Featured: Folder Change Auditor

[![Tests](https://github.com/Frotart/folder-change-auditor/actions/workflows/ci.yml/badge.svg)](https://github.com/Frotart/folder-change-auditor/actions/workflows/ci.yml)
[![Release](https://img.shields.io/github/v/release/Frotart/folder-change-auditor?color=258de0&style=flat-square)](https://github.com/Frotart/folder-change-auditor/releases)

Built while consolidating years of scattered files: before deleting or moving
anything, I wanted proof of exactly what changed. It snapshots a folder, compares
snapshots offline, and refuses to guess when something looks unsafe. Standard
library only, 71 tests, CI on Windows, Linux and macOS.

<a href="https://github.com/Frotart/folder-change-auditor">
  <img src="https://raw.githubusercontent.com/Frotart/folder-change-auditor/main/assets/demo.svg" alt="Terminal demo of folder-audit comparing two snapshots" width="640" />
</a>

```shell
pipx install git+https://github.com/Frotart/folder-change-auditor
```

### Tools I work with

<p>
  <img alt="Python" src="https://img.shields.io/badge/Python-252d39?style=flat-square&logo=python&logoColor=3776AB" />
  <img alt="GitHub Actions" src="https://img.shields.io/badge/GitHub_Actions-252d39?style=flat-square&logo=githubactions&logoColor=2088FF" />
  <img alt="Git" src="https://img.shields.io/badge/Git-252d39?style=flat-square&logo=git&logoColor=F05032" />
  <img alt="Docker" src="https://img.shields.io/badge/Docker-252d39?style=flat-square&logo=docker&logoColor=2496ED" />
  <img alt="Linux" src="https://img.shields.io/badge/Linux-252d39?style=flat-square&logo=linux&logoColor=FCC624" />
  <img alt="Windows" src="https://img.shields.io/badge/Windows-252d39?style=flat-square&logo=windows&logoColor=00A4EF" />
  <img alt="WSL" src="https://img.shields.io/badge/WSL-252d39?style=flat-square" />
  <img alt="ERPNext" src="https://img.shields.io/badge/ERPNext-252d39?style=flat-square" />
  <img alt="Cloudflare" src="https://img.shields.io/badge/Cloudflare-252d39?style=flat-square&logo=cloudflare&logoColor=F38020" />
</p>

### How I work

> Build for usefulness. Question assumptions. Document decisions. Keep improving.

- **Evidence over memory.** If it isn't verified, it's labelled as a claim.
- **Preservation first.** Nothing gets deleted until there's proof it's safe to.
- **Humans decide.** Automation does the repetitive work; people make the calls.

Most of my work stays private because it runs a real business. I publish tools
and templates when they're useful to someone else.

---

*Always learning. Always refining.*
