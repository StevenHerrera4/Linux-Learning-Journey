# Installing and Using LibreOffice Math on Pop!_OS

**Objective:** Open and use LibreOffice Math from the terminal to create mathematical equations and formulas.

**Operating System:** Pop!_OS 24.04 LTS (Ubuntu-based)

## Step 1 — Install LibreOffice Math

```bash
sudo apt install libreoffice-math -y
```

**Note:** Will ask for the administrator password if required.

## Step 2 — Open LibreOffice Math

```bash
libreoffice --math
```

**Note:** Opens the LibreOffice formula editor.

## Step 3 — Create a Mathematical Formula

In LibreOffice Math, enter:

```text
a^2 + b^2 = c^2
```

**Note:** LibreOffice Math uses its own formula syntax to display mathematical expressions.

## Step 4 — Open an Existing Math Document

```bash
libreoffice --math ~/Documents/Formula.odf
```

**Note:** The formula document must already exist.

## Result

Successfully installed and opened LibreOffice Math from the terminal.

## Issues Encountered

- **Command not found:** LibreOffice may not be installed.
- **Formula syntax errors:** Check the mathematical expression.
- **File not found:** Verify the file location using `ls`.

## What I Learned

- How to install LibreOffice Math.
- How to launch Math from the terminal.
- How to write mathematical expressions.
- How to open existing LibreOffice formula documents.
