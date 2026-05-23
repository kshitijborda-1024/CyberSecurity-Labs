# IP Address Configuration Report

## 1. Objective

The objective of this practical was to configure static and dynamic IP addresses and understand basic network configuration techniques.

---

# 2. Environment Used

| Component | Details |
|---|---|
| Operating System | Kali Linux / Windows |
| Platform | VirtualBox |
| Tools Used | Terminal, ipconfig, ifconfig |

---

# 3. Introduction

IP addresses are used to identify devices on a network. Static IP addresses are manually assigned, while dynamic IP addresses are automatically assigned using DHCP.

---
    
# 4. Practical Tasks Performed

## 4.1 Viewing Current IP Configuration

### Linux Command

```bash
ifconfig
```

### Windows Command

```cmd
ipconfig
```

### Description

Checked the current network configuration and IP address information.


## 4.2 Configuring Dynamic IP Address

### Command

```bash
sudo dhclient
```

### Description

Requested a dynamic IP address from the DHCP server.


## 4.3 Configuring Static IP Address

### Command

```bash
sudo ip addr add 192.168.1.100/24 dev eth0
```

### Description

Configured a static IP address manually.

---

## 4.4 Connectivity Testing

### Command

```bash
ping 8.8.8.8
```

### Description

Tested network connectivity using ping command.

---

# 5. Commands Summary

| Command | Purpose |
|---|---|
| ip a | View IP configuration |
| ifconfig | View network interfaces |
| dhclient | Obtain dynamic IP |
| ipconfig | Windows IP configuration |
| ping | Test connectivity |

---

# 6. Learning Outcome

This practical improved understanding of IP addressing, DHCP configuration, static IP assignment, and basic networking concepts.

---

# 7. Conclusion

The practical successfully demonstrated how static and dynamic IP addresses are configured and verified in Linux and Windows environments.
