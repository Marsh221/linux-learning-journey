# Linux Learning Journey — Lessons Covered So Far

> Progress record: these topics have been taught in chat. Practical completion is **not confirmed**. The Linux Mint VM is currently unavailable because the user reported a hard-drive failure. Continue with safe conceptual lessons until storage and the VM's status are clear.

## Lesson 1 — First boot and desktop orientation

**Goal:** Become familiar with the Linux Mint XFCE desktop before using the terminal.

Topics introduced:
- Starting the Linux Mint virtual machine and signing in.
- Finding the desktop menu, settings, file manager, and Terminal.
- Confirming the desktop loads correctly before beginning command-line practice.

**Practice status:** Not confirmed. No assumption that Mint successfully booted.

## Lesson 2 — Host, guest, and virtual machine basics

**Goal:** Understand how Linux runs inside VirtualBox.

Key ideas:
- **Host:** the physical Windows computer.
- **VirtualBox:** the virtualization software that runs a virtual computer.
- **Guest:** Linux Mint running inside that virtual computer.
- The virtual disk (commonly a `.vdi` file) stores the guest operating system and its data.

Planned environment:
- Windows host on a Dell Latitude 7390.
- Oracle VirtualBox.
- Linux Mint XFCE 64-bit guest.
- Planned VM resources: 3 GB RAM, 2 virtual CPUs, and a 40 GB dynamically allocated virtual disk on the external drive.

**Practice status:** Concepts explained; setup/boot not confirmed.

## Lesson 3 — Understanding the Linux filesystem

**Goal:** Understand the Linux directory tree.

Important locations:
- `/` — the filesystem root; the top of the directory tree.
- `/home` — home directories for ordinary users.
- `/etc` — system-wide configuration files.
- `/usr` — many installed programs and shared resources.
- `/var` — changing data such as logs and caches.
- `/tmp` — temporary files.
- `/root` — the administrator (root user)'s home directory.

Commands introduced:
- `pwd` — print the current working directory.
- `ls` — list directory contents.

**Practice status:** Explained; commands not confirmed as run.

## Lesson 4 — Absolute and relative paths

**Goal:** Understand how to describe a file's location.

- An **absolute path** starts at `/` and gives the full location, for example `/home/marsh/Documents/notes.txt`.
- A **relative path** describes a location from the current directory, for example `Documents/notes.txt` when starting in the home directory.

Commands introduced:
- `pwd` — show where you are.
- `ls` — see what is in the current directory.
- `cd` — change to another directory.

**Practice status:** Explained; no terminal exercise confirmed.

## Lesson 5 — File types and extensions

**Goal:** Recognise common file types and understand Linux filename conventions.

Examples:
- `.txt` — plain text.
- `.pdf` — PDF document.
- `.jpg` — image.
- `.sh` — commonly a shell script.
- `.py` — commonly a Python script.
- `.html` — HTML document.

Key idea: extensions are useful labels, but Linux does not rely on extensions alone to determine what a file is or whether it can be executed.

**Practice status:** Conceptual lesson; no file exercise confirmed.

## Lesson 6 — Essential commands and getting help

**Goal:** Recognise a few basic commands and learn how to find command guidance.

Commands introduced:
- `whoami` — display the current username.
- `date` — display the system date and time.
- `clear` — clear the terminal display.
- `ls` — list files and directories.
- `pwd` — display the current directory.
- `--help` — a common option that displays brief command help, for example `ls --help`.
- `man` — opens a command's manual page, for example `man ls`.

**Practice status:** Commands explained; not confirmed as run in the VM.

## Important storage interruption and safe next steps

The user reported that a hard disk was damaged and that the learning programme/VM may have been stored on it. It is not yet confirmed whether the failed drive was the external VM drive or the computer's internal drive.

Until that is clarified:
- Do not assume the VM or its files are accessible.
- Do not format, initialize, repartition, run repair writes, or use CHKDSK on a drive that may contain needed data.
- Avoid repeatedly powering on a drive that may be failing.
- If important files are on the failed drive, stop using it and consider professional data recovery.
- Continue with conceptual lessons that do not require the VM.
- If the VM is recovered on a healthy external drive, shut it down before disconnecting that drive.

## Next learning step

Continue with a short, beginner-friendly conceptual lesson that does not require access to Linux Mint. Return to hands-on terminal practice only after the VM is confirmed available and the desktop is working.

## Learning record conventions

For each future lesson, record:
1. Lesson number and topic.
2. Learning objective.
3. Concepts and commands introduced.
4. Safe practice exercise.
5. Whether the exercise was actually completed.
6. Questions or errors to revisit.
7. Next lesson.

Never mark an exercise complete unless the user confirms it.
