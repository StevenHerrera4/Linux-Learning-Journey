# Creating and Opening Word Documents from the Terminal on Pop!_OS

**Objective:** Learn how to navigate directories, create Word documents, and open existing documents using LibreOffice Writer from the Linux terminal.

**Operating System:** Pop!_OS 24.04 LTS (Ubuntu-based)

## Step 1 — Enter the Documents Directory

```bash
cd ~/Documents
```

**Note:** `cd` stands for Change Directory. The `~` represents the user's home directory.

## Step 2 — List Available Folders

```bash
ls
```

**Note:** Displays all visible files and folders inside the Documents directory.

## Step 3 — Enter an Existing Class Folder

```bash
cd ENG-111
```

**Note:** Changes the current directory to the ENG-111 folder.

## Step 4 — Verify the Current Directory

```bash
pwd
```

**Expected Output:**

```text
/home/steven/Documents/ENG-111
```

**Note:** `pwd` stands for Print Working Directory.

## Step 5 — List Existing Documents

```bash
ls -lah
```

**Note:** Displays existing files, including hidden files, their permissions, and sizes.

## Step 6 — Open LibreOffice Writer

```bash
libreoffice --writer
```

**Note:** Opens LibreOffice Writer to create a new document.

## Step 7 — Create and Save a Word Document

Inside LibreOffice Writer:

1. Write your class notes.
2. Press `Ctrl + Shift + S` to open Save As.
3. Select `Documents/ENG-111`.
4. Enter the filename `Class_Notes.docx`.
5. Select Word 2007–365 (`.docx`) as the file format.
6. Click Save.

**Note:** If a format compatibility warning appears, select **Use Word 2007–365 Format**.

## Step 8 — Open an Existing Word Document

From inside the ENG-111 folder:

```bash
libreoffice --writer Class_Notes.docx
```

**Note:** Opens the existing Word document using LibreOffice Writer.

## Step 9 — Open a Document Using Its Full Path

```bash
libreoffice --writer ~/Documents/ENG-111/Class_Notes.docx
```

**Note:** Allows the document to be opened from any directory in the terminal.

## Step 10 — Return to the Previous Directory

```bash
cd ..
```

**Note:** Moves one directory level up.

To return directly to the home directory:

```bash
cd ~
```

## Result

Successfully learned how to navigate class folders, create Word documents, save them in the correct directory, and open existing documents directly from the Pop!_OS terminal.

## Issues Encountered

**Issue 1 — Incorrect Directory Name**

Linux distinguishes between different folder names.

For example:

```text
ENG111
ENG-111
```

These are two different directories.

**Solution:** Verify the correct directory name using:

```bash
ls ~/Documents
```

**Issue 2 — File Does Not Exist**

Attempting to open a nonexistent document produced an error similar to:

```text
/home/steven/Documents/ENG-111/Just does not exist.
```

**Solution:** Open LibreOffice Writer without specifying a file:

```bash
libreoffice --writer
```

Create the document, save it, and then reopen it using its correct filename.

## What I Learned

- How to navigate directories using `cd`.
- How to display files and folders using `ls`.
- How to verify the current directory using `pwd`.
- How to open LibreOffice Writer from the terminal.
- How to create and save Microsoft Word-compatible documents.
- How to open existing `.docx` files using relative and absolute paths.
- How to troubleshoot incorrect file paths and nonexistent documents.
