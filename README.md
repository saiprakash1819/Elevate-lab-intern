TASK 1

🔐 Cyber Security Internship Task 1 - Port Scanning using Nmap

🎯 Objective
To perform a basic TCP SYN port scan using Nmap on a local network device and identify open ports to understand network exposure and potential security risks.

🛠 Tools Used

Nmap v7.95 – for network scanning

Command Prompt (Windows) – to execute the scan

🖥️ Target Device
IP Address Scanned: 192.168.56.1
Device Type: Local virtual network adapter
Latency: 0.0012s

📊 Scan Results

Port	State	Service
135	open	msrpc
139	open	netbios-ssn
445	open	microsoft-ds
1521	open	oracle

🔍 Key Observations

Port 135/139/445: Commonly used by Windows for file sharing and RPC. These can be high-risk if left unprotected.

Port 1521: Used by Oracle DB. Exposed database ports can lead to unauthorized access or data theft.

⚠️ Security Risks

Vulnerabilities like EternalBlue (SMB) can exploit open ports.

Unsecured Oracle DB access may lead to data breaches.

✅ Recommendations

Disable unused ports/services (especially RPC/SMB).

Use firewalls to block unauthorized access.

Keep systems updated with latest security patches.

📁 Repository Content

nmap_scan_results.txt – Raw scan output

scan_report.md – Detailed analysis of the scan










Ask ChatGPT
