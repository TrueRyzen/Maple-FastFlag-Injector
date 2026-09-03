# Maple - Roblox FastFlag Injector

**Maple** is a powerful, feature-rich FastFlag injector for Roblox with a modern GUI, real-time memory injection, and advanced monitoring capabilities.

---

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [FastFlag Types](#fastflag-types)
- [How It Works](#how-it-works)
- [Preset Reference](#preset-reference)
- [Security and Privacy](#security-and-privacy)
- [Troubleshooting](#troubleshooting)
- [Contributing](#contributing)
- [License](#license)
- [Disclaimer](#disclaimer)
- [Support](#support)
- [Acknowledgments](#acknowledgments)

---

## Features

### Core Injection

- Real-time FastFlag injection directly into Roblox process memory
- Automatic flag type detection (FFlag, FInt, FString, FLog, etc.)
- Support for all Roblox process versions with dynamic offset sync
- Multi-process injection - handles multiple Roblox instances simultaneously
- Startup persistence - saves flags to ClientAppSettings.json for bootstrappers like Bloxstrap/Froststrap

### Auto-Reapply System

- Memory monitoring - checks flags every 10 seconds
- Automatic reinjection if values are changed or overwritten
- Tracks reinjection count for debugging
- Process-aware - attaches to new Roblox processes automatically

### Flag Management

- Visual flag editor with search functionality
- Import/Export flags via JSON
- Drag and drop JSON file support
- Preset system for quick configuration:
  - Resolution presets
  - Render distance presets
  - MSAA/sharpness presets
  - Texture quality presets
  - Grey avatar toggle

### Performance Optimizations

- FPS Unlocker - removes Roblox's framerate cap (persistent)
- Potato mode - disables animations and background to reduce RAM usage
- Memory-efficient design

### Technical Features

- Auto-sync offsets from remote sources
- Manual offset upload support (.hpp files)
- Client version compatibility checking
- Encrypted local storage for sensitive data
- Disguise mode - renames app to "Spotify" for privacy

### User Interface

- Modern, dark-themed GUI with smooth animations
- Tab-based navigation (Injector, Presets, Mods, Console, Settings)
- System tray support - minimize to tray
- Live console output with color-coded logs
- Searchable flag list
- Frameless window with custom titlebar

### Monitoring and Debugging

- Reinjection counter - tracks how many times flags were reapplied
- Detailed logging in console
- Verification system - confirms writes to memory
- Failure tracking with detailed error messages

---

## Installation

### Prerequisites

- Python 3.8 or higher
- Windows OS (Roblox is Windows-only)

### Setup

```bash
# Clone the repository
git clone https://github.com/yourusername/maple-fflag-injector.git
cd maple-fflag-injector

# Install dependencies
pip install -r requirements.txt
