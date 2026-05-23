# IP Address Configuration Notes

## Objective
Learn how to configure static and dynamic IP addresses in Linux and Windows systems.

# Concepts Learned
## Static IP Address
A manually configured IP address that does not change automatically.
### Advantages
- Stable connection
- Useful for servers
- Easier remote access
### Disadvantages
- Manual configuration required

## Dynamic IP Address (DHCP)
An automatically assigned IP address provided by a DHCP server.
### Advantages
- Automatic configuration
- Easier management
### Disadvantages
- IP address may change

# Commands Learned
## Linux
### Check IP Address
ifconfig
### DHCP Configuration
sudo dhclient
### Configure Static IP
sudo ip addr add 192.168.1.100/24 dev eth0

## Windows
### Check IP
ipconfig

### Release IP
ipconfig /release

### Renew IP
ipconfig /renew

# Skills Practiced
- IP address configuration
- DHCP understanding
- Static IP setup
- Network troubleshooting
- Connectivity testing

# What I Learned
- Difference between static and dynamic IP addresses
- How DHCP works
- How devices receive IP addresses
- Basic network troubleshooting

# Conclusion
This practical improved understanding of IP addressing and basic network configuration techniques used in networking and cyber security environments.
