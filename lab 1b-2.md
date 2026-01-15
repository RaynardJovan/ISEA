Output showing creation of alice, bob, and mallory using adduser, verified using less /etc/passwd.

<img width="1277" height="799" alt="image" src="https://github.com/user-attachments/assets/d467b85a-c4cf-42ac-936c-ed3050a93719" />

Screenshot or command output confirming: • mkdir /home/shared • Ownership and group updated via chown, chgrp. 

<img width="617" height="50" alt="image" src="https://github.com/user-attachments/assets/168f42df-9450-49a0-996f-e9168bed7a2c" />

Switch user: `su - alice`, `su - bob`, `su - mallory`; use `whoami` and `ls -l /home/shared` to verify access

<img width="1279" height="791" alt="image" src="https://github.com/user-attachments/assets/50872b7c-66c4-4fa2-8f11-625a87816cd0" />

<img width="1278" height="148" alt="image" src="https://github.com/user-attachments/assets/70ea6183-91d8-4bd8-aa58-e1e1fc1450f8" />

Reflection Questions

· - How do Linux permissions differ from Windows ACL?

    Linux uses a simple "user-Group-Others" model, every file has one owner and one group that we can give Read, Write, Execute permission to these three model.

    Windows ACl can specify unique permissions for dozens of different users or groups on a single file.
    
    
· - What’s the effect of chmod 770 vs 750?

    Chmod 770: The user and Group have full control (Read,Write,Execute)
    
    Chmod 750: THe user has full controll and the group only can Read and Execute
    
· - What is the risk of adding users to the sudo group?

    By adding a user using "sudo", it's mean a user can read any file delete the entire filesystem, or install malware.
    
· - Why is it important to verify with `su` and `whoami`? 

    "su" command is the switch to get into the user environment, it forces a fresh session, ensuring that any new group memberships (like adding someone to sudo) are actually active.

    "whoami" command is to prevent user from accidentally running a destructive command in the wrong window
