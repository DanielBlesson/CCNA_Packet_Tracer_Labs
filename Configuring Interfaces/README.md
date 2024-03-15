# Configuring Interfaces
# Abstract
'interface [interface_name]': This command is used to enter interface configuration mode for the specified interface. In the example provided, interface g0/0 is used to configure interface GigabitEthernet0/0.

'ip address [IP_address] [subnet_mask]': This command assigns an IP address and subnet mask to the specified interface. In the example, ip address 192.168.20.2 255.255.0.0 assigns the IP address 192.168.20.2 with a subnet mask of 255.255.0.0 to interface GigabitEthernet0/0.

'speed [speed_value]': This command sets the speed of the interface. In the example, speed 1000 sets the speed of GigabitEthernet0/0 to 1000 Mbps.

'duplex [duplex_setting]': This command sets the duplex mode of the interface. In the example, duplex full sets the duplex mode of GigabitEthernet0/0 to full duplex.

'description [description_text]': This command adds a description to the interface, providing information about its purpose or connection. In the example, description connected to sw1 adds the description "connected to sw1" to GigabitEthernet0/0.

'no shutdown': This command enables (brings up) the interface. In the example, no shutdown activates GigabitEthernet0/0, allowing it to transmit and receive data.

'interface range [interface_range]': This command allows configuration changes to be applied to a range of interfaces simultaneously. In the example, interface range g0/1-2 specifies interfaces GigabitEthernet0/1 to GigabitEthernet0/2.

'shutdown': This command disables (shuts down) the specified interface(s), preventing them from transmitting or receiving data. In the example, shutdown deactivates interfaces GigabitEthernet0/1 and GigabitEthernet0/2.

'write memory (or wr)': This command saves the current configuration to the startup configuration file, ensuring that changes are persistent across reboots.

'show startup-config': This command displays the contents of the startup configuration file, showing the configuration that will be applied upon reboot.

# Preview

![Screenshot 2024-03-15 122653](https://github.com/DanielBlesson/CCNA_Packet_Tracer_Labs/assets/105119931/72a4467c-74e5-438c-8b5c-02d290a00b50)


![Screenshot 2024-03-15 122710](https://github.com/DanielBlesson/CCNA_Packet_Tracer_Labs/assets/105119931/8e7b9596-e8e9-42a5-8044-eb1e47734635)

