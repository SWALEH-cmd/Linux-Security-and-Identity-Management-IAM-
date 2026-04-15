# Linux-Security-and-Identity-Management-IAM-
## Overview
-Today i focused on how linux handles users, groups, and file-level security. Understanding these "locks" is critical for protecting cloud servers from unauthorised access.

## Key learning Points 
 * The principle of least privilege: Only giving users the bare minimum access they need to do their job.
 * Permission Triplets: -User (owner);the person who created the file.
                        -Group; a collection of users with shared access.
                        -Others; everyone else on the system.
 * File hardening: Using 'chmod' to restrict sensitive data.

## Practical Lab Steps
.Identity creation- Created and audited user accounts using 'adduser' and 'id'
.File Security Audit- Used 'ls -l' to analyze the security settings of system files like '/etc/shadow'
.Hardening Files- Created 'confidential.txt' and set permissions to '600', ensuring only the owner has access
                - Created 'public_notice.txt' and set permissions to '644', allowing the public to read but not edit.  
.Privilege Escalation: Practiced using 'sudo' to perfom administrative tasks that are blocked for standard users.

## Commmands Mastered
| command | purpose |
| :---| :--- |
| ls -l   | Auditing file ownership and permissions. |
| 'chmod' | Changing files access levels (read/write/execute). |
| 'chown' | Transferring file ownership between users. |
| 'sudo'  | Executing commands with administrative (root) power. |<img width="1920" height="1080" alt="Screenshot (38)" src="https://github.com/user-attachments/assets/69e17d3d-be22-4ef5-91ae-897336ea14c5" />
<img width="1920" height="1080" alt="Screenshot (37)" src="https://github.com/user-attachments/assets/d0ed1e80-1b41-4326-98ee-342e51126199" />

