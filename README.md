<h1 align="center">
  <a href="https://github.com/OMNIPOTENTHAVOC">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=28&pause=1000&color=00FF9C&center=true&width=900&lines=>+Siddhansh+Srivastava;>+(OMNIPOTENTHAVOC);>+Cybersecurity+%7C+Systems+Engineering;Built+from+the+terminal+up">
  </a>
</h1>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:00ff9c,100:0a0a0a&height=2">
</p>

<p align="center">
  <b>Systems-first security engineering.</b><br>
  <b>Understanding software by pushing it to failure.</b>
</p>

<br>

## **About Me**

```bash
omni@sidsri:~$ whoami
# > Systems-focused security engineer specializing in low-level analysis.

```

I have a strong interest in how software behaves under real constraints—memory, execution flow, permissions, and misuse. My work centers around:

* **Linux Internals:** Privilege boundaries and process isolation.
* **Applied Cryptography:** Implementation realities vs. theoretical security.
* **Defensive Design:** Analyzing failure states to build resilience.

I focus on **how things break**, because that’s how secure systems are built.

---

## **Current Focus**

* **Applied Cryptography** (AES, hashing, key management)
* **Linux Kernel & Internals** (Process isolation, memory safety)
* **Network Protocol Analysis** (Packet inspection, handshake integrity)
* **Threat Modeling** (Reducing attack surfaces in embedded systems)

---

## 🛠 **Tech Stack**

<p align="center">
  <img src="https://img.shields.io/badge/C-0a0a0a?style=for-the-badge&logo=c&logoColor=00ff9c">
  <img src="https://img.shields.io/badge/C%2B%2B-0a0a0a?style=for-the-badge&logo=c%2B%2B&logoColor=00ff9c">
  <img src="https://img.shields.io/badge/Java-0a0a0a?style=for-the-badge&logo=openjdk&logoColor=00ff9c">
  <img src="https://img.shields.io/badge/Python-0a0a0a?style=for-the-badge&logo=python&logoColor=00ff9c">
  
  <br>

  <img src="https://img.shields.io/badge/MySQL-0a0a0a?style=for-the-badge&logo=mysql&logoColor=00ff9c">
  <img src="https://img.shields.io/badge/Bash-0a0a0a?style=for-the-badge&logo=gnu-bash&logoColor=00ff9c">
  <img src="https://img.shields.io/badge/Linux-0a0a0a?style=for-the-badge&logo=linux&logoColor=00ff9c">
  
  <br>

  <img src="https://img.shields.io/badge/Cryptography-0a0a0a?style=for-the-badge&logo=letsencrypt&logoColor=00ff9c">
  <img src="https://img.shields.io/badge/Networking-0a0a0a?style=for-the-badge&logo=cisco&logoColor=00ff9c">
</p>

---

## **Featured Projects**

<table>
  <tr>
    <td width="50%" valign="top">
      <h3> > rawsniff (Low-level Network Analysis)</h3>
      <p>
        <em>C • Raw Sockets • Protocol Parsing • Systems Security</em>
      </p>
      <p>
        A raw socket packet sniffer written in C that captures live traffic using AF_PACKET and parses Ethernet → IPv4 → TCP/UDP manually — no libpcap, no abstractions.</b>.
      </p>
      <br />
      <strong>The Mission (What it does)</strong>
      <ul>
        <li>Captures packets directly from the network interface.</li>
        <li>Parses Ethernet, IPv4 (variable header length), TCP & UDP.</li>
        <li>Extracts ports, sequence numbers, flags, TTL.</li>
        <li>Converts multi-byte fields using ntohs() / ntohl().</li>
      </ul>
      <strong>Systems Insight (What I learned)</strong>
      <ul>
        <li>How the kernel exposes packets via SOCK_RAW.</li>
        <li>Why endianness matters at the wire level.</li>
        <li>Why ihl * 4 is required for IPv4 parsing.</li>
        <li>How tools like Wireshark work.</li>
        <li>The boundary between kernel networking stack and user-space.</li>
      </ul>
      <br />
      <a href="https://github.com/OMNIPOTENTHAVOC/pkt_sniff">
        <img src="https://img.shields.io/badge/View_Source-0a0a0a?style=for-the-badge&logo=github&logoColor=00ff9c">
      </a>
    </td>
    <td width="50%" valign="top">
      <h3> > Secure Encrypted Chatroom</h3>
      <p>
        <em>Python • X25519 • HKDF • AES-256-GCM • TLS 1.3</em>
      </p>
      <p>
        A standards-based end-to-end encrypted group chat implementing modern cryptographic primitives and replay protection with a zero-knowledge relay server.
      </p>
      <br />
      <strong>The Mission (What it does)</strong>
      <ul>
        <li>X25519 ECDH key exchange (RFC 7748)</li>
        <li>HKDF-SHA256 key derivation (RFC 5869)</li>
        <li>AES-256-GCM authenticated encryption</li>
        <li>Sequence numbers + sliding window replay defense</li>
        <li>TLS 1.3 secure transport</li>
      </ul>
      <strong>Systems Insight (What I learned)</strong>
      <ul>
        <li>Why key agreement ≠ secure messaging.</li>
        <li>Forward secrecy vs post-compromise security.</li>
        <li>How replay protection actually works in practice.</li>
        <li>The complexity of group key establishment.</li>
        <li>Where protocol design fails without formal modeling.</li>
      </ul>
      <br />
      <a href="https://github.com/OMNIPOTENTHAVOC/sec_chat">
        <img src="https://img.shields.io/badge/View_Source-0a0a0a?style=for-the-badge&logo=github&logoColor=00ff9c">
      </a>
    </td>
  </tr>
</table>

---
## 📈 SYSTEM METRICS

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=OMNIPOTENTHAVOC&show_icons=true&theme=dark&hide_border=true&bg_color=0a0a0a&title_color=00ff9c&icon_color=00ff9c&text_color=ffffff" width="48%" />
  
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=OMNIPOTENTHAVOC&layout=compact&theme=dark&hide_border=true&bg_color=0a0a0a&title_color=00ff9c&text_color=ffffff" width="48%" />
</p>

---
## **Connect**

<p align="center">
<a href="https://github.com/OMNIPOTENTHAVOC">
<img src="https://img.shields.io/badge/GitHub-0a0a0a?style=for-the-badge&logo=github&logoColor=00ff9c">
</a>
<a href="https://www.linkedin.com/in/siddhansh-srivastava-86214a326">
<img src="https://img.shields.io/badge/LinkedIn-0a0a0a?style=for-the-badge&logo=linkedin&logoColor=00ff9c">
</a>
</p>

---

<p align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:00ff9c,100:0a0a0a&height=2">
</p>

<p align="center">
<i>Understanding failure is the foundation of security.</i>
</p>
