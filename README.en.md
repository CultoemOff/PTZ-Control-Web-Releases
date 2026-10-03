# PTZ Control Web — by Culto em Off

**PTZ Control Web – Free PTZ Camera Controller for OBS, vMix & SPresenter**

[Português](README.md) · [English](README.en.md) · [Español](README.es.md)

[⬇️ Download for Windows](https://github.com/CultoemOff/PTZ-Control-Web-Releases/releases/latest)

Control PTZ cameras directly from your browser, inside your production software, or as a standalone control panel.

**PTZ Control Web — by Culto em Off** is a local web interface for PTZ camera control. It was designed for churches, live streaming, audiovisual productions and teams that need a simple, compact controller.

The application runs locally on Windows and its interface is opened in a browser. It can also be embedded directly in **OBS Studio as a Custom Browser Dock**.

## 📥 Download

Always download the latest version from:

https://github.com/CultoemOff/PTZ-Control-Web-Releases/releases/latest

Under **Assets**, download:

- `PTZ-Control-Web-Setup.exe`
- `SHA256SUMS.txt` — SHA-256 hash for installer integrity verification.

## 🖥️ Installation

1. Download `PTZ-Control-Web-Setup.exe`.
2. Run the installer.
3. Complete the installation normally.
4. PTZ Control Web will be configured to start with Windows.
5. A **PTZ Control Web** shortcut will be created to open the control panel in your browser.

The server runs locally on your computer and does not require an internet connection to control cameras on your local network.

## 🌐 How to open PTZ Control Web

After installation, open:

`http://127.0.0.1:8765/obs`

You can bookmark this address in your browser.

You can also use the **PTZ Control Web** shortcut created during installation.

> `127.0.0.1` means the server runs on the same computer. By default, the interface is not exposed to other devices on the network.

## 🎥 How to add it to OBS Studio

In OBS Studio, open:

**Docks → Custom Browser Docks**

Create a new dock with:

**Name:** `PTZ Control Web`

**URL:** `http://127.0.0.1:8765/obs`

Click **Apply**. The PTZ Control Web panel will appear inside OBS and can be dragged and docked with the other panels.

## 🎛️ Where it works

- **OBS Studio** as a Custom Browser Dock
- **vMix**
- **SPresenter**
- web browser
- **Bitfocus Companion**
- USB/Gamepad controller

Because the controller uses a local server and a browser interface, it does not depend on a specific internal OBS Studio plugin.

## 🎥 Features

- Pan, Tilt and Zoom
- diagonal movement
- Home command
- Focus Near / Far
- Autofocus
- adjustable Pan/Tilt speed
- camera presets with save, recall and custom names
- support for up to **8 cameras**
- up to **4 cameras per row**
- Portuguese, English, Spanish and German interfaces
- light and dark themes
- configurable preset count
- horizontal or vertical layout
- option to hide PTZ controls
- USB Gamepad control
- HTTP integration with Bitfocus Companion
- locally persisted configuration
- Auto Tracking on compatible ONVIF cameras

## 📷 Protocols and camera profiles

Supported protocols:

- **VISCA over IP — UDP**
- **VISCA over IP — TCP**
- **VISCA USB / Serial**
- **ONVIF**

Camera manufacturer profiles:

- **Generic**
- **AVer**
- **Telycam**
- **PTZOptics**
- **Sony**

Use the **Generic** profile for compatible cameras that are not listed.

Some features, such as **Auto Tracking**, depend on support provided by the camera itself.

## 🎮 USB / Gamepad control

The current mapping includes the left stick for Pan/Tilt, triggers for Zoom, shoulder buttons for Focus, D-Pad for preset selection and buttons for recalling, saving and triggering Autofocus.

## 🔲 Bitfocus Companion

The HTTP integration allows Companion buttons for camera movement, stop, Zoom, Focus, Autofocus, Home, preset recall and preset save.

## 🔐 Security

By default, the server listens only on:

`127.0.0.1`

This means the interface and API are accessible only from the computer where PTZ Control Web is installed.

Camera settings are stored locally.

## 🔎 PTZ Camera Controller

PTZ Control Web is a free browser-based PTZ camera controller for **OBS Studio, vMix and SPresenter**, with support for **VISCA over IP (UDP/TCP)**, **VISCA USB/Serial**, **ONVIF**, presets, Pan/Tilt/Zoom, focus, USB/Gamepad control, Auto Tracking on compatible devices and HTTP integration with **Bitfocus Companion**.

**Keywords:** PTZ controller, PTZ camera controller, PTZ web controller, OBS PTZ controller, VISCA controller, VISCA over IP, ONVIF PTZ, USB PTZ controller, Bitfocus Companion PTZ, vMix PTZ, SPresenter PTZ, church livestream PTZ.

## 🎥 About Culto em Off

**Culto em Off** is a channel created to share practical knowledge about **audio, video, streaming and technology for churches**.

Content includes live audio consoles, OBS Studio and streaming, cameras and PTZ, NDI, lighting and automation, REAPER, Holyrics, SPresenter, networking, equipment integration and practical tutorials for church production teams.

▶️ **YouTube:** https://www.youtube.com/@CultoemOff

---

**PTZ Control Web — by Culto em Off**

Created by **Jonas — Brazil 🇧🇷**
