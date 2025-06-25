# Zonos-for-Windows (CPU-Only, Easy Setup) 🚀

A lightweight, CPU-only setup for Zonos, tested on Windows 64-bit with 8GB RAM and Intel i5-4590.

# YouTube Channel Promotion 📺

Check out my YouTube channel: [AmiXDme](https://www.youtube.com/@AmiXDme)

# Quick Start 🛠️

Follow these steps to set up **Zonos-for-Windows (CPU-Only)** (64-bit).

## 1. Install Python 3.10+ (64-bit) 🐍

- Download from [python.org](https://www.python.org/).
- During installation, check **"Add Python to PATH"**.

## 2. Clone the Repository 📦

```powershell
git clone https://github.com/AmiXDme/-Zonos-for-Windows-CPU-Only.git
```

```powershell
cd Zonos-for-Windows-CPU-Only
```

## 3. Create and Activate a Virtual Environment 🌐

```powershell
python -m venv .venv
```

```powershell
.venv\Scripts\Activate.ps1
```

## 4. Install Dependencies 📚

```powershell
pip install -e .
```

## 5. Install eSpeak NG 🔊

- Download from [eSpeak NG Releases](https://github.com/espeak-ng/espeak-ng/releases).
- Install and add the directory (e.g., `C:\Program Files\eSpeak NG\`) to your system PATH if prompted.

## 6. Run the Gradio Web UI 🌐

- Right-click `2_run_gui.ps1` and select **"Run with PowerShell"**.

# Troubleshooting ⚠️

- **CUDA/GPU errors**: Ensure a CPU-only setup. Reinstall dependencies in a clean virtual environment.
- **eSpeak not found**: Verify eSpeak NG is installed and added to your system PATH.
- **Out-of-memory errors**: Use shorter text or audio inputs. 8GB RAM is the minimum requirement.

# Features ✨

- **CPU-Only** 💻: No GPU or CUDA required.
- **Voice Cloning** 🗣️: Supports multilingual text-to-speech (TTS).
- **Simple Setup** 🛠️: Easy installation and usage.
- **Gradio Web UI** 🌐: User-friendly interface for testing.

# Credits

Inspired from [sdbds/Zonos-for-windows](https://github.com/sdbds/Zonos-for-windows)