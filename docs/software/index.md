# Software Overview 🧠

Welcome to the software section! This area of the wiki is meant to help new developers understand how our robot code is structured, which repositories are used, and how the different components of our robot software interact.

---

## 🧩 Overview of Our Repositories

Our robot software is split across multiple repositories, each serving a specific purpose. Understanding the roles of these repos will help you navigate and contribute effectively.

** THIS IS FOR EXAMPLE ONLY. WE WILL NEED TO CLEAN OUR EXISTING REPOS AND PUT THE REMAINING HERE**

| Repository | Purpose | Notes |
|-------------|----------|-------|
| [`frc-robot-2025`](https://github.com/your-team/frc-robot-2025) | Main robot code for 2025 | Uses command-based architecture |
| [`vision`](https://github.com/your-team/vision) | Vision processing and camera tracking | Runs on a coprocessor (e.g. Raspberry Pi) |
| [`pathplanner-config`](https://github.com/your-team/pathplanner-config) | Stores autonomous path data | Editable with PathPlanner tool |
| [`team-wiki`](https://github.com/your-team/team-wiki) | This documentation | Built with MkDocs Material |

> 💡 Tip: Start by exploring the main `frc-robot-2025` repo, then gradually check out the supporting repos.

---

## 🔗 How the Software Fits Together

- **Main Robot Code**: Handles all commands, subsystems, and autonomous routines.  
- **Utilities**: Provides reusable code like math functions, logging, and configuration helpers.  
- **Simulation**: Lets you test new features safely without risking hardware.  
- **Dashboard**: Visualizes telemetry and sensor data for drivers and programmers.

---

## ⚙️ Development Setup

Before you start working with the software:

1. Ensure your development environment is installed ([Getting Started](../getting-started/index.md)).  
2. Clone the main repository and any supporting repos you need.  
3. Follow the project-specific README in each repo for setup instructions.  
4. Test locally using simulation before deploying to the robot.

---

## 📝 Next Steps

- [Repositories](repos.md) — detailed info about each repository, branches, and workflow  
- [Hardware](../hardware/index.md) — understand how subsystems map to code  
- [Team Practices](../team-practices.md) — coding conventions, Git workflow, and review process

> ⚠️ Always sync with the latest `main` branch before making changes to avoid conflicts.