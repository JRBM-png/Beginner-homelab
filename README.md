# Beginner-homelab
This repository it describes how I was able to set up a homelab in virtual box and observed packets over a network.
## Objective 
The main objective of this lab was to learn virtual machine fundamentals and to simulate a basic attack whilst observing the attack through wireshark. 
## Skills learnt
- Virtual machines
- Wireshark
- Linux command line (Used terminal commands such as sudo, apt install etc)
- Network diagram
## Tools used
- Virtual box
## Steps
### Step 1: Set up the iso's
The first step was to set up the kali and ubuntu iso in virtual box. During this process I had to allocate the resources to each machine such as the memory and the amount of processors. 

<img width="510" height="541" alt="ss of vm home" src="https://github.com/user-attachments/assets/a2bda379-ddd5-4791-a86f-57d3f37fd882" />

Here is a screenshot showing the main page of virtual box with kali and ubuntu

<img width="571" height="412" alt="ss of ubuntu memory" src="https://github.com/user-attachments/assets/81b024ca-126a-4d3c-a56f-aa71c9ffcb30" />

Here is the ubuntu memory with 4gb allocated

<img width="571" height="412" alt="ss of ubuntu processor" src="https://github.com/user-attachments/assets/c1bbe4ce-2749-4168-89b0-616e8027902f" />

Here is the ubuntu processors with 2 allocated

<img width="571" height="412" alt="ss of kali memory" src="https://github.com/user-attachments/assets/73a3a0e2-7578-4c9a-b298-399d9267150e" />

Same thing for kali except there is 2gb of memory allocated instead of ubuntu 4gb

<img width="571" height="412" alt="ss of kali processor" src="https://github.com/user-attachments/assets/c06b1981-2633-4e8c-ad68-c858dd5cf3df" />

Same as ubuntu with 2 allocated

### Step 2: Install the iso's
The next step was to install the distributions

<img width="571" height="412" alt="ubuntu set up" src="https://github.com/user-attachments/assets/d318db7e-da32-47f8-a248-8059fe10331f" />

For ubuntu the set up was straight forward and easy

<img width="571" height="412" alt="kali set up" src="https://github.com/user-attachments/assets/bd42c9d2-23fc-4a95-abeb-e43af73d6671" />

For kali I didnt have to go through the set up as I downloaded a pre installed iso

### Step 3: Snapshots

Then I had to create snapshots of ubuntu and kali. Snapshots are important as they allow you to revert the os to a previous state. This allows you to experiment, break and repair things, without consequences

<img width="510" height="500" alt="ubuntu snapshot" src="https://github.com/user-attachments/assets/d3f7b4bd-fde9-47d0-b659-adeff0b125d5" />

Snapshot of ubuntu

<img width="510" height="500" alt="kali snapshot" src="https://github.com/user-attachments/assets/f17c02fb-1673-41ed-a9d0-02ec81a92a5b" />

Snapshot of kali

### Step 4: Setting up the network

After that I had to set up the network, by setting up the network it allows the two virtual machines to be able to connect with eachother 

<img width="571" height="412" alt="setting up nat network" src="https://github.com/user-attachments/assets/d1c36ed8-92f4-46ed-9293-105b91eca216" />

Here I am setting up the nat network, this would be the router normally

<img width="571" height="412" alt="connecting ubuntu to nat network" src="https://github.com/user-attachments/assets/a749afa1-d8bb-4a71-9d8c-2c76e40aff0a" />

After setting up the nat network I connected ubuntu to it by selecting it as the network adapter instead of the default option

<img width="571" height="412" alt="connecting kali to nat network" src="https://github.com/user-attachments/assets/f4fe955a-34c1-481d-9ce6-fc612ba641fb" />

I then did the same thing for kali 

### Step 5: Installing wireshark and setting up firewall

I then installed wireshark and installed the firewall which set up the ability to monitor the traffic

<img width="571" height="412" alt="ubuntu installing wireshark" src="https://github.com/user-attachments/assets/75b7b108-1a86-4c5c-9bf3-99f5653321d2" />

Through using the linux command terminal I installed wireshark through the "sudo apt install wireshark" command

<img width="571" height="412" alt="ubuntu installing ufw" src="https://github.com/user-attachments/assets/682249a2-94a3-4d19-b8f5-eb9294914bf2" />

After that I set up the firewall which allows it to filter and monitor traffic, this can also be used to restrict certain ip addresses from accessing the network. I aksi allowed ssh which allows it to accept remote connections. As seen there was an issue as I did not correctly type the correct line however this was corrected after.

### Step 6: Capturing network traffic






