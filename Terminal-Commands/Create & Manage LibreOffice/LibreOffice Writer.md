# Installing and Using LibreOffice Writer on Pop!_OS

**Objective:** Open and use LibreOffice Writer from the terminal to create and edit Word documents.

**Operating System:** Pop!_OS 24.04 LTS (Ubuntu-based)

## **Note:** If you already have this Office app downloaded, go to Step #3


## Step 1 — Check LibreOffice Installation
```
libreoffice --version
```

Note: Displays the installed LibreOffice version.

## Step 2 — Install LibreOffice (If Needed)

```
sudo apt install libreoffice -y
```
Note: Installs the LibreOffice suite. Will ask for the administrator password.

## Step 3 — Open LibreOffice Writer

```
libreoffice --writer
```
Use: Create and edit text documents, essays, reports, and class notes.

Microsoft Office equivalent: Word (.docx)

## Result

Successfully installed and opened LibreOffice Writer from the terminal.

## Issues Encountered

- **Command not found:** LibreOffice may not be installed.
- **File not found:** Verify the file name and directory using `ls`.
- **Document does not open:** Verify that the document exists and is supported.

## What I Learned

- 
