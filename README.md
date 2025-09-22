# Elevate-Labs-Tasks
Task 1

# Scan Your Local Network for Open Ports

## Objective
Learn to discover open ports on devices in your local network to understand 
network exposure.


### Tools Used

- **Kali Linux** for penetration testing and security auditing.
- **Nmap** for network discovery and vulnerability scanning.
- **Wireshark** for network traffic analysis.

## Steps

Below are the key steps taken in the VAPT process:

### 1. Checking ip
Checked my ip address using 
ip a


![ip check](https://github.com/Abhijithprashanth/Elevate-Labs-Tasks/blob/main/ip%20check.png)

### 2. Nmap Installation
I already installed nmap on my kali. So here i checking its version by using

nmap --version


![Nmap version check](https://github.com/Abhijithprashanth/Elevate-Labs-Tasks/blob/main/nmap%20version.png)

### 3. To perform TCP SYN scan
Run nmap -sS 192.168.1.0/24 to perform TCP SYN scan



![TCP SYN Scan](https://github.com/Abhijithprashanth/Elevate-Labs-Tasks/blob/main/syn%20scan.png)

### 4. Analyze packet capture with Wireshark.
Analyzed packets using wireshark


### 5. Reporting
Finally, all findings were documented, including detailed descriptions of ip address, open ports, and packet analysis.
