# Hi there, I'm Aditya Jain 👋

> Computer Science and Engineering (Core) Undergraduate | Aspiring Security Researcher & Systems Developer

---

### 🎓 Academic Profile

| Field | Details |
| :--- | :--- |
| **Name** | Aditya Jain |
| **Registration Number** | `26BCE0309` |
| **Branch** | Computer Science and Engineering (Core) |
| **Focus Areas** | Offensive Security, Application Logic Auditing, Secure System Design |

---

### 🛡️ Why I Want to Join WhiteHats

As a Computer Science (Core) student, my primary goal is to **bridge the gap between building software and securing it**. Writing functional code is only one side of the coin; understanding how that code can be analyzed, manipulated, and defended is what transforms good software into resilient architecture.

I am eager to join **WhiteHats** to:
- **Sharpen Practical Ethical Hacking:** Move beyond high-level theory into hands-on offensive techniques, penetration testing, and defensive engineering.
- **Identify Critical Business Logic Flaws:** Master the ability to detect nuanced, contextual application flaws and architectural edge cases that automated security scanners overlook.
- **Architect Robust Defenses:** Learn attacker methodologies to design and implement dependable, defense-in-depth solutions from the ground up.
- **Collaborate & Compete:** Engage in real-world security challenges, compete in CTFs, and grow alongside an active, like-minded community passionate about cybersecurity.

---

### 🔬 Cybersecurity Case Study: The XZ Utils Backdoor

> *"Even the most battle-tested systems remain vulnerable to subtle, structural code manipulations that bypass automated scanners completely."*

#### 1. The Long-Con Supply Chain Infiltration
The **XZ Utils** incident (`CVE-2024-3094`) demonstrated a masterclass in patient, calculated supply chain compromise. A threat actor spent years establishing a reputable persona within the open-source ecosystem, earning maintainer trust on a critical compression library. Once trusted, they covertly injected an obfuscated, multi-stage backdoor targeting upstream build mechanisms to hook into `OpenSSH` (`sshd`), granting unauthorized remote control over target servers.

#### 2. The Discovery
The backdoor bypassed code audits, continuous integration pipelines, and static analysis tools. It was ultimately unmasked because an observant engineer investigated a minute anomaly: a **~500ms latency increase** and unusual CPU overhead during routine SSH authentication benchmarks. That intuition exposed one of the most dangerous software supply chain attacks before it reached widespread production environments.

#### 3. Key Takeaway & Security Philosophy
This incident exemplifies why I focus on **logical vulnerability discovery**. Standard automated tools are effective for known signature matches, but they fall short against deep, deliberate logic tampering. Spotting structural manipulation requires intuition, deep understanding of system architecture, and an adversarial mindset—the exact core competencies I aim to cultivate.

---

### ⚡ Technical Interests & Focus

- **Offensive Security & CTFs:** Binary analysis, network exploitation, and web application attack vectors.
- **Application Security (AppSec):** Business logic testing, access control auditing, and API security.
- **Systems & Supply Chain:** Dependency integrity, build pipeline hardening, and secure code review.

---

<p align="center">
  <i>"Security is not a feature you bolt on at the end; it is an architectural foundation."</i>
</p>
