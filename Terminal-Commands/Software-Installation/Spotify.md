# Installing and Using Spotify on Pop!_OS

**Objective:** Install and use Spotify from the terminal.

**Operating System:** Pop!_OS 24.04 LTS (Ubuntu-based)

## Step 1 — Check Flatpak

```bash
flatpak --version
```

**Note:** Verify that Flatpak is installed.

## Step 2 — Check Flathub

```bash
flatpak remotes
```

**Note:** Make sure Flathub is listed as an available repository.

If Flathub is missing:

```bash
flatpak remote-add --if-not-exists flathub https://flathub.org/repo/flathub.flatpakrepo
```

## Step 3 — Install Spotify

```bash
flatpak install flathub com.spotify.Client
```

**Note:** Confirm the installation by typing `Y` when prompted.

## Step 4 — Launch Spotify

```bash
flatpak run com.spotify.Client
```

**Note:** Spotify can also be opened from the applications menu.

## Step 5 — Verify Installation

```bash
flatpak list | grep -i spotify
```

**Note:** Displays Spotify if it is installed through Flatpak.

## Result

Spotify is installed and can be launched from the terminal or applications menu.

## Issues Encountered

No specific installation errors documented.

## What I Learned

- How to install applications using Flatpak.
- How to check Flatpak repositories.
- How to launch applications from the terminal.
- How to verify installed Flatpak applications.
