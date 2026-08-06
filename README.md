# Hi, I'm Mario Aguilar 👋

**Systems Administrator** — automation-focused
📍 McAllen, TX → relocating to Austin, TX

Systems Administrator at a managed service provider supporting 1,000+ endpoints
across 35+ client sites. My work spans incident response, identity and access
management, and automating the repetitive parts of MSP operations. Bachelor's in
Computer & Information Technology.

I introduced PowerShell automation to a team that had none, and most of what's
here came out of problems nobody assigned me.

---

### 🚀 Projects

* **[Windows 11 Readiness Audit](https://github.com/Marioaaj/Win11-Readiness-Data-Pipeline)**
  PowerShell hardware diagnostics paired with Python log parsing to assess
  upgrade eligibility at scale. Validated across 1,000+ production endpoints for
  30+ HIPAA-regulated clients, cutting manual audit labor roughly 85% and giving
  leadership the data to approve hardware refreshes.

* **[PowerShell Script Masterlist](https://github.com/Marioaaj/PowerShell-Script-Masterlist)**
  RMM-deployable scripts for multi-endpoint operations. Includes remediation for
  the legacy fax modem driver vulnerability (`ltmdm64.sys`) — reads a per-machine
  report, confirms whether the file exists, and logs the result. Also covers bulk
  process termination, AD user moves, group membership auditing, and shortcut
  deployment.

* **Alert-to-Ticket Automation** *(internal — not public)*
  Service monitoring in N-Central for a Dell server fleet with automatic ticket
  creation on failure. Reduced time-to-remedy by 31%.

* **BitLocker Deployment Automation** *(internal — not public)*
  Automated encryption rollout across 15+ client locations through N-Central
  policies, with recovery keys written to custom properties — removing manual key
  tracking entirely.

---

### 🔒 Security Work

* First responder during an active network intrusion — traced the initial access
  vector through Windows Event Viewer, identified Mimikatz credential-dumping in
  SentinelOne EDR, and escalated findings that drove country-level geo-blocking
  at the perimeter.
* Proposed MFA to leadership after the breach and led the Cisco Duo rollout
  across 15 locations, including an RDP Gateway behind Duo under a zero-trust
  policy. Follow-up log review surfaced credential sharing by a third-party
  vendor; the evidence went to executives and the vendor was terminated.
* Business email compromise investigations across client M365 tenants — Exchange
  message trace, Defender alerts, sign-in log review, and hunting persistence
  including malicious inbox rules and scheduled-task remnants.
* Caught a silently failing backup routine through manual log review during a
  live threat event. Recovered affected Hyper-V VMs from Cove Data Protection —
  restored the VHDs and rebuilt the VM configurations to point at them. Full
  recovery, no permanent data loss.
* Provisioned remote access for 50+ users on a least-privilege model — per-user
  OpenVPN profiles, scoped N-Central accounts limiting each user to their
  assigned machines, and folder permissions managed through AD groups.

---

### 🛠️ Tech Stack

| Category | Tools & Technologies |
| :--- | :--- |
| **Scripting & Automation** | PowerShell, Python, n8n |
| **Systems & Identity** | Windows Server 2012 R2–2022, Active Directory, Microsoft 365 |
| **Virtualization** | Hyper-V — VM management, backup and restore, host administration via RMM |
| **Security** | SentinelOne, Cisco Duo, Microsoft Defender, BitLocker, Adlumin |
| **Monitoring & RMM** | N-Central, Cove Data Protection |
| **Networking** | TCP/IP, VLANs, DHCP, QoS, Peplink firewalls, OpenVPN site-to-site & per-user, Cambium wireless |
| **Databases** | MySQL / MariaDB — tuning, slow-query analysis, upgrades |
| **Homelab** | WireGuard, Tailscale, Docker |

---

### 📫 Connect with Me

* **LinkedIn:** [linkedin.com/in/mario-a-aguilar](https://www.linkedin.com/in/mario-a-aguilar)
* **Email:** [mario661962@yahoo.com]
* **Location:** Based in McAllen, TX | **Actively Relocating to Austin, TX**

*"Automating the boring stuff so I can build the cool stuff."*
