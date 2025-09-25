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

<img width="1088" height="803" alt="image" src="https://github.com/user-attachments/assets/ae321a5d-be31-42bf-9e2d-9c175f45cedf" />

From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>


## OUTPUT:
![241192115-e985ae01-13fa-42f1-8155-94b04deddecb](https://github.com/pavankishore-AIDS/ARP-Attack-and-Network-Sniffing/assets/94154941/0bc59714-d2a5-459c-9e7d-517c82037ae1)


In Kali issue the following commands:
sudo dsnifff

## OUTPUT:

![241192308-b683d8ad-117e-44c7-b03c-bdd0b0f7e4c0](https://github.com/pavankishore-AIDS/ARP-Attack-and-Network-Sniffing/assets/94154941/d8000a29-e6c6-4ea3-ae36-9c66f9d139a6)



Invoke the wireshark and examine the various menus and controls of the tool:

![241192334-e9461986-63fa-4577-8c66-ccb63a3c56bf](https://github.com/pavankishore-AIDS/ARP-Attack-and-Network-Sniffing/assets/94154941/19ba4623-276d-43d9-8105-7395b509f9ae)


## RESULT:

The kali linux tools for ARP Attack and Network Sniffing were identified successfully
