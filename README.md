# Ahmed Sophy Elzeky (0xZiki)

<p align="left">
  <strong>Cybersecurity Software Engineer & Offensive Tool Architect</strong><br>
  <em>Undergraduate in Computer Science @ Mansoura University, Egypt</em>
</p>

<p align="left">
  <a href="https://www.linkedin.com/in/ahmed-elzeky-a88a3641b"><img src="https://img.shields.io/badge/LinkedIn-Ahmed%20Elzeky-0A66C2?style=flat-square&logo=linkedin" alt="LinkedIn"></a>
  <a href="mailto:ahmedelzeky2446@gmail.com"><img src="https://img.shields.io/badge/Email-ahmedelzeky2446%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
  <img src="https://img.shields.io/badge/Focus-Systems%20%26%20Offensive%20Engineering-10B981?style=flat-square" alt="Focus">
</p>

---

### 📖 Featured Publication (The Flagship Treatise)

<table border="0">
  <tr>
    <td width="300" valign="top">
      <a href="https://github.com/0xZiki/Active-Directory-Protocol-Internals">
        <img src="https://raw.githubusercontent.com/0xZiki/Active-Directory-Protocol-Internals/main/cover.png" width="280" alt="Active Directory Protocol Internals">
      </a>
    </td>
    <td valign="top">
      <h3><a href="https://github.com/0xZiki/Active-Directory-Protocol-Internals">Active Directory Protocol Internals</a></h3>
      <em>Volume 1: Foundations — A First-Principles Guide to Enterprise Identity, Kerberos Cryptography, and Kernel Authorization</em>
      <br><br>
      An exhaustive 150+ page engineering textbook dissecting enterprise identity at the wire and kernel layers. Explores the mathematical underpinnings of Windows Access Tokens, binary security descriptors (SDDL), Netlogon RPC channels, Kerberos PAC dual-signatures, and multi-master directory replication.
      <br><br>
      <strong>Publication Standard:</strong> ISO B5 Trim • Typeset with Typst • Fully Open-Source (CC BY-NC-SA 4.0)<br>
      👉 <strong><a href="https://github.com/0xZiki/Active-Directory-Protocol-Internals">Read Online or Download Official PDF Release</a></strong>
    </td>
  </tr>
</table>

---

### 🛠️ Production Offensive Frameworks & Custom Tooling

I build high-performance, zero-dependency security engines from the ground up, avoiding superficial wrappers to maintain strict memory safety, concurrency, and protocol-level control (15,000+ lines of production code):

* **[Nemesis Core Framework](https://github.com/0xZiki/nemesis-framework)** — Asynchronous high-concurrency security engine (1,000+ req/s) built on dual-engine (Fast/Deep) architectures, tiered storage (RAM/Bloom Filter $\rightarrow$ SQLite), and circuit-breaker fault tolerance.
* **[GhostSniffer v2.0](https://github.com/0xZiki/Ghost_Sniffer)** — Zero-dependency stealth network reconnaissance engine implemented directly over raw sockets with manual RFC 1071 IP/TCP/UDP checksum calculations and half-open SYN scanning.
* **[UltronNet v2.0](https://github.com/0xZiki/UltronNet)** — Custom encrypted network protocol framework featuring automated SSL/TLS negotiation, bidirectional TCP port forwarding, and interactive PTY allocation.
* **[Recondo v2.0](https://github.com/0xZiki/Recondo)** — Multi-threaded web reconnaissance engine with dynamic jitter, auto-proxy health checks, and Smart-404 body-hash detection.

---

### 🎯 Applied Research & Enterprise Lab Exploitation

* **31+ Enterprise Machines Compromised:** Extensive practical experience across OffSec Proving Grounds Play and HackTheBox, targeting realistic corporate attack paths (zero CTF rabbit holes).
* **Multi-Tier Campaign Execution:** Proven kill-chain execution bridging web entry points to full Forest Dominance (e.g., *Odyssey* NoSQLi $\rightarrow$ WebAuthn bypass $\rightarrow$ DPAPI extraction $\rightarrow$ dMSA BadSuccessor; *DanglingTree* WAC RCE $\rightarrow$ AD CS ESC4).
* **API & Infrastructure Assessment:** Credly-certified in **API Penetration Testing (APISec University)**, analyzing REST/GraphQL endpoints, token forgery, and broken object-level authorization (BOLA).

---

### 🔬 Core Technical Stack & Primitives

```text
┌─────────────────────────┬────────────────────────────────────────────────────────┐
│ DOMAIN                  │ SPECIALIZATION & APPLIED PRIMITIVES                    │
├─────────────────────────┼────────────────────────────────────────────────────────┤
│ Enterprise Identity     │ Kerberos State Machines, NTLM Relay, AD CS (ESC1–ESC8) │
│ Operating System Core   │ Access Tokens, SRM Decision Trees, DACL/SACL Graphs    │
│ Network Engineering     │ Raw Sockets, RFC 1071 Checksums, ASN.1 BER, DNS-SRV   │
│ Systems Programming     │ Python (Asyncio / Sockets), C/C++ Systems, Linux/Bash  │
│ Tooling & Protocols     │ Impacket, BloodHound, NetExec, Wireshark, Burp Suite   │
└─────────────────────────┴────────────────────────────────────────────────────────┘
