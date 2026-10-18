# Installing and Using Signal on Pop!_OS

**Objective:** Install and use Signal Desktop for secure and private messaging through the terminal.

**Operating System:** Pop!_OS 24.04 LTS (Ubuntu-based)

## Step 1 — Install Required Packages

```bash
sudo apt install curl gnupg -y
```

**Note:** Installs the tools needed to download and verify Signal's official signing key. You may be asked for your administrator password.

## Step 2 — Download the Signal Signing Key

```bash
curl https://updates.signal.org/desktop/apt/keys.asc | gpg --dearmor > signal-desktop-keyring.gpg
```

**Note:** Downloads Signal's official public signing key.

## Step 3 — Add the Signing Key to the System

```bash
cat signal-desktop-keyring.gpg | sudo tee /usr/share/keyrings/signal-desktop-keyring.gpg > /dev/null
```

**Note:** Allows the system to verify packages signed by Signal.

## Step 4 — Download the Official Signal Repository

```bash
curl -o signal-desktop.sources https://updates.signal.org/static/desktop/apt/signal-desktop.sources
```

**Note:** Downloads the repository configuration for Signal Desktop.

## Step 5 — Add the Repository

```bash
cat signal-desktop.sources | sudo tee /etc/apt/sources.list.d/signal-desktop.sources > /dev/null
```

**Note:** Adds Signal's official repository to the system's APT sources.

## Step 6 — Update Package Lists

```bash
sudo apt update
```

**Note:** Refreshes the package database, including the newly added Signal repository.

## Step 7 — Install Signal Desktop

```bash
sudo apt install signal-desktop
```

**Note:** Installs Signal Desktop and its required dependencies.

## Step 8 — Open Signal Desktop

```bash
signal-desktop
```

**Note:** Launches Signal directly from the terminal.

## Step 9 — Link Signal to Your Phone

1. Open Signal on your Android or iPhone.
2. Navigate to **Settings → Linked Devices**.
3. Select the option to link a new device.
4. Scan the QR code displayed on Signal Desktop.
5. Complete the linking process.

**Note:** Signal must already be configured on your phone before linking the desktop application.

## Result

Signal Desktop is installed on Pop!_OS 24.04 LTS and can be launched from the terminal.

The application supports encrypted messages, voice calls, video calls, and file sharing.

## Issues Encountered

- No installation issues documented.
- A mobile Signal account is required to link the desktop application.

## What I Learned

- How to install software using an official APT repository.
- How to download and register a software signing key.
- How to update the Linux package database using `apt`.
- How to install and launch a desktop application through the terminal.
- How to link a Linux desktop application to a mobile device using a QR code.
