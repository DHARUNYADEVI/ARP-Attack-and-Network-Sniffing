# ARP-Attack-and-Network-Sniffing
# Explore Network Sniffing and ARP Attacks
# NAME:Dharunyadevi S
# Register Number:212223220018

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

![WhatsApp Image 2025-09-21 at 18 50 51_763f9086](https://github.com/user-attachments/assets/6c17726b-efa1-4494-adc4-f0f2c37c012d)

From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>

## OUTPUT:

![WhatsApp Image 2025-09-22 at 14 46 21_7af45d96](https://github.com/user-attachments/assets/8f1bc887-b288-4178-8f99-cdd26a15b239)


Invoke the wireshark and examine the various menus  and controls of the tool:
## OUTPUT:
![WhatsApp Image 2025-09-22 at 08 53 59_549ea6ae](https://github.com/user-attachments/assets/ccacb8da-01f2-4c9c-870f-03d211abbb6d)


arp poisoning using ethercap 
## OUTPUT:
![WhatsApp Image 2025-09-22 at 08 54 36_acebf8fb](https://github.com/user-attachments/assets/d1f32861-b120-40c5-a164-943c3b6e3dca)


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
