Screenshot of the EC2 dashboard showing the instance running (state = running),

<img width="2559" height="1362" alt="image" src="https://github.com/user-attachments/assets/d058e65b-46a2-435b-aecc-6b863ba71892" />

Screenshot showing inbound rules:  • Port 22 (SSH)  • Port 80 (HTTP) opened 

<img width="2559" height="1360" alt="image" src="https://github.com/user-attachments/assets/e9367836-86c9-423d-a29d-38a60a254317" />

Terminal output showing successful SSH login using the .pem key. Example: ssh -i "yourkey.pem" ubuntu@<public_dns> 

<img width="1573" height="990" alt="image" src="https://github.com/user-attachments/assets/a6e88158-1934-4233-9751-b62b84d2742d" />

Output of sudo apt install apache2 and browser screenshot of the Apache welcome page (http://<public_ip>) 

<img width="970" height="168" alt="image" src="https://github.com/user-attachments/assets/40859963-12b8-497d-b734-fa2353e4cd0d" />

<img width="2559" height="1460" alt="image" src="https://github.com/user-attachments/assets/8060a7b0-12f6-4c6e-924a-c980de2a1e67" />


Edited /var/www/html/index.html with personalized content. Screenshot of the file content (nano or gedit) and browser output 

<img width="2559" height="1526" alt="image" src="https://github.com/user-attachments/assets/1eb1c2b2-27c7-4206-a253-c34ee12c7782" />

<img width="2559" height="1473" alt="image" src="https://github.com/user-attachments/assets/8b187c5c-928c-4cda-8930-b16c3ad36b97" />


Reflection Questions 

- What were the benefits of cloud deployment over local virtualisation? 

        Cloud bring a lot of benefits, including scalability, cost-effectiveness, and enchange access to data and applications
- How does Apache serve files, and how did you verify this?

        Apache serves files by listening from HTTP requests on specific ports and mapping requested URLs to a directory on the server's disk. To verify this is working, i can check the service status using "systemctl status apache2" or i can browse to the server's ip adress.

- What did you learn about file ownership and permissions? 

        In linux, file sercurity have 3 hierachy(User, Group, and Others) each assigned specific Read(r), Write(W), Execute(x) right.
- What risks are associated with leaving instances running? 

        Leaving cloud instances running when they are not needed poses significant financial and security risks such as cyber attacks.
  
- How would you explain the difference between DNS and /etc/hosts to a client? 

        DNS functions like a public phone book that tells the entire internet which IP address belongs to which domain name, whereas the /etc/hosts file lets you map IP addresses to any unique.
    
