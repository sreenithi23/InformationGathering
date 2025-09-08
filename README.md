# Ex-02 InformationGathering
Information Gathering Techiques

# To perform information gathering techniques

# AIM:

To perform information gathering techniques using kali linux 

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:
Open terminal/browser and try execute necessary commands/use url to perform information gathering

## Architecture Diagram
```
                      +-------------------------+
                      |     Attacker System     |
                      |     (Kali Linux)        |
                      +-----------+-------------+
                                  |
                                  | Terminal / Browser
                                  | Executes Recon Tools
                                  v
      +------------------- Passive Recon --------------------+
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  |   WHOIS Query  | --> |    Domain Registrars    |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  |   DNS Enum     | --> |     Public DNS Servers  |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      +-----------------------------------------------------+

                                  |
                                  v

      +------------------ Active Recon ----------------------+
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  |   Nmap Scan    | --> |  Target Host/Network    |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  | WhatWeb, Wapp | --> |   Target Web Application |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  | theHarvester   | --> |     Search Engines      |  |
      |  +----------------+     +------------------------+  |
      +-----------------------------------------------------+

                                  |
                                  v
                    +-----------------------------+
                    |     Collected Information   |
                    | - IPs, Subdomains           |
                    | - Open Ports & Services     |
                    | - Technology Stack          |
                    | - Emails, Metadata          |
                    +-----------------------------+
```

## OUTPUT:

### Whois

<img width="528" height="385" alt="image" src="https://github.com/user-attachments/assets/1670715f-16b8-47d6-b97a-81a2b8fa81bf" />


### Finding Hosting Company :
<img width="533" height="277" alt="image" src="https://github.com/user-attachments/assets/5529e199-4a0d-47d0-8a57-8038367e9a7a" />


### History of the website :
<img width="538" height="256" alt="image" src="https://github.com/user-attachments/assets/9abacba3-f9be-4536-87c6-75d5f0d148dd" />


### ping command :
<img width="506" height="506" alt="image" src="https://github.com/user-attachments/assets/08dfca53-3e3d-4357-9296-bbbcdc7b49ad" />


### whois :
<img width="536" height="523" alt="image" src="https://github.com/user-attachments/assets/3c311ef9-71f5-4006-8cb7-b2fa410e35b4" />

### netcat :
<img width="511" height="78" alt="image" src="https://github.com/user-attachments/assets/01fbeeab-09ea-46c2-ba66-2da15fc0cc47" />

### nmap :
<img width="525" height="212" alt="image" src="https://github.com/user-attachments/assets/b3d61809-31a1-4054-a9b0-a98ac044afb9" />


### whatweb :
<img width="541" height="131" alt="image" src="https://github.com/user-attachments/assets/73f0c79a-e47a-4452-b056-b5c0fd63f0c1" />


### httprint :
<img width="541" height="170" alt="image" src="https://github.com/user-attachments/assets/1586a504-ad1a-4378-87af-27060fdedc1f" />


### TCP traceroute :
<img width="541" height="277" alt="image" src="https://github.com/user-attachments/assets/43ca7f5e-272c-4795-affc-da34d70205c1" />


### UDP traceroute :
<img width="543" height="392" alt="image" src="https://github.com/user-attachments/assets/3000fdb6-54a3-47c3-ad31-31bdf5b46b00" />


## RESULT:
The information gathering techniques tools/procedure were  identified successfully
