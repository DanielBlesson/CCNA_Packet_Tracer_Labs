
# Basic Device Security

# Abstract
Securing network devices is crucial for maintaining the integrity and confidentiality of your network infrastructure. Here are some basic device security measures using the enable password, service password-encryption, and enable secret commands:

Enable Password:
The 'enable password' command sets a password required to access privileged EXEC mode (sometimes called enable mode or privileged mode). This mode allows users to make changes to the device's configuration. Here's how to set it:
Router(config)# enable password <password>

Service Password-Encryption:
By default, passwords configured on Cisco devices are stored in plain text, which is a significant security risk. The 'service password-encryption' command encrypts these passwords in the configuration file, making them less vulnerable to unauthorized access. Here's how to enable it:
Router(config)# service password-encryption

Enable Secret:
The enable secret command is similar to the enable password command but provides stronger encryption for the password. It's recommended to use enable secret over enable password. Here's how to set it:
Router(config)# enable secret <password>

By using these commands together, you can enhance the security of your network devices. However, keep in mind that these are just basic security measures. For comprehensive security, consider additional measures such as access control lists (ACLs), role-based access control (RBAC), Secure Shell (SSH) for remote access, and regular audits of device configurations. Additionally, always ensure that passwords are strong and changed regularly.

# Preview
![Screenshot 2024-03-12 195930](https://github.com/DanielBlesson/CCNA_Packet_Tracer_Labs/assets/105119931/a4185b48-226e-4e7a-920a-c1a383b729d2)
