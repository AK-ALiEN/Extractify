Reporting Issues
================

Thank you for helping improve **Extractify**. Your bug reports and feedback make the project better for everyone.

Before you report
-----------------

Please take a moment to:

- Check the documentation – The main ``README`` covers installation, usage, and common troubleshooting steps.
- Search existing issues – Your problem may already be reported or solved. Look for similar issues in the `GitHub Issues <https://github.com/AK-ALiEN/Extractify/issues>`_ (once enabled).
- Test the latest version – Download the newest release from the releases page. Your issue might already be fixed.

What to include in your report
-------------------------------

A great bug report helps me understand and fix the problem quickly. Please include:

1. Clear description – What happened? What did you expect to happen?
2. Steps to reproduce – List exact actions that trigger the issue.
3. Your environment:

   - Windows version (Windows 7, 10, 11, Server, etc.)
   - System architecture (x64, x86)
   - Archive Extractor Pro version (e.g., latest release date)

4. Archive details:

   - Archive format (ZIP, RAR, 7Z, etc.)
   - Is the archive password-protected?
   - Is it a multi-volume archive (e.g., .7z.001, .r01)?

5. Password file sample – Anonymized excerpt of your password list (if relevant).
6. Error logs – Copy the error message or log output from the bottom panel.
7. Screenshots (optional) – If the issue is visual or GUI-related.

Example report template:

::

   Description:
   Extractify crashes when extracting a password-protected RAR5 archive.

   Steps to reproduce:
   1. Launch Archive Extractor Pro
   2. Set "Folder to Scan" to directory containing archive.rar
   3. Set "Output Folder" to a valid path
   4. Load password file with 10 common passwords
   5. Click "Start Extraction"
   6. Application freezes and closes after 30 seconds

   Environment:
   - Windows 10 Pro (22H2)
   - x64 architecture
   - Archive Extractor Pro (August 8, 2025 release)

   Archive details:
   - Format: RAR5
   - Password-protected: Yes
   - Multi-volume: No

   Password file excerpt (anonymized):
   password123
   admin123
   mypassword

   Error log:
   [ERROR] 7-Zip returned code 2: Wrong password or file is corrupted

Where to report
----------------

- GitHub Issues – Preferred location: `https://github.com/AK-ALiEN/Extractify/issues <https://github.com/AK-ALiEN/ArchiveExtractor/issues>`_
- Telegram – For quick questions or minor clarifications: `https://t.me/aliendevlab <https://t.me/aliendevlab>`_

Known limitations (not bugs)
-----------------------------

The following are not considered bugs. Please do not report them:

- **Windows-only** – The tool is designed exclusively for Windows systems.
- **Password cracking** – The tool only tries passwords from a user-supplied list. It does not perform brute-force or dictionary attacks.
- **RAR5 password recovery** – Some RAR5 encryption methods may have limited support depending on the underlying 7-Zip engine.
- **Very large archives** – Extremely large or heavily compressed archives may require more memory and processing time.
- **Network drives** – Performance may vary when extracting from or writing to network locations.

Feature requests
-----------------

Suggestions are welcome! Open a GitHub Issue with the label ``enhancement`` and describe:

- What you want to achieve
- Why it would be useful
- Any ideas on implementation (if you have them)

Keep requests focused on Extractify's core mission: **extracting archives efficiently, with support for password-protected and multi-volume files**.

Security issues
----------------

If you discover a security vulnerability (e.g., arbitrary code execution, path traversal), **do not open a public issue**.

Please report privately via Telegram to `https://t.me/ak_xlien <https://t.me/ak_xlien>`_.

Etiquette
----------

- Be respectful and patient – this is a solo project.
- Provide as much detail as you can.
- Follow up if I ask for more information.
- Close the issue when it's resolved for you.

Thank you for helping make Archive Extractor Pro reliable and efficient.
