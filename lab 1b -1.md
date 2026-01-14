Screenshot of sudo apt install apache2 and Apache running at http://127.0.0.1. 

<img width="1276" height="800" alt="image" src="https://github.com/user-attachments/assets/4f902817-68d1-46f4-896d-dc72692736fd" />

<img width="1282" height="800" alt="image" src="https://github.com/user-attachments/assets/0ad66882-b310-46ec-b922-a88c3a763970" />


Edited /var/www/html/index.html 
<img width="1279" height="798" alt="image" src="https://github.com/user-attachments/assets/e90faedb-e1ae-4e8c-ac64-5eaafef220cc" />

screenshot of nmap [partner’s IP] showing open ports before and after Apache is removed. 

Before Remove

<img width="1053" height="244" alt="image" src="https://github.com/user-attachments/assets/14202491-14db-49ac-819c-4afeaa6ac9eb" />

After Remove

<img width="1214" height="580" alt="image" src="https://github.com/user-attachments/assets/d561dccd-1ae6-4be1-b006-409c4a49851b" />

Outputs of: • sudo ufw status verbose before and after enabling • Port 80 allowed and verified via partner’s Nmap scan 

<img width="1273" height="543" alt="image" src="https://github.com/user-attachments/assets/0e6cfac8-6d93-4863-a2d7-a8c0d9fa655c" />

SSH Enabled and Tested 

<img width="947" height="501" alt="image" src="https://github.com/user-attachments/assets/bf4ab7b3-ae24-4bb5-aa54-c2a2b41ab656" />

Screenshots of: • tar cf, bzip2, bunzip2, and tar -xvf 

<img width="1277" height="796" alt="image" src="https://github.com/user-attachments/assets/65f93cee-86ef-4739-a0f1-bc23acad9296" />

<img width="1280" height="812" alt="image" src="https://github.com/user-attachments/assets/fab65672-b263-4c52-a608-7ec133e968b0" />

<img width="496" height="135" alt="image" src="https://github.com/user-attachments/assets/a7d98f4d-c070-4b29-a63d-51f6b21b1d39" />

Reflection Questions

· - What’s the role of a firewall in managing services?

    Firewall is to monitors and filters all network traffic to ensure only authorized and safe traffic passes through.

    
· - How did SSH access deepen your understanding of Linux as a server?'

    SSH (Secure Shell) allows me to securely access and control servers remotely.
    
· - Why is file compression important in server contexts?

    Because File compression isn't only making things smaller but it's a tool for resource optimazation and cost management.
    
· - How does user privilege management help secure systems? 

    By using tools like sudo and strict file permissions, it prevents unauthorized changes to the OS
    
