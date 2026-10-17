# Installing and Using LibreOffice Impress on Pop!_OS

**Objective:** Open and use LibreOffice Impress from the terminal to create and edit PowerPoint presentations.

**Operating System:** Pop!_OS 24.04 LTS (Ubuntu-based)

## **Note:** If you already have this app, move to Step #2


## Step 1 — Install LibreOffice Impress

```bash
sudo apt install libreoffice-impress -y
```

**Note:** Will ask for the administrator password if required.

## Step 2 — Open LibreOffice Impress

```bash
libreoffice --impress
```

**Note:** Opens LibreOffice Impress to create a new presentation.

## Step 3 — Open an Existing PowerPoint Presentation

```bash
libreoffice --impress ~/Documents/Presentation.pptx
```

**Note:** The presentation must already exist.

## Step 4 — Open a Presentation from the Current Directory

```bash
libreoffice --impress slides.pptx
```

**Note:** Opens an existing PowerPoint presentation from the current directory.

## Result

Successfully installed and opened LibreOffice Impress from the terminal.

## Issues Encountered

- **Command not found:** LibreOffice may not be installed.
- **File not found:** Verify the presentation path using `ls`.
- **Formatting differences:** Some PowerPoint animations, transitions, or fonts may behave differently in LibreOffice.

## What I Learned

- How to install LibreOffice Impress.
- How to launch Impress from the terminal.
- How to open PowerPoint presentations.
- How to work with `.pptx` files on Linux.
