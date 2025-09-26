# Network Scanning Project Using Nessus

## Objective
The goal of this project is to perform network vulnerability scanning using **Tenable Nessus Essentials**. 
The scan identifies live hosts, open ports, running services, and potential vulnerabilities in authorized systems. 
This is intended for educational purposes and ethical cybersecurity practice.


## Tools Used
- **Tenable Nessus Essentials (v10.9.4)**
- **Operating System:** Windows 11
- **Targets:** 
  - Laptop Wi-Fi: <Host IP>
- **Browser:** Google Chrome / Edge


## Procedure
1. **Installation & Setup**
   - Downloaded and installed Nessus Essentials from the official website.
   - Registered using the free activation key.
   - Downloaded and installed the latest plugin set.

2. **Scan Creation**
   - Opened Nessus GUI → **Scans → New Scan → Basic Network Scan**.
   - Named scans (`MyLaptop - Wi-Fi Scan`).
   - Entered targets: <Host IP>.
   - Left other settings as default (common ports, discovery).

3. **Scan Execution**
   - Launched scans and monitored progress.
   - Waited for scans to complete.

4. **Results Analysis & Export**
   - Checked vulnerability counts (Critical, High, Medium, Low).
   - Viewed host information and services.
   - Exported results as **.nessus** files.
   - Created a PDF report using **browser print-to-PDF**.


- **Wi-Fi IP Scan <Host IP>**:
  - Detailed vulnerability report categorized by severity.
  - Vulnerabilities included configuration issues and outdated software.

> All scans were conducted on systems owned or explicitly authorized for testing.


## Conclusion
- Nessus Essentials successfully identified hosts, open ports, services, and vulnerabilities.
- The project provided practical experience in network scanning, vulnerability assessment, and report generation.
- Ethical scanning practices and license limitations (max 16 IPs) were followed.
- Future improvements include performing authenticated scans and scanning multiple hosts in a controlled lab network.
