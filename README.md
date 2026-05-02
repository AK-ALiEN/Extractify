Extractify
==========

Extractify is a powerful and lightweight desktop application for
extracting password-protected and multi-volume archives with ease. Powered by
the robust 7-Zip engine, it supports a wide range of archive formats while
offering a clean, modern, and user-friendly interface.


Quick Start
-----------

- Report a bug: See Documentation/reporting-issues.rst
- Get the latest release: https://github.com/AK-ALiEN/Extractify/releases/latest
- Join the community: https://t.me/aliendevlab


What it does
------------

Extractify reads archive files (ZIP, RAR, 7Z, etc.) from a source
folder and extracts them into a destination folder. It supports password-
protected archives by automatically trying passwords from a user-provided list.

Key capabilities:

- Extract single or multiple archives in bulk
- Handle password-protected archives with a custom password list
- Extract multi-volume archives (e.g., .r01, .r02, .7z.001)
- Delete original archives after successful extraction (optional)
- Process archives in parallel using multiple worker threads

The goal is simple: reduce manual extraction effort and handle tricky archives
automatically.


Why it exists
-------------

Extracting many archives by hand is slow and repetitive. Password-protected
files add extra friction.

Extractify exists to:

- Save time when processing large collections of archives
- Automate password trials from a known list
- Provide a visual, user-friendly alternative to command-line tools
- Handle multi-volume archives without extra steps
- Offer a repeatable workflow for extraction tasks

It focuses on speed, simplicity, and reliability.


Core Features
-------------

- Graphical User Interface (GUI) – Dark theme with clear logs
- Password-protected extraction – Auto-try passwords from a .txt list
- Multi-format support – ZIP, RAR, 7Z, TAR, ISO, DMG, CAB, ARJ, WIM, and more
- Parallel extraction – Multi-threaded for faster processing
- Auto-delete option – Remove archives after successful extraction
- Built-in password list editor – Modify and save password files directly
- Real-time progress tracking – Per-file and overall progress
- One-click operation – Simple controls for fast execution


System requirements
-------------------

- Windows OS (7 and above recommended)
- No additional runtime or dependencies required (7-Zip engine included)
- Sufficient disk space for extracted content
- Basic system resources – depends on archive size and thread count

No external installations are required for normal usage.


How to use
----------

1. [Download](https://github.com/AK-ALiEN/Extractify/releases/latest) and run Extractify.exe

2. Configure extraction settings:
   - Folder to Scan – Directory containing archive files
   - Output Folder – Where extracted files will be saved
   - Password File – A .txt file with possible passwords (one per line)

3. Adjust optional settings:
   - Worker Threads – Number of parallel extraction tasks
   - Delete After Extraction – Remove archives once extracted successfully

4. Click "Start Extraction"

5. Monitor progress and logs in the bottom panel

Output folders will be created automatically if they don't exist.


Supported archive formats
-------------------------

.zip    .rar    .7z     .tar    .gz     .bz2
.iso    .cab    .arj    .wim    .dmg    .tar.gz
.7z.001 (and other multi-volume patterns)

Note: Some formats may have limited password recovery support depending on the
encryption method used.


Design philosophy
-----------------

Extractify follows a few simple rules:

- Do one job well – extract archives efficiently
- Keep the interface clean and intuitive
- Prioritize performance over unnecessary animations
- Keep everything local and self-contained
- Use a proven extraction engine (7-Zip) for reliability


Limitations
-----------

- Windows-only environment (no native Linux/macOS builds)
- Password recovery relies on a user-supplied list (no brute-force cracking)
- Very large archives with extreme compression may require more memory
- Multi-volume RAR5 support depends on underlying 7-Zip engine capabilities


Security & responsibility
-------------------------

This tool is intended for:

- Legitimate archive management
- Recovering access to your own password-protected files
- Authorized data processing

You are responsible for how you use it.

Do not use Extractify on archives you do not own or have explicit
permission to access.


Contact
-------

Developer: https://t.me/ak_xlien


Final notes
-----------

Extractify is built for utility, not flashy presentation.

If it saves you time and frustration when dealing with archives, it has done
its job.
