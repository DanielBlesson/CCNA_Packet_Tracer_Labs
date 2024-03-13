# Ethernet Lan Switching

# Abstract
In Ethernet LAN switching, switches learn MAC addresses by observing the source MAC address of frames received on each port. This learning process builds the MAC address table (also known as the CAM table or MAC address table) within the switch. Here's how you can check the learning of MAC addresses using the 'ping' command, 'show mac address-table', and 'clear mac-address-table dynamic' commands:

Using Ping Command:
You can initiate communication between two devices on the same network segment to ensure that the switch has learned the MAC address of the sending device. Here's how you can do it:

Ping from one device to another on the same network segment.
Once the ping is successful, the switch learns the MAC address of the sending device.
For example:
PC1# ping 192.168.1.2

Using show mac address-table:
The show mac address-table command displays the MAC address table entries on the switch. This command shows the MAC addresses learned by the switch and the corresponding interface where they were learned. Here's how you can use it:
Switch# show mac address-table

Using clear mac-address-table dynamic:
If you want to clear the dynamically learned MAC addresses from the table (for example, to refresh the table or troubleshoot network connectivity issues), you can use the clear mac-address-table dynamic command. Here's how you can use it:
Switch# clear mac-address-table dynamic
This command clears only the dynamically learned MAC addresses, leaving any statically configured MAC addresses intact.

# Preview
![Screenshot 2024-03-13 101935](https://github.com/DanielBlesson/CCNA_Packet_Tracer_Labs/assets/105119931/95815655-9147-46e5-a72b-f233c19f6d06)

--------------------------------------------------------------------------------------------------------------------------------------------------------------------

![Screenshot 2024-03-13 102517](https://github.com/DanielBlesson/CCNA_Packet_Tracer_Labs/assets/105119931/68b4cae2-ce39-4ba8-ade3-aa1ed486b17d)
