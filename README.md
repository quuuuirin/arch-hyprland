# Archinstall

[TOC]

## 1. ISO Installation

Download ISO from [archlinux.org/download/]() -> Scroll down to Swiss Mirrors

## 2. Start Installation

### 2.1 Set Keyboard Layout

Set keyboard layout to Swiss German with this:

```
loadkeys de_CH-latin1
```

### 2.2 Set WLAN Connection

1. Start Wireless Daemon (iwctl)

        iwctl

2. Show available devices

        device list

3. Scan available networks

        station <device> scan

4. Show available networks

        station <device> get-networks

5. Connect to a network

        station <device> connect <SSID>

6. Check connection

        station <device> show


7. Exit the IWCTl with `exit`

### 2.3 Archinstall

Start the installation process with `archinstall`

#### 2.3.1 Locales

**Set locales:**

- **Keyboard Layout**: CH
- **Locale Language**: 
- **Locale Encoding**:
