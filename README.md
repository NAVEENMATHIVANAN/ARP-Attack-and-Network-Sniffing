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

![image](https://github.com/NAVEENMATHIVANAN/ARP-Attack-and-Network-Sniffing/assets/119394582/7ce3e18e-e2a2-4416-9730-79788ba62e0c)

From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:

![image](https://github.com/NAVEENMATHIVANAN/ARP-Attack-and-Network-Sniffing/assets/119394582/e48d8ef6-f3af-4f33-b1cb-0236f4c99e4d)

 dsniff:

In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:

![image](https://github.com/NAVEENMATHIVANAN/ARP-Attack-and-Network-Sniffing/assets/119394582/2174589b-cb4f-4096-bb5a-5ba2fb84ba20)

In Kali issue the following commands:
sudo dsnifff
## OUTPUT:

![image](https://github.com/NAVEENMATHIVANAN/ARP-Attack-and-Network-Sniffing/assets/119394582/d140afb3-dc9a-4553-af22-ec28701974c2)

Invoke the wireshark and examine the various menus  and controls of the tool:
![image](https://github.com/NAVEENMATHIVANAN/ARP-Attack-and-Network-Sniffing/assets/119394582/566db55d-2187-4ad1-a1bb-40ff17ca1801)


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
