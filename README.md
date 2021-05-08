Project A – OS and Networking
Scenario
You have been hired by an IT company as an IT subject matter expert. Management has a client who
wants to upgrade their IT systems, but the client has a limited budget and no more physical space to
install new equipment. You suggest implementing virtual machines instead of more hardware to help
reduce costs and to meet the client’s operational needs. Part of the upgrade includes installing a
Firewall, a PC for the CEO, a Webserver, DNS server, and some Linux machines for monitoring and
conducting cybersecurity related tasks. Once the new network is installed, you will document
configurations and create a security baseline by scanning for open ports.
Project Tasks
A network diagram is attached to this document and should be used as guidance for completing this
project. Feel free to use it in your presentation.
By successfully completing this project, you will have demonstrated the ability to install and configure
different types of operating systems, configure a network, use network tools, create security baselines,
and develop a professionally written report which documents your work. Depending on your personal
computer hardware settings, you may need to run scans or updates overnight.
Project tasks are:
1. Install VirtualBox and extensions.
2. Using the supplied VMs, install the Router-FW, DNS Server, Webserver, and CEO PC, ensuring they
are connected to the correct network segment.
3. Install a Kali Linux computer in each of the 3 network segments.
4. Using the CEO PC, open www.seclab.net with Firefox. Troubleshoot and resolve any issues
discovered.
5. Use FTP to download Social-Media-Security-Policy to the CEO PC.
6. Document the OS version and IP configuration of the CEO PC.
7. Create a new user account on the web server.
8. Document the OS versions and IP configurations of the web and DNS servers.
9. Use nmap on Kali Linux to perform port scans on the DNS and Web servers. Document the open
ports on each server.
10. Verify through that the trusted network is protected from the untrusted network.
11. Use Wireshark on Kali Linux to capture an FTP file transfer between the CEO PC and the web
server.
Deliverables
To successfully complete this project, you must perform the following:
1. Complete all project tasks.
2. Answer the 10 exam questions in written form and submit to your coach.
3. Provide an executive presentation to your coach via Zoom. The presentation will be done using
PowerPoint (or similar product), followed by a live demonstration of your working network. The
PowerPoint presentation must have a design of your choice and have at least 7 slides to include:
a. Executive Summary at beginning
b. Description of what you created
c. Problems identified and their resolution
d. Recommendations and closing remarks at the end
Project Grading
The project is worth 100 points. A passing grade is 70 or more points. Points are distributed as follows:
 Creation of network and demonstration of OS knowledge – 30 pts
 Written answers – 20 pts
 Presentation development – 20 pts
 Complete all tasks – 20 pts
 Presentation execution – 10 pts
Exam Questions
1. What style or type of DMZ is being deployed?
2. Describe any problems you discovered on the CEO PC and how you resolved them.
3. List the OS version and IP configuration (IP address, prefix, default gateway, and DNS server) of
the CEO PC.
4. List the OS version and IP configuration of the Web Server.
5. List the OS version and IP configuration of the DNS Server.
6. List the open ports and protocols found on the Web Server.
7. List the open ports and protocols found on the DNS Server.
8. What is the purpose of a security baseline for a server?
9. What are the contents of the file you transferred with FTP to the CEO computer?
10. What username and password were shown by Wireshark for the FTP session between the CEO
computer and Web Server?
Project Accounts
System Username Password
Router-FW admin pfsense
DNS Server root password
Web Server admin
root
$eclab!2
$eclab!3
CEO PC user
root
$eclab!2
$eclab!3
FTP user credentials: Username: jasper Password: 2hard2guess
Project Files
Download the required VMs here:
https://s3.amazonaws.com/media.quickstart.com/Bootcamp/Infosec/ProjectA.zip
Download VirtualBox here:
https://www.virtualbox.org/wiki/Downloads
Download Kali Linux here:
https://www.offensive-security.com/kali-linux-vm-vmware-virtualbox-image-download
