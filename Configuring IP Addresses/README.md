# Configuring IP Addresses

# Abstract

To configure an IP address using the ip address command and to view the interface status using the show ip interface brief command on a Cisco router or switch, you would typically follow these steps:

1.Enter Privileged EXEC Mode: Access privileged EXEC mode on the router or switch. You can do this by typing 'enable' and entering the enable password if required.

2.Enter Global Configuration Mode: Type 'configure terminal' or 'conf t' to enter global configuration mode.

3.Navigate to the Interface: Select the interface to configure the IP address. You can do this by typing 'interface <interface>' where <interface> is the name of the interface you want to configure. For example, interface GigabitEthernet0/1.

4.Configure the IP Address: Use the 'ip address' command followed by the IP address and subnet mask. For example:
ip address 192.168.1.1 255.255.255.0

5.Bring Up the Interface: If the interface is administratively down, you'll need to bring it up using the 'no shutdown' command. 
For example: no shutdown

6.Exit Interface Configuration Mode: Type 'exit' to leave the interface configuration mode.

7.Verify Configuration: Use the 'show ip interface brief' command to verify that the interface is up and has the correct IP address assigned.

Here's an example session illustrating these steps:

Router> enable

Router# configure terminal

Router(config)# interface GigabitEthernet0/1

Router(config-if)# ip address 192.168.1.1 255.255.255.0

Router(config-if)# no shutdown

Router(config-if)# exit

Router(config)# exit

Router# show ip interface brief


This sequence of commands will configure the IP address on the specified interface and verify its status using the show ip interface brief command.

# Preview
![Screenshot 2024-03-14 093352](https://github.com/DanielBlesson/CCNA_Packet_Tracer_Labs/assets/105119931/053ccb4a-21b0-40a0-aed3-5b4bbeb3eb03)


![Screenshot 2024-03-14 093617](https://github.com/DanielBlesson/CCNA_Packet_Tracer_Labs/assets/105119931/b8e7e818-74f5-416b-a689-a76fdaa38595)



![Screenshot 2024-03-14 094022](https://github.com/DanielBlesson/CCNA_Packet_Tracer_Labs/assets/105119931/19cb4a23-b480-45fb-baaa-73f114e62b62)
