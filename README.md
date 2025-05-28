# 🛡️ Threat Intelligence – IoC Collection (Manual Validation)

This repository contains curated, manually validated Indicators of Compromise (IoCs) related to various malware campaigns.  
These indicators are contributed to help defenders, researchers, and the public in detecting threats.

---

## 📘 Master Table of IoCs

| Name      | Type             | Description                             | IPs IoCs              | Hashes IoCs              | Domain-URL IoCs         | Last Validated |
|-----------|------------------|-----------------------------------------|------------------------|------------------------|--------------------------|----------------|
| **Lumma** | Stealer Malware| Credential & crypto wallet stealer | [Link](https://github.com/dimaswahyudi7/IoC-Collections/blob/main/Lumma%20Stealer/ips.txt) | [Link](https://github.com/dimaswahyudi7/IoC-Collections/blob/main/Lumma%20Stealer/hashes) | [Link](https://github.com/dimaswahyudi7/IoC-Collections/blob/main/Lumma%20Stealer/domain-urls.txt) | May 2025|
| **Bad IP Reputation (Suricata & OSSEC)** | Reputation Feed | Manually validated IPs flagged by Suricata & OSSEC | [Link](https://github.com/dimaswahyudi7/IoC-Collections/blob/main/Bad%20IP%20Reputation/ips.txt) | – | – | May 2025 |
| **Qilin** | Ransomware | Qilin operates as a Ransomware-as-a-Service (RaaS) that employs double extortion tactics, whereby harvested data is exfiltrated and threatened of publication on the group's DLS, which is hosted on Tor | [Link](https://github.com/dimaswahyudi7/IoC-Collections/blob/main/Qilin/ips) | [Link](https://github.com/dimaswahyudi7/IoC-Collections/blob/main/Qilin/hashes) | [Link](https://github.com/dimaswahyudi7/IoC-Collections/blob/main/Qilin/domain-urls) | May 2025|
| **Remcos** | RAT | Remcos is a RAT type malware that attackers use to perform actions on infected machines remotely. This malware is extremely actively caped up to date with updates coming out almost every single month - (any.run) | [Link](https://github.com/dimaswahyudi7/IoC-Collections/blob/main/Remcos/ips) | [Link](https://github.com/dimaswahyudi7/IoC-Collections/blob/main/Remcos/hashes) | [Link](https://github.com/dimaswahyudi7/IoC-Collections/blob/main/Remcos/domain-urls) | May 2025|
| **Interlock** | Ransomware | Interlock is a relatively recent entrant into the ransomware landscape. First identified in 2023, it's a multi-functional malware strain used in ransomware-as-a-service (RaaS) operations - (any.run) | [Link](https://github.com/dimaswahyudi7/IoC-Collections/blob/main/Interlock/ips) | [Link](https://github.com/dimaswahyudi7/IoC-Collections/blob/main/Interlock/hashes) | [Link](https://github.com/dimaswahyudi7/IoC-Collections/blob/main/Interlock/domain-urls) | May 2025|
| **RansomHub** | Ransomware | RansomHub emerged in early February 2024 as a Ransomware-as-a-Service (RaaS) coinciding with the closure of ALPHV’s operations. ALPHV shut down its infrastructure following the significant fallout from a disruptive attack on Change Healthcare - (group-ib.com) | [Link](https://github.com/dimaswahyudi7/IoC-Collections/blob/main/RansomHub/ips) | [Link](https://github.com/dimaswahyudi7/IoC-Collections/blob/main/RansomHub/hashes) | [Link](https://github.com/dimaswahyudi7/IoC-Collections/blob/main/RansomHub/domain-urls) | May 2025|
| **DragonForce** | Ransomware | DragonForce is a Malaysia-origin RaaS operation active since August 2023, evolving from hacktivism to a profit-driven, multi-extortion model via its RansomBay data-leak site. It leverages phishing, CVE exploits (e.g., CVE-2021-44228, CVE-2023-46805), and RDP/VPN credential stuffing for initial access, then deploys Conti v3–derived payloads with AES/RSA and ChaCha8 encryption via a white-label affiliate panel supporting Windows, Linux, ESXi, and NAS builds - (sentinelone.com) | – | [Link](https://github.com/dimaswahyudi7/IoC-Collections/blob/main/DragonForce/hashes) | [Link](https://github.com/dimaswahyudi7/IoC-Collections/blob/main/DragonForce/domain-urls) | May 2025|

---

## 🙌 Purpose
These IoCs are shared for:
- Improving early threat detection
- Assisting SOC and IR teams
- Public defense and awareness

All indicators are manually reviewed.

---

## 🙋 Maintainer
Curated by [Dimas Wahyudi](https://www.linkedin.com/in/dimaswahyudi/) – Security Analyst
