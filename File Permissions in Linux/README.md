# Project: Enforcing File Permissions in Linux

## Objective
This project demonstrates the fundamental skill of managing file and directory permissions in a Linux environment. [cite_start]The goal was to use command-line interface (CLI) commands to enforce the principle of least privilege, ensuring users and groups have only the access necessary for their roles[cite: 1324, 1325].

## Process & Tools Used
All tasks were performed in the **Linux command line**. The primary commands used were `ls -la` for viewing permissions and `chmod` for modifying them:
* [cite_start]**Viewing Permissions:** Used `ls -la` to display detailed information about files and directories, including ownership and their current permission settings (read, write, execute)[cite: 1278].
* [cite_start]**Modifying File Permissions:** Used symbolic notation with the `chmod` command (e.g., `chmod o-w project_k.txt`) to remove the write permission for the "others" category on a specific file[cite: 1290, 1291].
* [cite_start]**Securing Hidden Files:** Applied multiple permission changes in a single command (e.g., `chmod u-w,g-w,g+r .project_x.txt`) to remove write access for the user and group while adding read access for the group[cite: 1303, 1304].
* [cite_start]**Changing Directory Permissions:** Modified directory permissions (e.g., `chmod g-x drafts`) to prevent a group from executing (accessing) a directory, thereby restricting access to its contents[cite: 1313, 1314, 1315].

## Skills Demonstrated
* **Linux Command Line (CLI):** Proficiency in using essential commands like `ls` and `chmod`.
* **Access Control:** Understanding and implementing file and directory permissions for users, groups, and others.
* **Security Hardening:** Applying the principle of least privilege to secure a file system.
* **System Administration:** Performing basic administrative tasks to maintain system security.