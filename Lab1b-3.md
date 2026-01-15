Output of ls -l or tree structure showing contents of extracted files 

<img width="1284" height="261" alt="image" src="https://github.com/user-attachments/assets/f4919c2d-e4ab-4d03-bfe7-e0eda1731d98" />

Command and result for: • find . -name "*.txt" or similar extension-based search

<img width="1300" height="226" alt="image" src="https://github.com/user-attachments/assets/bae78426-a0bd-4cfd-b53d-ec88ed47abf1" />

Search for strings: `grep -r 'keyword' ./Gutenberg`

<img width="1281" height="799" alt="image" src="https://github.com/user-attachments/assets/816e2374-efae-4768-8d1d-c25435f24b4d" />

Reflection Prompts

· - Which command-line tool was the most useful in solving the questions?

    "Grep" because it allows for complex filtering that would take many hours to do manually
    
· - How might these search tools help in cybersecurity investigations?

    Using "Grep" investigator can search for specific IP address across thousand of log entries to track a hackers movement.

· - How could scripting improve repetitive search tasks?

    Instead of typing five different commands to find, filter, and count words, a script can run them all at once.

· - What limitations did you encounter using grep and find? 

    Grep works best on plain text. If the Gutenberg books were in PDF or Word format, standard grep would fail to read them properly, whereasFind has a difficult syntax.
