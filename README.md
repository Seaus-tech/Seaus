# 🌊 Seaus - Next Generation Productivity Suite

<p align="center>
  <strong>A modern SwiftUI productivity application for macOS and iOS.</strong>
</p>

<p align="center>
  <img src="https://img.shields.io/badge/Platform-iOS%20%7C%20macOS-blue?style=flat-square&logo=apple" alt="Platforms" />
  <img src="https://img.shields.io/badge/Language-Swift-F54A46?style=flat-square&logo=swift" alt="Swift" />
  <img src="https://img.shields.io/badge/Framework-SwiftUI-F54A46?style=flat-square&logo=swift" alt="SwiftUI" />
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square" alt="License" />
</p>

---

## 📖 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Screenshots](#screenshots)
- [Installation](#installation)
- [Usage](#usage)
- [System Requirements](#system-requirements)
- [Codebase Structure](#codebase-structure)
- [Development](#development)
- [Roadmap](#roadmap)
- [Contributing](#contributing)

## Overview

Seaus is a next-generation productivity suite built with SwiftUI for Apple platforms. This application provides a clean, intuitive interface for managing tasks, notes, and productivity workflows across iOS and macOS.

## Features

| Feature | Description |
|---------|-------------|
| 📱 **Cross-Platform** | Native support for iOS and macOS |
| 🎨 **Modern Design** | Built entirely with SwiftUI |
| ⚡ **Swift Performance** | Native Apple Silicon and Intel support |
| 🛠️ **Tool Integration** | Built-in productivity tools |
| 🔄 **Sync** | CloudKit synchronization across devices |
| 🌙 **Dark Mode** | Full dark mode support |

## Screenshots

*(Coming soon)*

## Installation

### From Source

```bash
# Clone the repository
git clone https://github.com/Seaus-tech/Seaus.git
cd Seaus

# Open in Xcode
open Seaus.xcodeproj
```

### Build

Select your target device and press `Cmd + R` in Xcode.

## Usage

Seaus provides a unified interface for:

- Task management
- Note taking
- Calendar integration
- Focus tracking

## System Requirements

- Xcode 15.0 or later
- iOS 17.0+ or macOS 14.0+ deployment target
- Apple Silicon or Intel Mac

## Codebase Structure

```
Seaus/
├── Seaus/                    # Main source directory
│   ├── SeausApp.swift        # Main application entry point
│   ├── ContentView.swift     # Primary view
│   ├── Views/                # UI components
│   ├── Models/               # Data models
│   ├── Services/             # Business logic
│   └── Tools/                # Productivity tool modules
└── Seaus.xcodeproj/         # Xcode project file
```

## Development

This project follows modern SwiftUI patterns with a clean architecture. Key files:

- `SeusApp.swift` - The main entry point, launches `ContentView` within a `WindowGroup`
- `ContentView.swift` - Primary view with navigation and tool integration

## Roadmap

- [ ] Add task collaboration features
- [ ] Implement AI-powered productivity insights
- [ ] Add watchOS companion app
- [ ] Create widget support

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

© 2026 Seaus Tech. All rights reserved.