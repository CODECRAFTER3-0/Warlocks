#Warlocks
Team ID - CC3H-178
Team - Pratham Jain (Leader) Ashmit Bajaj Vaibhav Dadwal Rahul

# Project Phantasm 🛡️

**Project Phantasm** is a sophisticated, AI-driven active cyber defense system and honeypot. It is designed to disrupt the 'Exploitation' phase of a cyberattack by trapping adversaries in a forensic labyrinth, analyzing their tactics in real-time, and exposing synthetic identity threats using Error Level Analysis (ELA).

## 🚀 Key Features

- **GhostPort Sniffer:** A stealthy network monitor that detects reconnaissance and port scans before the attacker even reaches the web gateway.
- **AI Forensic Engine:** Uses Error Level Analysis (ELA) to identify digital manipulations in uploaded ID documents by detecting metadata and compression inconsistencies.
- **Interactive Sinkhole:** A deceptive file repository designed to consume attacker time and resources while harvesting forensic data.
- **Remote Alerting:** Real-time push notifications via Discord/Slack webhooks for immediate incident response.
- **Forensic Command Center:** A centralized dashboard for monitoring active sessions, AI threat verdicts, and captured imagery.

## 🛠️ Architecture



The system consists of three distinct layers:
1.  **Network Layer:** Raw socket monitoring for TCP SYN packet detection.
2.  **Application Layer:** A FastAPI-based honeypot serving a deceptive "Internal Data Repository."
3.  **Analysis Layer:** A Python-based ELA engine using NumPy and Pillow for pixel-level metadata inconsistency detection.

## 📦 Setup & Installation

### Prerequisites
- Python 3.8+
- Administrator/Root privileges (Required for Raw Socket sniffing)
- Access to the local network (For multi-device demos)

### Installation
1. Clone the repository:
   ```bash
   git clone [https://github.com/yourusername/project-phantasm.git](https://github.com/yourusername/project-phantasm.git)
   cd project-phantasm

```
 2. Install dependencies:
   ```bash
   pip install fastapi uvicorn nest_asyncio pillow numpy requests
   
   ```
## 🖥️ Usage
 1. **Launch:** Run the integrated cells in your Python environment with administrative privileges.
 2. **Access Portal:**
   * **Attacker Gateway:** http://localhost:8002
   * **Admin Console:** http://localhost:8002/admin/phantasm-secret-42
 3. **Forensics:** Upload any image through the gateway to trigger the ELA engine. Modified images will display high error levels in the Forensic Console.
*If they think they're in, you've already won.*
```

### **Documentation Summary**
The PDF documentation has also been updated to emphasize the **Security Engineering** aspect:
* **Protocol Analysis:** How the sniffer identifies the TCP Three-Way Handshake.
    
* **Forensic Methodology:** The mathematical approach to Error Level Analysis.
    
* **Sinkhole Logic:** The use of 403 Forbidden and 401 Unauthorized mocks to simulate a hardened environment.

This documentation is now purely focused on the functional and technical strengths of the project. Your GitHub and PDF files are ready for final submission!

```
