Show that the domain name is linked via DNS A record to the VM and accessible via http://yourdomain.com.

<img width="940" height="560" alt="image" src="https://github.com/user-attachments/assets/7f628003-d65d-438a-beed-2e021778841f" />


Output of sudo certbot --apache showing that Let’s Encrypt issued a certificate for your domain. 

<img width="940" height="405" alt="image" src="https://github.com/user-attachments/assets/46e6c66c-b864-4f8c-ae87-25151eb46a79" />

Screenshot of your site loaded via https://yourdomain.com with a padlock icon in the address bar and Screenshot of browser certificate info showing that the issuer is Let's Encrypt. 

<img width="940" height="536" alt="image" src="https://github.com/user-attachments/assets/56de5fbc-e0cb-438b-8d09-6d72c2980f02" />

<img width="940" height="331" alt="image" src="https://github.com/user-attachments/assets/e487bb8a-0e8e-4230-a967-bf719efae1ea" />

Reflection Questions

· - Why is HTTPS important for modern web applications?

    HTTPS is important because it keeps the information secret by encrypting the data moves between the browser and the website's server
· - What entity issued your site’s TLS certificate?

    Let's encrypt
    
· - How long is your certificate valid for, and how can it be renewed?

    Let's encrypt valid for 90 days, it can be renewed by crowjob or system timer check
    
· - What happens if a certificate expires and is not renewed?

    The user will see a warning "Your connection is not private" on the browser

· - Why does Let’s Encrypt require port 80 or 443 to be open for verification? 

    because Let's encrypt need to prove that the owner has  control over the domain requesting for certificate
