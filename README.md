# Mohamed Omar Bacha — Cybersecurity & Penetration Testing Engineer

<p align="center">
  <img src="https://img.shields.io/badge/Role-Cybersecurity%20Engineer-blue?style=flat-square" alt="role" />
  <img src="https://img.shields.io/badge/Focus-Penetration%20Testing-red?style=flat-square" alt="focus" />
  <img src="https://img.shields.io/badge/Location-Tunisia-9cf?style=flat-square" alt="location" />
</p>

---

## 👋 About Me

I'm **Omar Bacha**, a cybersecurity engineer specializing in penetration testing, web application security, and network defense. I enjoy finding creative, reliable ways to discover vulnerabilities and harden systems.

* 🔧 Tools I use: **Burp Suite**, **Metasploit**, **Kali Linux**, **Nmap**, **Wireshark**, **John the Ripper**
* 🎯 Focus areas: Web App Pentesting, Network Security, Exploit Validation, Secure Configurations
* 📫 Contact: `omar.bacha@example.com` (replace with preferred contact)

---

## 🛠️ Skills & Expertise

* **Offensive Security:** Penetration testing methodologies, vulnerability discovery, exploit verification
* **Web Security:** OWASP Top 10, secure HTTP headers, authentication/authorization testing
* **Network Security:** TCP/IP, firewall evasion techniques, service enumeration, lateral movement basics
* **Tools & Platforms:** Burp Suite, Metasploit, Kali Linux, Nmap, Wireshark, Hashcat
* **Languages:** Bash, Python (scripting for automation & PoCs), basic PHP/SQL knowledge for testing

---

## 🔍 Penetration Testing Highlights

> These are real testing categories and findings I've performed and validated during engagements and CTFs.

### Web (HTTP / Application) — Notable Verifications

* **PHP — Command Injection**: identification and exploitation of unsanitized input leading to command execution on the host.
* **HTTP — User-Agent based bypasses**: manipulating `User-Agent` to bypass simple filters or WAF rules.
* **HTTP — IP Restriction Bypass**: techniques used to bypass IP-based access controls (e.g., header spoofing, trusted proxy exploitation).
* **HTTP — Directory Indexing**: discovery of exposed directories and sensitive files due to missing index pages.
* **HTTP — Headers**: verification of missing or misconfigured security headers (CSP, X-Frame-Options, HSTS, X-XSS-Protection).
* **HTTP — Improper Redirect**: identifying open redirect or incorrect redirect handling allowing forged flows.
* **HTTP — Verb Tampering**: testing for differences in handling between GET/POST/PUT/DELETE and abusing verb handling.

> Each of the above was confirmed via controlled testing, documented in engagement reports and, where appropriate, responsibly disclosed.

---

## 🔬 Typical Pentest Workflow

1. **Reconnaissance & Scanning** — DNS enumeration, port/service discovery, technology fingerprinting.
2. **Enumeration** — directory bruteforce, endpoint mapping, parameter discovery.
3. **Vulnerability Discovery** — automated scans + manual verification (Burp + custom scripts).
4. **Exploit & Proof-of-Concept** — carefully produce PoCs for confirmed issues (no destructive testing without permission).
5. **Reporting & Remediation Guidance** — clear findings, CVSS estimates, reproduction steps and remediation suggestions.

---

## 📁 Selected Projects / Demos

* **Internal Web App Audit (example)** — full web app assessment covering OWASP Top 10 issues, authenticated testing, and session management.
* **Network Segmentation Review** — scanned and validated segmentation controls, identified firewall misconfigurations.
* **CTF Write-ups** — several CTF challenges solved that demonstrate web and network exploitation skills.

> See the `projects/` folder for write-ups, PoCs and sanitized reports.

---

## 🧰 Tools & Resources

* **Burp Suite** — Proxy, scanner, intruder, repeater workflows
* **Metasploit** — exploit development and payload delivery in controlled labs
* **Kali Linux** — pentesting distribution for enumeration and exploitation
* **Nmap / Masscan** — discovery and network profiling
* **Wireshark** — packet capture and protocol analysis

---

## 📚 Certifications (optional)

* Offensive Security Certified Professional (OSCP) — *if applicable, add date*
* CompTIA Security+ — *if applicable, add date*
* Any other certs — *add here*

---

## 📫 Contact & Connect

* GitHub: [omar-bacha](https://github.com/omar-bacha) (replace with your handle)
* LinkedIn: [Omar Bacha](https://www.linkedin.com/in/omar-bacha) (replace)
* Email: `omar.bacha@example.com`

---

## ✨ Readme Styling & Images

To make this README visually appealing, I recommend:

* Use a profile banner at the top (e.g., `assets/banner.png`).
* Add a `screenshots/` folder for sanitized PoC images (e.g., Burp request/response, proof images) and link them inline like:

```md
![PoC - command injection](./screenshots/poc-command-injection.png)
```

* Add GitHub stats and languages cards:

```md
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=omar-bacha&layout=compact)
![Stats](https://github-readme-stats.vercel.app/api?username=omar-bacha&show_icons=true)
```

---

## ⚖️ Responsible Disclosure

I follow responsible disclosure policies: all real-world testing is performed with explicit authorization, and sensitive details/traces are kept out of public repositories unless sanitized or permissioned.

---

### Want it customized?

If you want, I can:

* Replace placeholder links and emails with your real handles.
* Produce a clean `assets/` folder (banner & sanitized PoC images) ready to drop into the repo.
* Convert this into a compact one-file `README.md` with inline images and icons.

---

*Generated for a cybersecurity engineer with a focus on penetration testing.*
