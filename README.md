#  Ahmed Sophy Elzeky (0xZiki)

<p align="left">
  <strong>Cybersecurity Software Engineer & Offensive Tool Architect</strong><br>
  <em>Undergraduate in Computer Science @ Mansoura University, Egypt</em>
</p>

<p align="left">
  <a href="https://www.linkedin.com/in/ahmed-elzeky-a88a3641b"><img src="https://img.shields.io/badge/LinkedIn-Ahmed%20Elzeky-0A66C2?style=flat-square&logo=linkedin" alt="LinkedIn"></a>
  <a href="mailto:ahmedelzeky2446@gmail.com"><img src="https://img.shields.io/badge/Email-ahmedelzeky2446%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
  <img src="https://img.shields.io/badge/Focus-Network%20%26%20Identity%20Internals-10B981?style=flat-square" alt="Focus">
</p>

---

###  Flagship Publication (The Core Research)

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
      An exhaustive 143+ page engineering textbook dissecting enterprise identity at the wire and kernel layers. Explores the internal mechanics of Active Directory multi-master replication, Kerberos cryptographic workflows, PAC dual-signatures, NTLMv2 challenge-response, and Windows Security Descriptors (SDDL).
      <br><br>
      <strong>Standard:</strong> ISO B5 Trim • Typeset with Typst • Fully Open-Source (CC BY-NC-SA 4.0)<br>
      <strong>Academic Registration:</strong> <a href="https://doi.org/10.5281/zenodo.23282927">DOI: 10.5281/zenodo.23282927</a> (CERN / Zenodo Indexed)<br>
       <strong><a href="https://github.com/0xZiki/Active-Directory-Protocol-Internals">Read Online or Download Release</a></strong>
    </td>
  </tr>
</table>

---

###  Production Offensive Tooling & Network Engines

I build high-performance, low-level networking and reconnaissance tooling from the ground up, avoiding third-party dependencies to maintain raw socket control and protocol fidelity:

* **[GhostSniffer v2.0](https://github.com/0xZiki/Ghost_Sniffer)** — Advanced stealth network reconnaissance engine implemented directly over raw sockets with zero external dependencies. Features manual RFC 1071 IP/TCP/UDP checksum calculation, Layer-2 ARP discovery, TCP SYN half-open scanning, DNS protocol mimicry, and passive OS fingerprinting via TTL analysis.
* **[UltronNet v2.0](https://github.com/0xZiki/UltronNet)** — Custom encrypted network transport and command utility ("Swiss Army Knife"). Built in a single unified architecture supporting bidirectional TCP/UDP sockets, automated SSL/TLS self-signed negotiation, interactive PTY shell allocation, and concurrent port forwarding.

---

###  Core Technical Stack & Applied Domains

```text
┌─────────────────────────┬────────────────────────────────────────────────────────┐
│ DOMAIN                  │ SPECIALIZATION & APPLIED PRIMITIVES                    │
├─────────────────────────┼────────────────────────────────────────────────────────┤
│ Enterprise Identity     │ Kerberos State Machines, NTLM Relay, AD CS (ESC1–ESC8) │
│ Operating System Core   │ Access Tokens, SRM Decision Trees, DACL/SACL Graphs    │
│ Network Engineering     │ Raw Sockets, RFC 1071 Checksums, ASN.1 BER, DNS-SRV   │
│ Systems Programming     │ Python 3.8+ (Asyncio, Raw Sockets, PTY), Bash, Linux   │
│ Tooling & Protocols     │ Impacket, BloodHound, NetExec, Wireshark, Typst        │
└─────────────────────────┴────────────────────────────────────────────────────────┘
