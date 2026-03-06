# ⚛️ Quantum Security Defense Matrix

> **An interactive intelligence platform for visualizing quantum computing threats, post-quantum cryptography algorithms, and enterprise migration strategy.**

[![Live Demo](https://img.shields.io/badge/Live%20Demo-View%20App-00d4ff?style=for-the-badge&logo=github)](https://yourusername.github.io/quantum-defense-matrix)
[![License](https://img.shields.io/badge/License-MIT-7b2fff?style=for-the-badge)](LICENSE)
[![HTML](https://img.shields.io/badge/Built%20With-HTML%2FCS%2FJS-ff3860?style=for-the-badge&logo=html5)](index.html)
[![NIST](https://img.shields.io/badge/Standards-NIST%20FIPS%20203--206-00e676?style=for-the-badge)](https://csrc.nist.gov/projects/post-quantum-cryptography)

---

## 🖥️ Preview

A dark, terminal-style intelligence dashboard built for security professionals, researchers, and enterprise architects navigating the transition to post-quantum cryptography.

---

## 📡 What Is This?

The **Quantum Security Defense Matrix** is a single-file, zero-dependency interactive web application that maps the quantum threat landscape against modern cryptographic defenses. It is designed for:

- **Security architects** planning PQC migration roadmaps
- **CISOs and executives** needing a clear visual overview of quantum risk
- **Researchers and educators** teaching post-quantum cryptography concepts
- **Enterprise teams** conducting cryptographic asset risk assessments

---

## ✦ Features

### 6 Interactive Panels

| Panel | Description |
|---|---|
| **Overview** | Global threat status, domain exposure levels, and enterprise quantum readiness score |
| **Threat Landscape** | Full vulnerability table mapping algorithms to quantum attacks, risk levels, and remediation actions |
| **PQC Algorithms** | Interactive cards for all 4 NIST-finalized PQC standards plus QKD and code-based alternatives |
| **Mitigation Strategy** | 6-step framework, layered defense stack, and quick-win actions deployable immediately |
| **Migration Roadmap** | 2024–2030 timeline with priority matrix and regulatory compliance drivers |
| **Technique Comparison** | Full capability matrix, key size comparisons, and algorithm selection decision guide |

### Algorithms Covered

**Vulnerable (Classical)**
- RSA-2048, ECDSA, ECDH, Diffie-Hellman, DSA
- AES-128, SHA-256, TLS 1.2/1.3, SSH

**Quantum-Safe (PQC)**
- `CRYSTALS-Kyber` — FIPS 203 · Key Encapsulation Mechanism
- `CRYSTALS-Dilithium` — FIPS 204 · Digital Signature
- `FALCON` — FIPS 206 · Compact Digital Signature
- `SPHINCS+` — FIPS 205 · Stateless Hash-Based Signature
- `McEliece / BIKE` — Code-Based (NIST Round 4)
- `QKD` — Quantum Key Distribution (Physics-Based)

### Quantum Attacks Visualized
- **Shor's Algorithm** — breaks all public-key cryptography
- **Grover's Algorithm** — halves symmetric key security
- **Harvest Now / Decrypt Later (HNDL)** — the active threat happening today

---

## 🚀 Getting Started

### Option 1 — View Live (GitHub Pages)
Visit: `https://yourusername.github.io/quantum-defense-matrix`

### Option 2 — Run Locally
No installation required. Just download and open in any modern browser:

```bash
git clone https://github.com/yourusername/quantum-defense-matrix.git
cd quantum-defense-matrix
open index.html
```

### Option 3 — Deploy Your Own
1. Fork this repository
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)` folder
4. Your live URL will be: `https://yourusername.github.io/quantum-defense-matrix`

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Structure | HTML5 |
| Styling | CSS3 (custom properties, animations, grid) |
| Interactivity | Vanilla JavaScript |
| Fonts | Google Fonts — Orbitron, Rajdhani, Share Tech Mono |
| Dependencies | **Zero** — single file, no frameworks, no build step |

---

## 📋 Standards & References

This application is built around current official guidance from:

- **NIST FIPS 203** — Module-Lattice-Based Key-Encapsulation Mechanism (Kyber)
- **NIST FIPS 204** — Module-Lattice-Based Digital Signature Standard (Dilithium)
- **NIST FIPS 205** — Stateless Hash-Based Digital Signature Standard (SPHINCS+)
- **NIST FIPS 206** — FN-DSA (FALCON)
- **NSA CNSA 2.0** — Commercial National Security Algorithm Suite
- **NIST SP 800-208** — Recommendation for Stateful Hash-Based Signature Schemes
- **OMB M-23-02** — Federal quantum-safe cryptography migration mandate
- **ENISA / EU NIS2** — European quantum cybersecurity framework

---

## 🗺️ Roadmap

- [ ] Add live CVE feed integration for quantum-adjacent vulnerabilities
- [ ] Export mitigation checklist as PDF
- [ ] Organization-specific readiness scoring input form
- [ ] NIST PQC algorithm benchmark performance data
- [ ] Dark/Light theme toggle
- [ ] Embeddable widget mode for security portals

---

## 🤝 Contributing

Contributions, corrections, and pull requests are welcome. If NIST updates standards or new PQC research emerges, please open an issue or PR to keep the data current.

1. Fork the repo
2. Create a feature branch (`git checkout -b feature/add-hqc-algorithm`)
3. Commit your changes (`git commit -m 'Add HQC Round 4 algorithm card'`)
4. Push to the branch (`git push origin feature/add-hqc-algorithm`)
5. Open a Pull Request

---

## 📄 License

MIT License — free to use, modify, and distribute with attribution.

---

## ⚠️ Disclaimer

This tool is for **educational and planning purposes**. Threat timelines and risk assessments are based on current public research and expert consensus as of 2025–2026. Quantum computing timelines remain uncertain. Always consult a qualified cybersecurity professional for enterprise security decisions.

---

<div align="center">

**Built for the security community navigating the quantum transition.**

`CRYSTALS-Kyber` · `CRYSTALS-Dilithium` · `FALCON` · `SPHINCS+`

*Start your PQC migration today. The clock is running.*

</div>
