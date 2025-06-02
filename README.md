# 📡 Network Traffic Capture and Analysis using Wireshark

## 🧰 Requirements

- **Wireshark** (Install from [https://www.wireshark.org/](https://www.wireshark.org/))
- Internet connection
- A network interface (Wi-Fi)
- Basic browsing or ping command to generate traffic

---

## 🧪 Steps Performed

1. **Installed Wireshark**
   - Version used: 4.4.6

2. **Started Capture**
   - Interface: wlan0 
   - Duration: ~2 minute

3. **Generated Traffic**
   - Opened a web browser and visited `https://example.com`

4. **Stopped Capture**
   - Saved the capture file as `network_traffic.pcap`

5. **Applied Filters in Wireshark**
   - `tcp`
   - `udp`
   - `dns`
   - `http`

6. **Analyzed Protocols**
   - Identified common protocols:
     - TCP
     - UDP
     - DNS
     - ICMP
     - TLS/SSL

7. **Exported Findings**
   - Capture saved as `.pcap` file
   - Summary of packet types and traffic provided in the report

---

## 📁 Files Included

- `network_traffic.pcap` – Captured packet data file
- `Report.docx` – Detailed analysis and summary (optional)
- `README.md` – This file

---

## 📊 Sample Insights

- **DNS Query:** `example.com` resolved to `93.184.216.34`
- **HTTP Request:** TCP connection over port 80
- **TLS Handshake:** Detected over port 443
- **ICMP Echo:** Successful ping request and reply to `8.8.8.8`

---

## ✅ Conclusion

This project demonstrates how to:
- Capture real-time network traffic
- Filter and analyze packets using protocol types
- Interpret low-level data to understand network behavior

Wireshark is a powerful tool for learning and applying network forensics and cybersecurity fundamentals.

---

## 🔒 Disclaimer

This capture and analysis was performed on a personal network for educational purposes only. Do not intercept or analyze traffic from networks without proper authorization.

