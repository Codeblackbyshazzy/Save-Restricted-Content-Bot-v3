# GitHub Project Description: Save-Restricted-Content-Bot-v3

A high-performance, feature-rich Telegram bot designed to bypass content restrictions and facilitate the seamless saving of media and messages from protected channels and groups. This version (v3) is fully optimized for speed, security, and production readiness.

### 🚀 Key Features

*   **Bypass Content Restrictions**: Effortlessly save and forward content from channels and groups where "Restrict Saving Content" is enabled.
*   **Batch Extraction**: Extract and download hundreds of messages in a single command with progress tracking and customizable delays.
*   **Multi-Platform Downloader**: Integrated support for downloading high-quality video and audio from YouTube, Instagram, and other social platforms using `yt-dlp`.
*   **Secure Session Management**: Advanced login system supporting both Bot Token and User Session String with end-to-end encryption for stored credentials.
*   **Premium Membership System**: Built-in subscription management with automated payment processing, expiration tracking, and renewal reminders.
*   **Custom Branding**: Fully customizable bot name, start messages, and branding options to make the bot your own.
*   **Web Interface**: A lightweight Flask-based landing page for status monitoring and user support.

### 🛠️ Technical Highlights

*   **Hybrid Client Architecture**: Leverages both **Telethon** and **Pyrogram** for maximum compatibility and performance.
*   **Asynchronous Processing**: Fully non-blocking I/O ensures smooth operation even under heavy load.
*   **Fast Uploads**: Optimized file uploading logic with dynamic progress bars and large file splitting (up to 2GB+).
*   **Database Integration**: Robust data storage using MongoDB (Motor) for user profiles, settings, and premium status.

### 📦 Quick Setup

1.  Clone the repository.
2.  Install dependencies: `pip install -r requirements.txt`.
3.  Configure your environment variables in `config.py` or `.env`.
4.  Run the bot: `python3 main.py`.

---
*Developed with a focus on stability, security, and user experience.*
