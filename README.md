#  Task 5 – Wireshark Network Traffic Analysis

## Objective:
Capture live network packets using Wireshark and identify basic protocols and traffic types.

---

## 📁 Files Included:
- `task5_capture.pcap` – Captured packet file
- `README.md` – This report

---

## 🔍 Protocols Identified:

1. **DNS (Domain Name System)**  
   - Resolves domain names like `google.com` into IP addresses.  
   - Total packets: 102 (IPv4) + 2806 (Multicast DNS over IPv6)

2. **ICMPv6 (Internet Control Message Protocol v6)**  
   - Used for ping operations.  
   - Total packets: 275

3. **TLS (Transport Layer Security)**  
   - Encrypts secure communication (used by HTTPS).  
   - Total packets: 2132 (IPv6) + 95 (IPv4)

4. **HTTP (Hypertext Transfer Protocol)**  
   - Used for unencrypted website browsing.  
   - Total packets: 46

5. **TCP (Transmission Control Protocol)**  
   - Manages connections and data transfer reliability.  
   - Total packets: 5613

---

## 📌 Tools Used:
- **Wireshark** – for packet capturing and protocol analysis
- **Kali Linux** – operating system used for the task

---

## 💡 Outcome:
This task improved my hands-on skills in packet analysis, protocol identification, and using Wireshark for basic network troubleshooting.

