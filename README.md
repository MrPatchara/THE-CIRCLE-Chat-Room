<div align="center">

# 💀 **THE CIRCLE** 💀
### *Dark Web Style Chat Room Application*

![Dark Web Chat](your_animation.gif)

[![Python](https://img.shields.io/badge/Python-3.7+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Flask](https://img.shields.io/badge/Flask-2.0+-000000?style=for-the-badge&logo=flask&logoColor=white)](https://flask.palletsprojects.com/)
[![Socket.IO](https://img.shields.io/badge/Socket.IO-4.0+-010101?style=for-the-badge&logo=socket.io&logoColor=white)](https://socket.io/)
[![License](https://img.shields.io/badge/License-MIT-00FF00?style=for-the-badge)](LICENSE)

**A secure, encrypted-style chat room application with a dark web aesthetic interface**

---

</div>

## 🔥 **Features**

- 🏴 **Dark Web Aesthetic UI** - Retro hacker-style interface with green terminal colors
- 🔐 **Password-Protected Rooms** - Secure chat rooms with access codes
- 💬 **Real-Time Messaging** - Instant message delivery using WebSocket technology
- 👥 **Multi-Room Support** - Create and join multiple chat rooms simultaneously
- 🌐 **Cross-Platform** - Works on Windows, Linux, and macOS
- 🎨 **Customizable Themes** - Dark mode with retro terminal styling
- 📡 **Server-Client Architecture** - Deploy your own server for full control
- 🔑 **Admin Controls** - Room creation and management with admin codes

---

## 📋 **Table of Contents**

- [Installation](#-installation)
- [Quick Start](#-quick-start)
- [Usage](#-usage)
- [Server Setup](#-server-setup)
- [Client Setup](#-client-setup)
- [Project Structure](#-project-structure)
- [Configuration](#-configuration)
- [Contributing](#-contributing)
- [License](#-license)

---

## 🚀 **Installation**

### Prerequisites

- Python 3.7 or higher
- pip (Python package installer)

### Step 1: Clone the Repository

```bash
git clone https://github.com/yourusername/Chat-Room.git
cd Chat-Room
```

### Step 2: Install Dependencies

```bash
pip install -r requirements.txt
```

### Step 3: Verify Installation

```bash
python --version
pip list | grep flask
```

---

## ⚡ **Quick Start**

### 1. Start the Server

```bash
python server3.py
```

The server will start on `http://0.0.0.0:5000` by default.

### 2. Launch the Client

```bash
python client.py
```

Or use any of the advanced client versions:
- `c2.py` - Enhanced version with room list
- `c3.py` - Advanced features
- `c4.py` - Extended functionality
- `c5.py` - Full-featured client

### 3. Connect and Chat

1. Enter your server URL (e.g., `http://127.0.0.1:5000`)
2. Click **Connect**
3. Enter your username
4. Join an existing room or create a new one
5. Start chatting! 💬

---

## 📖 **Usage**

### Default Rooms

The server comes with pre-configured rooms:

- 💰 **DarkMarket** - Code: `root`
- 💾 **ZeroDay** - Code: `root`
- 🏴 **OnionLounge** - Code: `root`
- 🔑 **HiddenForum** - Code: `root`

### Creating a New Room

1. Enter your username
2. Enter a unique room name
3. Set a room access code
4. Enter admin code: `admin`
5. Click **Create Room**

### Joining a Room

1. Enter your username
2. Enter the room name
3. Enter the room access code
4. Click **Join Room**

### Sending Messages

- Type your message in the input field
- Press `Enter` or click **Send**
- Messages are broadcast to all users in the room

---

## 🖥️ **Server Setup**

### Local Development

```bash
python server3.py
```

### Production Deployment

#### Option 1: VPS Deployment

1. Upload server files to your VPS
2. Install dependencies: `pip install -r requirements.txt`
3. Run with process manager (e.g., `systemd`, `supervisor`):

```bash
python server3.py
```

#### Option 2: Replit Deployment

1. Import repository to Replit
2. Install dependencies
3. Run `server3.py`
4. Use the Replit URL as your server address

### Server Configuration

Edit `server3.py` to customize:

- **Port**: Change `port=5000` to your preferred port
- **Host**: Modify `host='0.0.0.0'` for specific network binding
- **Default Rooms**: Edit the `rooms_with_codes` dictionary
- **Admin Code**: Change `SECRET_ADMIN_CODE` for room management

---

## 💻 **Client Setup**

### Basic Client (`client.py`)

Simple client with core chat functionality.

### Advanced Clients

- **c2.py** - Room list display
- **c3.py** - Enhanced UI features
- **c4.py** - Extended functionality
- **c5.py** - Full-featured with login window

### Client Configuration

Edit the client file to customize:

- **Default Server URL**: Modify connection settings
- **UI Theme**: Adjust colors in `ctk.set_default_color_theme()`
- **Font**: Change `font_mono` variable

---

## 📁 **Project Structure**

```
Chat-Room/
│
├── server.py          # Basic server implementation
├── server2.py         # Enhanced server version
├── server3.py         # Full-featured server (recommended)
│
├── client.py          # Basic client application
├── c2.py              # Client v2 with room list
├── c3.py              # Client v3 enhanced
├── c4.py              # Client v4 extended
├── c5.py              # Client v5 full-featured
│
├── template/
│   └── chat.html      # Web-based chat interface
│
├── requirements.txt   # Python dependencies
├── README.md          # This file
├── LICENSE            # MIT License
└── your_animation.gif # Project animation
```

---

## ⚙️ **Configuration**

### Environment Variables

You can set these environment variables for customization:

```bash
export SERVER_PORT=5000
export SERVER_HOST=0.0.0.0
export ADMIN_CODE=admin
```

### Security Notes

⚠️ **Important**: This is a demonstration project. For production use:

- Implement proper authentication
- Use HTTPS/WSS for encrypted connections
- Add rate limiting
- Implement message encryption
- Use secure password hashing
- Add input validation and sanitization

---

## 🤝 **Contributing**

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Contribution Guidelines

- Follow PEP 8 style guidelines
- Add comments for complex logic
- Update documentation as needed
- Test your changes thoroughly

---

## 📝 **License**

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🎯 **Roadmap**

- [ ] End-to-end encryption
- [ ] File sharing capabilities
- [ ] User authentication system
- [ ] Message history persistence
- [ ] Mobile app version
- [ ] Voice chat integration
- [ ] Video chat support

---

## 💡 **Troubleshooting**

### Connection Issues

**Problem**: Cannot connect to server
- **Solution**: Check if server is running and firewall allows the port

**Problem**: "Connection refused" error
- **Solution**: Verify server URL and port number

### Room Issues

**Problem**: Cannot join room
- **Solution**: Verify room name and access code are correct

**Problem**: Room creation fails
- **Solution**: Ensure admin code is correct (default: `admin`)

---

## 📞 **Support**

- 🐛 **Report Bugs**: [Open an Issue](https://github.com/yourusername/Chat-Room/issues)
- 💬 **Discussions**: [GitHub Discussions](https://github.com/yourusername/Chat-Room/discussions)
- 📧 **Contact**: Your email here

---

## 🌟 **Acknowledgments**

- Built with [Flask](https://flask.palletsprojects.com/)
- Real-time communication via [Socket.IO](https://socket.io/)
- UI powered by [CustomTkinter](https://github.com/TomSchimansky/CustomTkinter)
- Inspired by retro terminal aesthetics

---

<div align="center">

### ⚠️ **Disclaimer**

This project is for educational and demonstration purposes only. The "dark web" styling is purely aesthetic and does not provide actual anonymity or security features.

---

**Made with 💀 by the community**

⭐ **Star this repo if you find it useful!** ⭐

[⬆ Back to Top](#-the-circle-)

</div>
