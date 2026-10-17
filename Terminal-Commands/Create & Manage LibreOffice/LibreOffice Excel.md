# Installing and Using LibreOffice Calc on Pop!_OS

**Objective:** Open and use LibreOffice Calc from the terminal to create and edit Excel spreadsheets.

**Operating System:** Pop!_OS 24.04 LTS (Ubuntu-based)

## **Note:** If you have this app already, go to Step #2

## Step 1 — Install LibreOffice Calc

```bash
sudo apt install libreoffice-calc -y
```

**Note:** Will ask for the administrator password if required.

## Step 2 — Open LibreOffice Calc

```bash
libreoffice --calc
```

**Note:** Opens LibreOffice Calc to create a new spreadsheet.

## Step 3 — Open an Existing Excel Spreadsheet

```bash
libreoffice --calc ~/Documents/Budget.xlsx
```

**Note:** The spreadsheet must already exist.

## Step 4 — Open a Spreadsheet from the Current Directory

```bash
libreoffice --calc spreadsheet.xlsx
```

**Note:** Opens an existing Excel spreadsheet from the current directory.

## Result

Successfully installed and opened LibreOffice Calc from the terminal.

## Issues Encountered

- **Command not found:** LibreOffice may not be installed.
- **File not found:** Verify the spreadsheet name and path using `ls`.
- **Formatting differences:** Some Excel features may not be fully compatible with LibreOffice.

## What I Learned

- How to install LibreOffice Calc.
- How to launch Calc from the terminal.
- How to open Excel spreadsheets.
- How to work with `.xlsx` files on Linux.
