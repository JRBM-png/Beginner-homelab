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
### Step 1:
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

### Step 2:
The next step was to install the distributions

<img width="571" height="412" alt="ubuntu set up" src="https://github.com/user-attachments/assets/d318db7e-da32-47f8-a248-8059fe10331f" />

For ubuntu the set up was straight forward and easy

<img width="571" height="412" alt="kali set up" src="https://github.com/user-attachments/assets/bd42c9d2-23fc-4a95-abeb-e43af73d6671" />

For kali I didnt have to go through the set up as I downloaded a pre installed iso

### Step 3:

Then I had to create snapshots of ubuntu and kali. Snapshots are important as they allow you to revert the os to a previous state. This allows you to experiment, break and repair things, without consequences

<img width="896" height="748" alt="ubuntu snapshot" src="https://github.com/user-attachments/assets/d3f7b4bd-fde9-47d0-b659-adeff0b125d5" />

Snapshot of ubuntu

<img width="891" height="744" alt="kali snapshot" src="https://github.com/user-attachments/assets/f17c02fb-1673-41ed-a9d0-02ec81a92a5b" />

Snapshot of kali









