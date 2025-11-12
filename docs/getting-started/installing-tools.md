# Installing Tools 🧰

Before you can start coding for FRC, you’ll need to set up your development environment.  
Follow the instructions below — you only need to do this once per season or computer.

---

## 🧩 1️⃣ Required Software

| Tool | Purpose | Download |
|------|----------|-----------|
| **WPILib** | Core FRC libraries and VS Code extension | [WPILib Installer](https://github.com/wpilibsuite/allwpilib/releases) |
| **Java 17** | Language used for robot code | Included with WPILib |
| **Git** | Version control system | [git-scm.com/downloads](https://git-scm.com/downloads) |
| **VS Code (WPILib Edition)** | IDE preconfigured for FRC | Installed by WPILib |
| **GradleRIO** | Build system (bundled with WPILib) | Included automatically |
| **FRC Driver Station** | For competition use only (Windows only) | [NI FRC Game Tools](https://www.ni.com/en-us/support/downloads/drivers/download.frc-game-tools.html) |

---

## 🪟 Windows Setup

1. Download and run the **WPILib Installer** (`.exe` version).  
2. Choose *“Install for this user only”* to avoid admin issues.  
3. Allow it to install **VS Code**, **Java 17**, and **GradleRIO**.  
4. Verify the installation:
   ```
   bash
   java -version
   git --version
   ```
5. Open the WPILib VS Code shortcut created by the installer — it should show the WPILib splash screen.