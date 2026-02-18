# 🚀 Universal Game Launcher

A modern, GUI-based replacement for `.bat` files. Perfect for tinkering with self-hosted game servers, emulators, and experimental hobby projects.

## 🛠️ Key Features
- **Visual Argument Manager:** Add, remove, and manage launch flags (like `-Console` or `-SetGameServer`) without editing text files.
- **Profile System:** Save different configurations for different games or test environments.
- **Built-in DNS Resolver:** Instantly convert a friend's domain name (e.g., `server.ddns.net`) into a numeric IP address.
- **Smart Working Directory:** Automatically handles the "Start In" folder so games find their textures and config files correctly.

## 📖 How it Works
1. **Choose Program:** Use the "Select Game EXE" button to find your game.
2. **IP Helper:** If you have a server domain, enter it in the DNS tool to get the current IP.
3. **Arguments:** Add your arguments (e.g., `-SetLoginServer 127.0.0.1`) one by one.
4. **Save & Launch:** Click "Save Profile" to keep your settings, then hit "Launch" to start the game!

## 📦 For Non-Developers (Standalone EXE)
If you don't have Python installed, you can download the standalone `launcher.exe` from the **Releases** section on the right side of this page.

## 🔨 Build from Source
If you wish to build the EXE yourself:
1. Install requirements: `pip install customtkinter pyinstaller`
2. Run command: `pyinstaller --noconsole --onefile --collect-all customtkinter launcher.py`
