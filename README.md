# Elevate Labs Cyber Security Internship - Task 5

## 🎯 Task: Capture and Analyze Network Traffic Using Wireshark

### 📝 Objective
Capture live network packets using Wireshark, filter traffic by protocol, and identify basic network protocols and traffic types.

---

### 🛠️ Tools Used
* **Wireshark** (Free and open-source packet analyzer)

---

### 🚀 Steps Performed
1. Opened **Wireshark** and started capturing live packets on the active network interface.
2. Generated network traffic by browsing websites and pinging servers (e.g., `ping google.com`).
3. Stopped the packet capture after approximately 1 minute.
4. Applied display filters (`dns`, `http`, `tcp`, `icmp`) to isolate and inspect specific protocols.
5. Reviewed the overall traffic breakdown using **Statistics > Protocol Hierarchy**.
6. Exported the captured traffic as a `.pcap` file (`Wireshark/tcpdump/... - pcap` format).
7. Captured screenshots of each filtered protocol and the protocol hierarchy for documentation.

---

### 🔍 Protocols Identified & Findings

1. **DNS (Domain Name System):**
   * **Filter used:** `dns`
   * **Observation:** Captured DNS queries and responses showing how domain names (e.g., website URLs) are resolved into IP addresses.

2. **HTTP (Hypertext Transfer Protocol):**
   * **Filter used:** `http`
   * **Observation:** Captured unencrypted web requests (such as `GET`) and server responses (such as `200 OK`).

3. **TCP (Transmission Control Protocol):**
   * **Filter used:** `tcp`
   * **Observation:** Observed reliable, connection-oriented communication, including the TCP 3-way handshake (`SYN`, `SYN-ACK`, `ACK`) and data transfer packets.

4. **ICMP (Internet Control Message Protocol):**
   * **Filter used:** `icmp`
   * **Observation:** Captured `Echo (ping) request` and `Echo (ping) reply` packets generated during connectivity testing.

5. **Protocol Hierarchy:**
   * Used `Statistics > Protocol Hierarchy` to view the percentage and packet count distribution of all protocols captured during the session.

*(Refer to the `Screenshots` folder for visual proof of each filter and the `.pcap` file for raw packet data.)*

---
