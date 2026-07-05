# Cloud-Networking-VPCs-NAT-Gateways
<img width="746" height="667" alt="image" src="https://github.com/user-attachments/assets/cd86155b-1995-44da-a7d4-19141451407e" />


# Why Use This:
To keep our systems safe! This setup lets our hidden, private computers securely download updates from the internet without ever letting strangers or hackers inside.

# What I did: 
• Created a virtual network (VPC) named vpc1 and split it into Public (open) and Private (hidden) areas. 
• Set up an Internet Gateway and Route Tables to control the traffic.
• Started two virtual computers: one Public Server and one Private Server. 
• Tested the Private Server's internet. It showed "Request timed out," meaning it was perfectly hidden.
• Added a NAT Gateway in the Public area to act as a safe messenger. 
• Updated the rules so the Private Server could use the NAT Gateway to safely reach the internet. 

# What I learned today:
VPC: It is like having your own private, fenced-in yard in the cloud.
Private Subnet: A hidden room where computers are completely safe from the public internet.
NAT Gateway: A helpful messenger that goes to the internet for your private computers without exposing them.
Route Tables: Digital traffic signs that tell network data exactly where to go.
Bastion Host: A cool trick where you log into a public computer first, just so you can safely reach your hidden computers.

Actually building this step-by-step made everything so easy to understand! Hands-on learning is the best way to grow.
