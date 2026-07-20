<h1 align="center">
  <img src="docs/assets/labo-icon.png" alt="LABO" width="56" valign="middle" /> LABO
</h1>

<p align="center">
  <a href="https://github.com/newmes/labo-local/releases"><img src="https://img.shields.io/github/v/release/newmes/labo-local?label=release&color=brightgreen" alt="Latest release" /></a>
  <a href="https://github.com/newmes/labo-local/releases"><img src="https://img.shields.io/github/downloads/newmes/labo-local/total?label=downloads" alt="Total downloads" /></a>
  <img src="https://img.shields.io/badge/macOS%20(Apple%20Silicon)%20%7C%20Windows%20%7C%20Linux-4493F8" alt="Supported platforms: macOS (Apple Silicon), Windows, Linux" />
  <a href="https://labo.parrotvox.com"><img src="https://img.shields.io/badge/Web-labo.parrotvox.com-C9A227" alt="Website" /></a>
</p>

<p align="center"><sub>English · <a href="README.ko.md">한국어</a></sub></p>

<p align="center">
  <strong>Lab Orchestrator — the AI collaboration workspace for research labs.</strong><br/>
  Meetings, literature, writing, and code — your lab's work flows through one place,<br/>
  with each researcher's own AI agent connected to the room.
</p>

<h3 align="center"><a href="https://github.com/newmes/labo-local/releases"><ins>Download LABO</ins></a></h3>

<p align="center">
  <img src="docs/assets/hero-chat-thread.png" alt="A LABO research room: lab-meeting chat on the left, a paper discussion thread with its citation pinned on the right" width="960" />
</p>

## Features

<table>
<tr>
<td width="42%" valign="middle">

### Meeting minutes → task board

Lab meetings become structured records. The action items you confirm move onto the room's kanban board — nobody re-types meeting notes into a tracker.

</td>
<td width="58%">
  <img src="docs/assets/feature-kanban.png" alt="Room task board with cards promoted from meeting notes" width="100%" />
</td>
</tr>
<tr>
<td width="42%" valign="middle">

### A paper library that fills itself

Papers cited in conversation are captured into the room's library automatically, with bibliography and PDF. Annotate them with the pen and open a discussion thread anchored to a paper when you want one.

</td>
<td width="58%">
  <img src="docs/assets/feature-journal-pdf.png" alt="A room's paper library of cited papers, with bibliography" width="100%" />
</td>
</tr>
<tr>
<td width="42%" valign="middle">

### LaTeX writing, next to your sources

Draft, revise, and compile manuscripts in the same room as your references and discussions.

</td>
<td width="58%">
  <img src="docs/assets/feature-writing.png" alt="LaTeX manuscript with live compiled preview" width="100%" />
</td>
</tr>
<tr>
<td width="42%" valign="middle">

### Room documents & experiment notes

Shared markdown docs live inside the room — experiment notes, protocols, and drafts stay next to the conversation that produced them.

</td>
<td width="58%">
  <img src="docs/assets/feature-docs.png" alt="Experiment notes as room documents" width="100%" />
</td>
</tr>
</table>

### Bring your own agent

Connect the coding-agent subscription you already have and it joins the room like a teammate: it answers mentions, files papers, and runs experiments in its own terminal session. **Claude Code and Codex** are wired up today; **Cursor** support is expanding.

LABO does not resell AI usage. Usage from the coding agent you connect is billed to your own subscription with that provider. Some features rely on separate external services (voice recognition, meeting minutes, image generation), and how they handle your data is shown in the data transfer guide.

### Local-first

The LABO desktop app ships with two profiles, and where your data lives depends on which one you choose. On the **remote** profile, rooms are hosted on LABO's servers so a team can work together. On the **local** profile, the backend runs on your own machine and your conversations, documents, and papers are stored there. You choose the profile when you set up the app.

Sharing a room with teammates is opt-in. End-to-end encryption for shared rooms is in progress: the relay is built to pass ciphertext through, but key management isn't available yet, so E2EE isn't a finished feature today.

## Install

Download the installer for your OS from the official releases page, [github.com/newmes/labo-local/releases](https://github.com/newmes/labo-local/releases):

| OS | File |
|---|---|
| Windows | `labo-desktop-*-setup.exe` |
| macOS (Apple Silicon only) | `Labo-*-arm64.dmg` |
| Linux | `Labo-*.AppImage` |

macOS builds run on Apple Silicon (M-series) only; Intel Macs are not supported.

**Verify your download.** Each release lists a SHA-256 checksum for every file. After downloading, compute the checksum of your file and confirm it matches the value on the release page before you run the installer:

- macOS / Linux: `shasum -a 256 <file>`
- Windows (PowerShell): `Get-FileHash <file> -Algorithm SHA256`

Builds are not yet code-signed, so your OS may warn you. Only bypass the warning for a file you downloaded from the official releases page above and whose checksum you have verified. Windows SmartScreen: **More info → Run anyway**. macOS Gatekeeper: **right-click → Open**.

## Early access

LABO is in invite-based early access. Request access on the [website](https://labo.parrotvox.com).

<sub>Screenshots show a demo research room with fictional people and data. UI localization (English) is in progress — screenshots will be refreshed.</sub>
