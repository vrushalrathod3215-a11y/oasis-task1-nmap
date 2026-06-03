# Basic Network Scanning with Nmap

## Objective
The objective of this task is to perform a basic network scan using Nmap in order to identify open ports and services running on the local machine.

---

## Tool Used
- Nmap 7.97

---

## Commands Used

```bash
nmap localhost
```

```bash
nmap localhost > nmap_scan_results.txt
```

---

## Scan Results

| Port | State | Service | Description |
|------|--------|----------|-------------|
| 135/tcp | Open | msrpc | Microsoft Remote Procedure Call service |
| 445/tcp | Open | microsoft-ds | SMB file sharing service |
| 7778/tcp | Open | interwise | Application-specific service |

---

## Findings

- Port 135 is used for Microsoft RPC communication.
- Port 445 is used for SMB file and printer sharing in Windows systems.
- Port 7778 is associated with a locally running application/service.

---

## Screenshots
Screenshots of the Nmap scan output are included in the screenshots folder.

---

## Conclusion
This task helped in understanding how Nmap can be used to identify open ports and services running on a system. Network scanning is an important part of cybersecurity and system administration.
