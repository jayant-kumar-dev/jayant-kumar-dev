<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0f172a&height=200&section=header&text=Jayant%20Kumar&fontSize=44&fontColor=7dd3fc&animation=fadeIn&fontAlignY=38&desc=Post-Quantum%20Cryptography%20%7C%20Quantum%20Cryptanalysis%20%7C%20Applied%20Security&descAlignY=58&descSize=18&descColor=94a3b8" alt="Jayant Kumar banner" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&pause=1000&color=7DD3FC&center=true&vCenter=true&width=800&lines=Post-Quantum+Cryptography+%E2%80%A2+Quantum+Cryptanalysis;Learning+Parity+with+Noise+%E2%80%A2+Authentication+Protocols;Quantum+Key+Distribution+%E2%80%A2+LDPC+Codes;Independent+Research+%E2%80%A2+Applied+Cryptography;Building+Secure+Systems+for+a+Quantum-Ready+Internet" alt="Typing SVG" />
</p>

<p align="center">
  <a href="mailto:jayantkumar11102004@gmail.com"><img src="https://img.shields.io/badge/Email-0b1220?style=for-the-badge&logo=gmail&logoColor=7dd3fc" alt="Email" /></a>
  <a href="https://doi.org/10.5281/zenodo.21934507"><img src="https://img.shields.io/badge/Zenodo-10.5281%2Fzenodo.21934507-0b1220?style=for-the-badge&logo=zenodo&logoColor=7dd3fc" alt="Zenodo DOI" /></a>
  <a href="https://orcid.org/0009-0009-6272-6601"><img src="https://img.shields.io/badge/ORCID-0009--0009--6272--6601-0b1220?style=for-the-badge&logo=orcid&logoColor=7dd3fc" alt="ORCID" /></a>
  <a href="https://linkedin.com/in/jayant-jugal-kumar"><img src="https://img.shields.io/badge/LinkedIn-0f172a?style=for-the-badge&logo=linkedin&logoColor=7dd3fc" alt="LinkedIn" /></a>
  <a href="https://scholar.google.com/citations?user=YOUR_SCHOLAR_ID"><img src="https://img.shields.io/badge/Google%20Scholar-0b1220?style=for-the-badge&logo=googlescholar&logoColor=7dd3fc" alt="Google Scholar" /></a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=jayant-kumar-dev&label=profile%20views&color=0e7490&style=flat" alt="profile views" />
  <img src="https://img.shields.io/github/followers/jayant-kumar-dev?label=Followers&style=flat&color=0e7490&labelColor=0f172a" alt="followers" />
</p>

---

## About

I'm Jayant Kumar, a first-year Cyber Security undergraduate and independent researcher working across two threads: the **cryptanalysis of authentication protocols under quantum adversaries**, and the **practical migration path toward post-quantum cryptography** in real-world infrastructure. I research under the mentorship of Asst. Prof. Nitin Soni, and lead the CTF team **QuantumAegis**.

My work sits in three places at once — theory (superposition-query leakage, QKD finite-key thresholds), measurement (internet-scale PQC/TLS scanning), and tooling (open-source scanners and analysis frameworks that make the theory reproducible).

**Research focus**

- Quantum cryptanalysis of symmetric and lightweight authentication protocols
- Learning Parity with Noise (LPN) and its deterministic variants
- Spectral / Walsh–Hadamard methods for leakage characterisation
- Superposition-query security models (Q1 / Q2)
- Siftingless Quantum Key Distribution — finite-block, finite-key regimes
- LDPC code design for QKD information reconciliation (density evolution, BESC)
- Post-Quantum Cryptography deployment and migration (ML-KEM / hybrid TLS)
- Cryptographic Bill of Materials (CBOM) and PQC readiness assessment

---

## Publications

**Spectral Characterization of Superposition Leakage in Deterministic-LPN Authentication Protocols** (2026)
Preprint — Zenodo · CC BY 4.0
[**DOI: 10.5281/zenodo.21934507**](https://doi.org/10.5281/zenodo.21934507)

> Characterises, via Walsh–Hadamard spectral analysis, the structural leakage exposed when a deterministic-LPN authentication protocol is queried in superposition, together with an information-theoretic treatment of the keyed-secret setting.

**An Empirical Study of Post-Quantum Cryptographic Readiness Across Enterprise TLS Infrastructure** (2026)
IEEE conference paper package · with N. Soni

> Measurement study across 400 TLS endpoints spanning banking and multi-sector datasets, finding that the banking sector lags other sectors in hybrid PQC adoption. Built on the AegisGuard scanning pipeline.

**In progress**
*Reassessing Siftingless Quantum Key Distribution Under Matched Finite-Block and Finite-Key Conditions* — research note reproducing and extending BESC/LDPC density-evolution thresholds for siftingless QKD (Project **Q-FAIR**, Phase 1 complete).

---

## Research Interests

`Post-Quantum Cryptography` · `Quantum Cryptanalysis` · `Learning Parity with Noise` · `Quantum Key Distribution` · `LDPC Codes & Density Evolution` · `Authentication Protocols` · `Superposition-Query Security Models` · `Applied Cryptography` · `Spectral Analysis of Boolean Functions` · `Secure Protocol Design` · `TLS Security` · `Cryptographic Inventory (CBOM)`

---

## Research Software

### 🛡️ AegisGuard
Post-quantum-aware TLS security assessment platform. FastAPI backend, modular architecture, CBOM generation.

- TLS analysis and cipher-suite evaluation across a 13-stage auditing pipeline
- Cryptographic Bill of Materials (CBOM) generation, ML-KEM (Kyber) / hybrid PQC detection
- Certificate-chain validation, risk breakdown reporting, SQLite scan history
- Backbone of the 400-endpoint IEEE PQC-readiness measurement study

**National Finalist — Punjab National Bank Cyber Security Hackathon 2025–26**
[`github.com/jayant-kumar-dev/AegisGuard-Quantum-Safe-PQC-Scanner`](https://github.com/jayant-kumar-dev/AegisGuard-Quantum-Safe-PQC-Scanner) · **v2.1**

### 🌀 AegisGuard-Q
Reference implementation and analysis toolkit accompanying the superposition-leakage work.

- Walsh–Hadamard Transform analytics over protocol response functions
- Independent NumPy statevector cross-validator for spectral results
- 25-test regression suite; verified on Linux and Windows
- JSON / Markdown export for reproducible experiment records

[`github.com/jayant-kumar-dev/AegisGuard-Q`](https://github.com/jayant-kumar-dev/AegisGuard-Q) · **v2.0**

### 🔑 Q-FAIR
Four-phase research codebase reproducing and extending siftingless-QKD finite-key thresholds.

- `besc.py`, `distributions.py`, `de.py`, `table1.py` — BESC/LDPC density-evolution pipeline
- Quantized LLR-grid box-plus check-node implementation (replacing a divergent G-domain approach)
- 18 fast + 3 slow unit tests, full documentation, packaged via `pyproject.toml`
- Phase 1 complete: coarse Gate 1 threshold rows reproduced against Elkouss & Martinez-Mateo
- Next: Numba-accelerated box-plus kernel, full 14-row fine-grid Gate 1 sweep, then Gate 2 (PEG construction, sum-product decoding, rate adaptation)

### 🌊 Maritime GeoShield
Consent-based maritime cybersecurity monitoring dashboard — portfolio project.

- GIS-based vessel security visualisation on a Three.js globe
- OT/ICS monitoring with MITRE ATT&CK ICS technique mapping
- Mock telemetry and GPS-spoofing simulation for demonstration

---

## Achievements

<p align="left">
  <img src="https://img.shields.io/badge/IEEE%20Paper%20Package-0f172a?style=for-the-badge&labelColor=0f172a&color=155e75" alt="IEEE Paper" />
  <img src="https://img.shields.io/badge/Peer--Reviewable%20Preprint-0f172a?style=for-the-badge&labelColor=0f172a&color=155e75" alt="Preprint" />
  <img src="https://img.shields.io/badge/National%20Finalist%20%E2%80%94%20PNB%20Hackathon-0f172a?style=for-the-badge&labelColor=0f172a&color=155e75" alt="National Finalist" />
  <img src="https://img.shields.io/badge/Top%2013%25%20National%20CTF-0f172a?style=for-the-badge&labelColor=0f172a&color=155e75" alt="Top 13% CTF" />
</p>

- **IEEE measurement study** — 400-endpoint PQC/TLS readiness study across banking and multi-sector datasets, with N. Soni
- **Independent research output** — deposited preprint on superposition leakage in LPN-based authentication (Zenodo, CC BY 4.0)
- **National Finalist** — PNB Cyber Security Hackathon 2025–26
- **Top 13% nationally** — CTF competitions (1,250+ teams), Team Lead of **QuantumAegis**
- **Workshop organiser** — designed and ran a 6-session technical workshop series (SOC log analysis → full-stack architecture) for a first-year cohort

---

## Certifications

<p>
  <img src="https://img.shields.io/badge/CEH-0b1220?style=for-the-badge&logoColor=7dd3fc" alt="CEH" />
  <img src="https://img.shields.io/badge/CompTIA%20Security%2B-0b1220?style=for-the-badge&logo=comptia&logoColor=7dd3fc" alt="CompTIA Security+" />
  <img src="https://img.shields.io/badge/Google%20Cybersecurity-0b1220?style=for-the-badge&logo=google&logoColor=7dd3fc" alt="Google Cybersecurity" />
</p>

---

## Technical Environment

**Research & Cryptography**
<p>
  <img src="https://img.shields.io/badge/Python-0b1220?style=for-the-badge&logo=python&logoColor=7dd3fc" alt="Python" />
  <img src="https://img.shields.io/badge/NumPy-0b1220?style=for-the-badge&logo=numpy&logoColor=7dd3fc" alt="NumPy" />
  <img src="https://img.shields.io/badge/SageMath-0b1220?style=for-the-badge&logoColor=7dd3fc" alt="SageMath" />
  <img src="https://img.shields.io/badge/LaTeX-0b1220?style=for-the-badge&logo=latex&logoColor=7dd3fc" alt="LaTeX" />
  <img src="https://img.shields.io/badge/ML--KEM%20(Kyber)-0b1220?style=for-the-badge&logoColor=7dd3fc" alt="ML-KEM" />
  <img src="https://img.shields.io/badge/TLS%20%2F%20X.509-0b1220?style=for-the-badge&logoColor=7dd3fc" alt="TLS/X.509" />
  <img src="https://img.shields.io/badge/OpenSSL-0b1220?style=for-the-badge&logo=openssl&logoColor=7dd3fc" alt="OpenSSL" />
  <img src="https://img.shields.io/badge/CBOM-0b1220?style=for-the-badge&logoColor=7dd3fc" alt="CBOM" />
</p>

**Systems & Development**
<p>
  <img src="https://img.shields.io/badge/C-0b1220?style=for-the-badge&logo=c&logoColor=7dd3fc" alt="C" />
  <img src="https://img.shields.io/badge/C%2B%2B-0b1220?style=for-the-badge&logo=c%2B%2B&logoColor=7dd3fc" alt="C++" />
  <img src="https://img.shields.io/badge/FastAPI-0b1220?style=for-the-badge&logo=fastapi&logoColor=7dd3fc" alt="FastAPI" />
  <img src="https://img.shields.io/badge/React-0b1220?style=for-the-badge&logo=react&logoColor=7dd3fc" alt="React" />
  <img src="https://img.shields.io/badge/PostgreSQL-0b1220?style=for-the-badge&logo=postgresql&logoColor=7dd3fc" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Git-0b1220?style=for-the-badge&logo=git&logoColor=7dd3fc" alt="Git" />
  <img src="https://img.shields.io/badge/Docker-0b1220?style=for-the-badge&logo=docker&logoColor=7dd3fc" alt="Docker" />
  <img src="https://img.shields.io/badge/Linux-0b1220?style=for-the-badge&logo=linux&logoColor=7dd3fc" alt="Linux" />
</p>

**Security Operations**
<p>
  <img src="https://img.shields.io/badge/Wireshark-0b1220?style=for-the-badge&logo=wireshark&logoColor=7dd3fc" alt="Wireshark" />
  <img src="https://img.shields.io/badge/Burp%20Suite-0b1220?style=for-the-badge&logo=burpsuite&logoColor=7dd3fc" alt="Burp Suite" />
  <img src="https://img.shields.io/badge/Nmap-0b1220?style=for-the-badge&logo=nmap&logoColor=7dd3fc" alt="Nmap" />
  <img src="https://img.shields.io/badge/Splunk-0b1220?style=for-the-badge&logo=splunk&logoColor=7dd3fc" alt="Splunk" />
  <img src="https://img.shields.io/badge/ELK-0b1220?style=for-the-badge&logo=elastic&logoColor=7dd3fc" alt="ELK" />
  <img src="https://img.shields.io/badge/MITRE%20ATT%26CK-0b1220?style=for-the-badge&logoColor=7dd3fc" alt="MITRE ATT&CK" />
  <img src="https://img.shields.io/badge/YARA%20%2F%20Sigma-0b1220?style=for-the-badge&logoColor=7dd3fc" alt="YARA/Sigma" />
</p>

---

## GitHub Stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=jayant-kumar-dev&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0f172a&title_color=7dd3fc&icon_color=7dd3fc&text_color=cbd5e1" alt="GitHub stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=jayant-kumar-dev&layout=compact&theme=tokyonight&hide_border=true&bg_color=0f172a&title_color=7dd3fc&text_color=cbd5e1" alt="Top languages" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=jayant-kumar-dev&theme=tokyonight&hide_border=true&background=0f172a&stroke=7dd3fc&ring=0e7490&fire=7dd3fc&currStreakLabel=7dd3fc" alt="GitHub streak" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=jayant-kumar-dev&theme=tokyo-night&hide_border=true&bg_color=0f172a&color=7dd3fc&line=7dd3fc&point=cbd5e1" alt="Contribution Graph" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Contributions-50-1e293b?style=for-the-badge&labelColor=0f172a&color=10b981" alt="Contributions" />
  <img src="https://img.shields.io/badge/Lines%20of%20Code-30k%2B-1e293b?style=for-the-badge&labelColor=0f172a&color=10b981" alt="Lines of Code" />
  <img src="https://img.shields.io/badge/Visitors-225-1e293b?style=for-the-badge&labelColor=0f172a&color=10b981" alt="Visitors" />
  <img src="https://img.shields.io/badge/Followers-5-1e293b?style=for-the-badge&labelColor=0f172a&color=10b981" alt="Followers" />
</p>

---

## Environment Snapshot

```text
jayant@secure-research:~$
role         : undergraduate cybersecurity researcher, BCA (Cyber Security), Sobhasaria GoI
mentor       : Asst. Prof. Nitin Soni
focus        : quantum cryptanalysis, LPN authentication, siftingless QKD, post-quantum cryptography
preprint     : 10.5281/zenodo.21934507 - superposition leakage in deterministic-LPN
in-progress  : IEEE PQC/TLS readiness study (400 endpoints) - with N. Soni
              : Q-FAIR - siftingless QKD finite-key research note (Phase 1 complete)
projects     : AegisGuard, AegisGuard-Q, Q-FAIR, Maritime GeoShield
achievement  : National Finalist - PNB Cyber Security Hackathon 2025-26
ctf          : Top 13% national - Team Lead, QuantumAegis
certs        : CEH, CompTIA Security+, Google Cybersecurity
status       : researching - building - publishing
```

---

<p align="center">
  <i>Logic & focus meets artistry with care 🤍 — ship tools that respect both data and the people using them.</i>
</p>

<p align="center">
  <a href="mailto:jayantkumar11102004@gmail.com">jayantkumar11102004@gmail.com</a> •
  <a href="https://doi.org/10.5281/zenodo.21934507">Zenodo</a> •
  <a href="https://orcid.org/0009-0009-6272-6601">ORCID</a> •
  <a href="https://scholar.google.com/citations?user=YOUR_SCHOLAR_ID">Scholar</a> •
  <a href="https://linkedin.com/in/jayant-jugal-kumar">LinkedIn</a>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0f172a&height=100&section=footer" alt="footer" />
</p>
