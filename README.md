
# Risc-Vera - A Linux-Based OS for Education

## 🚀 Overview

Risc-Vera is a lightweight, Linux-based operating system designed to enhance the educational experience. It provides students and educators with a powerful, distraction-free environment equipped with pre-installed tools for coding, collaboration, and learning.

## 🎯 Features

### **Phase 1: CLI-Based Version (Core Foundation)**

✅ **Lightweight & Optimized** – Runs efficiently on low-end hardware.
✅ **User-Friendly CLI** – Simple and intuitive command-line interface with Bash/Zsh support.
✅ **Multi-User Support** – Role-based access for students, teachers, and admins.
✅ **Pre-installed Development Tools** – Python, Java, GCC, Git, Vim, and Nano.
✅ **Offline Learning Resources** – Kiwix for Wikipedia, dictionary, and math tools.
✅ **Networking & Collaboration** – SSH for remote access, terminal-based chat.
✅ **Productivity Tools** – Pomodoro timers, note-taking CLI apps.
✅ **Security & Kiosk Mode** – Lock features during exams, parental control settings.

### **Phase 2: XFCE-Based GUI Version (Full OS)**

✅ **Lightweight XFCE Desktop** – Optimized for performance and ease of use.
✅ **Pre-installed Educational Software** – LibreOffice, GeoGebra, Stellarium, GCompris.
✅ **Coding IDEs** – VS Code, PyCharm, Code::Blocks, Arduino IDE.
✅ **Virtual Labs** – Interactive simulations for physics, chemistry, and programming.
✅ **Collaboration Tools** – Screen sharing, remote assistance, and cloud sync.
✅ **Focus Mode** – Distraction-free learning environment with time management tools.
✅ **Security & Customization** – Role-based access, parental controls, Kiosk mode.

## 🏗️ Installation

### **Requirements**

- Minimum **2GB RAM**, **20GB Storage**, and a **64-bit processor**.
- Internet connection (for package updates).

### **Installation Steps**

1. **Download the ISO** – [Link Coming Soon]
2. **Create a Bootable USB**
   ```sh
   sudo dd if=Risc-Vera.iso of=/dev/sdX bs=4M status=progress
   ```


*(Replace `/dev/sdX` with your USB drive)*

3. **Boot from USB** – Select Risc-Vera in BIOS boot options.
4. **Follow On-Screen Instructions** – Install using CLI or GUI.

## 🔧 Development Setup

If you want to contribute or customize Risc-Vera, follow these steps:

1. **Clone the Repo**
   ```sh
   git clone https://github.com/YourUsername/Risc-Vera.git
   cd Risc-Vera
   ```
2. **Run the OS in a Virtual Machine**
   ```sh
   qemu-system-x86_64 -cdrom Risc-Vera.iso -m 2048
   ```

## 🤝 Contributing

We welcome contributions! Open an issue or submit a pull request to help improve Risc-Vera.

## 📜 License

Risc-Vera is open-source and licensed under the MIT License.

## 📞 Contact

For queries or contributions, reach out at kushagra.kushagra@sitpune.edu.in / om.dhamame.btech2023@sitpune.edu.inor open an issue in the GitHub repository.

---
