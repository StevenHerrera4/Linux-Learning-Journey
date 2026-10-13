
# Installing and Using Brave on Pop!_OS

**Objective:** Install and use Brave Browser in the terminal

**Operating System:** Pop!_OS (Ubuntu-based)

## Step 1 — Install curl

```bash
sudo apt install curl
```
**note:** Will ask you for admin password


## Step 2 — Download the Brave key

```bash
sudo curl -fsSLo /usr/share/keyrings/brave-browser-archive-keyring.gpg https://brave-browser-apt-release.s3.brave.com/brave-browser-archive-keyring.gpg
```

## Step 3 — Add the repository

```bash
sudo curl -fsSLo /etc/apt/sources.list.d/brave-browser-release.sources https://brave-browser-apt-release.s3.brave.com/brave-browser.sources
```

## Step 4 — Actualize package list

```bash
sudo apt update
```


## Step 5 — Install Brave

```bash
sudo apt install brave-browser
```

# Step 6 — Open Brave

```bash
brave-browser
```

## Result
Installation of Brave Browser successfully 

## Issues Encountered

NONE

## What I Learned

- I learned how to install a web browser using the Linux terminal instead of downloading it manually from a website.
- I learned how to use curl to download files directly from an official website.
- I learned how to add a third-party repository to my Linux system.
- I learned that installing software through an official APT repository allows the application to receive updates through the system's package manager.
  
  
