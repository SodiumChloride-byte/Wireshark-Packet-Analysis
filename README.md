# Wireshark Packet Capture and Analysis (Task 5)

## 🎯 Objective
Capture live network packets using Wireshark, identify at least 3 protocols, and summarize the findings.

---

## 🛠 Tools
- [Wireshark](https://www.wireshark.org/) (Free and Open Source)

---

## 📌 Steps

### 1. Install Wireshark
- Download and install from the official website.
- Run it with administrator privileges.

### 2. Start a Capture
- Open Wireshark.
- Select your active network interface (usually Wi-Fi or Ethernet).
- Click the blue **shark fin** icon to start capturing.

### 3. Generate Network Traffic
- Open a web browser and visit a website.
  I just visited tryhackme.com
- Let it run for about a minute.

### 4. Stop Capture
- Click the **red square** button to stop.

### 5. Apply Filters
- HTTPS traffic:  
  ```
  https
  ```
- DNS traffic:  
  ```
  dns
  ```
- TCP traffic:  
  ```
  tcp
  ```

### 6. Export the Capture
- Go to **File > Save As...**
- Save the file as `sample_capture.pcap`.

### 7. Summarize Findings
- Identify at least 3 protocols (e.g., HTTP, DNS, TCP).
- Note down:
  - Source & destination IPs
  - Ports used
  - Basic description of the protocol’s role

---

## ✅ Outcome
By completing this task, you’ll gain:
- Hands-on packet analysis skills
- Awareness of network protocols
- Confidence in using Wireshark for troubleshooting

---

👉 More details: [report.md](./report.md)
