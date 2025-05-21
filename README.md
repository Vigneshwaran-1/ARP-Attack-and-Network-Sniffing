# ARP-Attack-and-Network-Sniffing
# Explore Network Sniffing and ARP Attacks

# AIM:

To explore network sniffing and ARP Attacks

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:


### Step 3:
Open terminal and try execute some kali linux commands

## ARP Attacks:  
ARP spoofing: A hacker sends fake ARP packets that link an attacker's MAC address with an IP of a computer already on the LAN. 
Boot kali and Windows7 virtual machines.
In windows 7 give the command arp -a
## OUTPUT:
![image](https://github.com/user-attachments/assets/f7f837b7-0fe0-477a-9837-1036d542d477)



From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![image](https://github.com/user-attachments/assets/daa5db86-859e-400e-9cce-cd6d853016c1)



 dsniff: 








In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![image](https://github.com/user-attachments/assets/aa178420-6677-4c29-8145-a72b4149dd6d)





In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![image](https://github.com/user-attachments/assets/8569d1b7-dd02-4328-aecb-9a5e1daf7c8f)




Invoke the wireshark and examine the various menus  and controls of the tool:
![image](https://github.com/user-attachments/assets/8236c5b1-2358-4e4b-929a-addf9f103375)



## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
