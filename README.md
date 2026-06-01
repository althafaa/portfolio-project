# Portfolio-Project

## Tools Installed

- Cursor IDE
- Claude Code Extension
- Codex Extension
- GitHub
- Git for Windows

## Steps Completed

1. Installed GitHub
2. Created a GitHub account
3. Installed Cursor IDE
4. Installed Claude Code Extension
5. Installed Codex Extension
6. Installed Git for Windows
7. Created a Public GitHub repository
8. Created a README.md file on Cursor IDE
9. Committed a README.md file on Cursor IDE
10. Pushed a README.md file to GitHub repository

## Issues Encountered

### Issue 1: Codex Phone Number Verification
* **Problem:** Codex required phone number verification before login. I made multiple verification attempts because my phone number was not detected.

* **Solution:** I verified that the extension was installed successfully and attempted to complete the phone verification process. I will retry the verification after the temporary limit is lifted.

### Issue 2: Git Not Recognized
* **Problem:** Cursor could not recognize Git commands because Git was not installed on the computer.

* **Solution:** Downloaded and installed Git for Windows, then restarted Cursor.

### Issue 3: Git Commit Conflicts and Accidental File Deletion
* **Problem:** Experienced a loop of file conflicts where the README.md kept getting overwritten or deleted. This happened because changes made directly on the GitHub web interface vibrated out of sync with my local Git repository, leading to accidental deletions and messy commit history.

* **Solution:** Used Git revert to restore the deleted README.md file (`Revert "Delete README.md"`). To prevent this from happening again, I synchronized the remote and local repositories properly by pulling the latest changes to my laptop before making and pushing any new edits.