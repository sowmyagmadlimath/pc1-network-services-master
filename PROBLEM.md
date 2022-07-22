### Practice : Configuring Linux Services

## Problem Statements

Skylark Industries is a growing organization that is expanding its departments due on new incoming projects. You are hired as a network administrator and are responsible to set up network infrastructure for end-user systems. You have been asked to set up dynamic IP addressing. You have also been asked to set up domain names for certain systems as they provide specific company-wide services.​
Your objective is to:​

Configure a DHCP server to automatically assign IP address to all devices.​
Configure a DNS server for the company’s network.​

# Exercise 1: Configure DHCP server.

The departments of Skylark Industries have more than 100 machines. Manually configuring IP addresses on these machines will be a time-consuming task and may result in human errors. Therefore, as a network admin, you have decided to set up a DHCP server to automatically allocate the IP addresses.​

You need to: ​

1. Configure a DHCP server and configure machines to automatically receive IP addresses from the server.​
1. Verify that the DHCP process works properly.​

The objective  is to​

1. Configure Static IP address 192.168.1.10/24 in G1
1. Configure the DHCP server on G1 ​
1. Define the DHCP scope 192.168.1.1/24 to 192.168.1.50/24
1. Machines M1 and M2 should get IP address from DHCP server​

​**VM for server and clients are provided in vagrant file**

# Exercise 2: Configure DNS Server.​

Skylark Industries maintains an employee portal, which provides various services to its employees. For this, the company runs a web server with the domain name www.mydomain.lab.​ 
Configure a DNS server to recognize the domain name.​
Verify that the DNS server works properly and that the web server is accessible from end-user systems.​
Static Ip addresses are provisioned in vagrant file for machines G1, M1 and M2

Your objective is to ​
1. Configure G1 as DNS server ​to resolve www.mydomain.lab​ domain.
1. Verify the DNS server is working properly with command $ nslookup www.mydomain.lab which should be executed from machine M1​

** Note: Virtual Machines required for lab setup are provided in vagrant file​**

# Submit Instructions
1. To automate the task you are required to use the given solution.md file. 
2. You are required to fill up solution.md with the step by step commands.
3. Take screenshot of each step that mention in the solution.md file.
4. Once the solution is completed and pushed into the repository submit your repository URL to the mentor.
