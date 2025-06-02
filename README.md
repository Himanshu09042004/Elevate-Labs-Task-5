# Elevate-Labs-Task-5
Captured live traffic using Wireshark while accessing Google and YouTube. Identified and analyzed protocols like TCP, DNS, and mDNS. Exported protocol-specific .pcapng files and documented findings for hands-on network analysis experience.

# 📡 Task 5 – Capture and Analyze Network Traffic Using Wireshark

## 🎯 Objective
To capture live network traffic using Wireshark, identify key protocols such as TCP, DNS, and mDNS, and analyze their behavior during web activities like accessing Google and YouTube.

---

## 🛠 Tools Used
- **Wireshark** – Packet analyzer
- **Operating System** – Kali Linux
- **Browsers** – Google Chrome, Youtube, Github
- **Commands** – `ping google.com`

---

## 🔄 Steps Performed

1. Installed and launched Wireshark.
2. Started capturing on the active Wi-Fi interface.
3. Visited websites like **Google** and **YouTube** to generate traffic.
4. Used terminal to run: `ping google.com`
5. Stopped capture after ~1 minute.
6. Applied protocol filters: `tcp`, `dns`, `mdns`.
7. Saved capture files protocol-wise in `.pcapng` format.
8. Documented the findings in this README.

---

## 📊 Protocols Identified

| Protocol | Purpose | Observation |
|----------|---------|-------------|
| TCP | Reliable data transmission | Packets exchanged between local machine and YouTube/Google servers |
| DNS | Domain name resolution | Queries for `google.com`, `youtube.com` |
| mDNS | Local network service discovery | Multicast queries to `.local` domains |

## 📌 Key Learnings

- Understood how to monitor and filter traffic with Wireshark.
- Learned to differentiate between DNS and mDNS protocols.
- Gained insights into TCP session establishment and communication.
- Practiced exporting and organizing network captures.

---

## ✅ Summary

Captured and analyzed live network traffic while accessing Google and YouTube. Identified TCP, DNS, and mDNS protocols using Wireshark. Exported findings in protocol-specific files and created a detailed report.

