A registered domain from Namecheap, GoDaddy, Route 53, or similar: Duckdns.org/domain and DNS A record pointing your domain to your VM's public IP 

<img width="1911" height="608" alt="image" src="https://github.com/user-attachments/assets/885de6ee-be5f-4cce-a6b4-7b46b0b89427" />

Apache2 running and accessible on port 80 

<img width="940" height="387" alt="image" src="https://github.com/user-attachments/assets/05a47589-93fe-4bc8-972a-bc8fc82c1c05" />

Open http://yourdomain.com and capture the Apache welcome pag

<img width="940" height="560" alt="image" src="https://github.com/user-attachments/assets/42f896ab-b5ed-441b-9ad2-a56467d7edc4" />

Output of nslookup yourdomain.com or dig

<img width="918" height="216" alt="image" src="https://github.com/user-attachments/assets/b6db7aba-a923-498a-a81d-7d37bfc43e5f" />

Reflection Questions

· - What is the role of DNS in Internet presence?

    DNS functions like a public phone book that tells the entire internet which IP address belongs to which domain name
    
· - Why does DNS propagation take time?

    DNS propagation takes time due to factors such as the Time to Live (TTL) of the DNS record, record type, DNS cache, and network conditions.\
    
· - How does Let’s Encrypt validate domain ownership?

    Let's Encrypt memvalidasi kepemilikan domain perangkat lunak klien ACME menggunakan kunci publik.
    
· - What are the risks if TLS is not configured on a public-facing site?

    Running a site with out TLS will be dangerous beacuse anyone on the same network (like at a coffee shop) can see exactly what users are typing like passwords, personal info, or messages.
    
· - What could happen if you leave your cloud VM running for months? 

    it will take a lot of cost because most cloud providers charge by the hour or second and vulnerable to cyber attacks
