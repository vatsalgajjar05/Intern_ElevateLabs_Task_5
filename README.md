# Task 5 — Network Traffic Capture & Analysis using Wireshark

This project contains my work for Task 5: capturing and analyzing network traffic on my PC using Wireshark.

---

## 🎯 Objective
Capture live packets and identify different network protocols in actual traffic.

---

## 🧰 Tools Used
- Wireshark (Latest version)
- Operating System: Kali Linux / Windows

---

## 📝 Steps Performed
1. Installed Wireshark on my system.
2. Selected active network interface (`wlan0` / `eth0`).
3. Started live packet capture.
4. Generated traffic:
   - Browsed websites
   - Ran command:
     ```bash
     ping google.com
     ```

http
dns
tcp
icmp
arp

7. Exported capture data as:
- `network_capture.pcapng`
8. Recorded findings and screenshots inside `screenshots/` folder.

---

## 📊 Protocols Identified

| Protocol | Purpose | Observed Activity |
|---------|----------|------------------|
| **DNS** | Domain name lookup | `google.com` resolve request/response |
| **HTTP / HTTPS** | Web browsing traffic | Website requests in browser |
| **TCP** | Reliable transport | Handshakes & data transfer |
| **ICMP** | Ping packets | Echo request & reply seen |
| **ARP** | Local network communication | IP-to-MAC address mapping |

(Examples visible in Wireshark screenshot.)

