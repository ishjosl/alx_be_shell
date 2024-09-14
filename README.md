# Shell Permissions Challenge

## Overview

This repository contains a script to switch the current user to a user named `betty`. The script is designed as part of a shell permissions challenge to demonstrate basic shell scripting and file permissions management.

## Challenge Description

The task was to create a script that switches the current user to the `betty` user using the `su` command. The script should be executable and should handle switching users properly.

## Steps Completed

1. **Create the Script:**
   - Created a new file named `0-iam_betty` in the `shell_permissions` directory.
   - Added the command `su betty` to the script to switch the user to `betty`.

2. **Make the Script Executable:**
   - Used the `chmod +x 0-iam_betty` command to make the script executable.

3. **Stage, Commit, and Push Changes:**
   - Staged the new script file using `git add 0-iam_betty`.
   - Committed the changes with the message "Add script to switch user to betty" using `git commit -m "Add script to switch user to betty"`.
   - Pushed the changes to the remote repository using `git push`.

## How to Run the Script

1. **Ensure the Script is Executable:**
   - Verify that the script has executable permissions by running:
     ```bash
     ls -l 0-iam_betty
     ```
     The output should include `-rwxr-xr-x`, indicating the script is executable.

2. **Run the Script:**
   - Execute the script by running:
     ```bash
     ./0-iam_betty
     ```
   - The script will prompt for the `betty` user’s password to switch users.

## Additional Information

- **User Permissions:** Ensure that the `betty` user exists on the system where this script is run.
- **Script Behavior:** The `su` command will switch the user context, requiring password authentication if run interactively.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.



