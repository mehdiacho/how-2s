
---

# Setup Guide – Installing Node.js v18 (via NVM) and Git on Windows

## 1. Install NVM (Node Version Manager) for Windows

NVM lets you easily install and switch between different versions of Node.js.

1. Go to the **nvm-windows** releases page:
   [https://github.com/coreybutler/nvm-windows/releases](https://github.com/coreybutler/nvm-windows/releases)
2. Download the latest file named something like:

   ```
   nvm-setup.exe
   ```
3. Run the installer:

   * Accept the license
   * Choose the default install locations (unless you have a special reason to change them)
   * Finish the installation
4. Close and reopen your terminal (Command Prompt or PowerShell).

---

## 2. Use NVM to Install Node.js v18

1. Open **Command Prompt** or **PowerShell**.
2. Run:

   ```bash
   nvm install 18
   nvm use 18
   ```
3. Verify it worked:

   ```bash
   node -v
   ```

   You should see something like:

   ```
   v18.x.x
   ```

---

## 3. Install Git

Git is a tool for downloading and managing code.

1. Go to the Git download page:
   [https://git-scm.com/download/win](https://git-scm.com/download/win)
2. The download should start automatically — run the installer.
3. **Recommended settings during installation**:

   * Use default options for most prompts (just keep clicking **Next**).
   * When asked about the editor, you can leave it as **Vim** (default) or choose **Notepad**.
4. Verify Git installed:

   ```bash
   git --version
   ```

   You should see something like:

   ```
   git version 2.xx.x
   ```

---

✅ **At this point, Node.js v18 and Git are ready to use.**

---
