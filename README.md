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
![image](https://github.com/NAVEENMATHIVANAN/ARP-Attack-and-Network-Sniffing/assets/119394582/d0172319-ca45-4887-b2fc-8d30f47f2535)



From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:

![image](https://github.com/NAVEENMATHIVANAN/ARP-Attack-and-Network-Sniffing/assets/119394582/42318476-cc91-4f32-95e5-92825908c4cd)


 dsniff:

In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:

![image](https://github.com/NAVEENMATHIVANAN/ARP-Attack-and-Network-Sniffing/assets/119394582/28fafade-0ccb-40aa-a9a4-52df5325a99f)


In Kali issue the following commands:
sudo dsnifff
## OUTPUT:

![image](https://github.com/NAVEENMATHIVANAN/ARP-Attack-and-Network-Sniffing/assets/119394582/31dcacac-e7e9-4ae4-9721-cca92ad7b7dd)

Invoke the wireshark and examine the various menus  and controls of the tool:

![image](https://github.com/NAVEENMATHIVANAN/ARP-Attack-and-Network-Sniffing/assets/119394582/9784ccb0-ed06-4e61-b97b-a34a616d6c46)



## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
