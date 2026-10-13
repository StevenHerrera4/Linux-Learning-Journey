# Installing and Using Discord on Pop!_OS

**Objective:** Install and use Discord through the Linux terminal.

**Operating System:** Pop!_OS (Ubuntu-based)

## Step 1 — Download Discord

Go to the official website:

https://discord.com/download

Select **Linux → deb** and download the installation file.

## Step 2 — Navigate to Downloads

Open the terminal and enter:

```bash
cd ~/Downloads
```

**Note:** This command changes the current directory to the Downloads folder, where the Discord installation file was saved.

## Step 3 — Locate the Discord File

```bash
ls
```

**Note:** Look for a file similar to `discord-0.0.xxx.deb`. The version number may vary.

## Step 4 — Install Discord

```bash
sudo apt install ./discord-*.deb
```

**Note:** Will ask for your administrator password. Make sure there is only one matching Discord installation file.

## Step 5 — Open Discord

```bash
discord
```

## Result

Discord was successfully installed on Pop!_OS.

## Issues Encountered

NONE

## What I Learned

- I learned how to download a `.deb` installation package from an official website.
- I learned how to navigate to the Downloads directory using `cd`.
- I learned how to locate downloaded files using `ls`.
- I learned how to install a local `.deb` package using APT.
- I learned that `./` tells APT to look for a package file in the current directory.
- I learned how to open Discord directly from the Linux terminal.
