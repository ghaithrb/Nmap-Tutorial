# Nmap Tutorial

## 🚀 Introduction

**Nmap** (Network Mapper) is a powerful tool used for network discovery and security auditing. It's widely used in penetration testing, network inventory, and vulnerability scanning. This tutorial covers essential Nmap usage and tips for beginners and professionals in the cybersecurity field.

## Author

Made by [Ghaithrb](https://github.com/ghaithrb)

## 📦 Features

- **Host Discovery**: Identify active hosts on a network.
- **Port Scanning**: Find open ports on target hosts.
- **Service Version Detection**: Discover the versions of services running on open ports.
- **OS Detection**: Identify the operating system of the target.

## 🔧 How to Use Nmap

### Basic Syntax

```bash
nmap [options] [target]
```

#### Examples

- Scan a Single IP Address
  ```bash
  nmap 192.168.1.1
  ```

- Scan a Range of IP Addresses
  ```bash
  nmap 192.168.1.1-10
  ```

- Scan for Open Ports
  ```bash
  nmap -p 22,80,443 192.168.1.1
  ```

- Service Version Detection
  ```bash
  nmap -sV 192.168.1.1
  ```

- Operating System Detection
  ```bash
  nmap -O 192.168.1.1
  ```

- Aggressive Scan
  ```bash
  nmap -A 192.168.1.1
  ```

#### Additional Options

- `-sS`: TCP SYN scan (stealth scan)
- `-sU`: UDP scan
- `-p`: Specify ports
- `-O`: OS detection
- `-A`: Aggressive scan (includes version, OS, and traceroute)

## 🛡️ Best Practices

- Use Nmap for authorized penetration testing only.
- Ensure that you have permission to scan a network to avoid legal issues.
- Combine Nmap with other tools like Wireshark for traffic analysis.

## 📄 License

This tutorial is licensed under the MIT License. See the LICENSE file for details.
