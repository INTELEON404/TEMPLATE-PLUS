<div align="center">
  <img src="https://github.com/INTELEON404/Template/blob/main/tm%2B1.png" width="600" alt="TEMPLATE-PLUS Logo"/>
  <br><br>
</div>

[![Nuclei Version](https://img.shields.io/badge/nuclei-v3.3%2B-blue.svg)](https://github.com/projectdiscovery/nuclei)
[![License](https://img.shields.io/badge/license-Private-red.svg)]()
[![Status](https://img.shields.io/badge/status-Private-important)](#)

**TEMPLATE-PLUS** is a private, high-signal collection of premium Nuclei templates curated exclusively for professional penetration testing, red team operations, bug bounty hunting, and enterprise-grade automated security assessments.

This repository contains heavily optimized, low-false-positive, and stealth-oriented templates that significantly outperform the public `nuclei-templates` collection. Every template is battle-tested in real-world engagements and continuously refined for maximum accuracy, evasion, and operational impact.

---

**DRIVE:** [Open Folder 📂](https://drive.google.com/drive/folders/1cwdX88xhUrPlvjSz8QRkEtO3q_dxJazY?usp=sharing)


---

## Features

- High-accuracy detection with advanced matchers & extractors  
- Dramatically reduced false positives  
- Stealth-optimized payloads and request patterns  
- Regular updates including zero-day and post-exploitation checks  
- Clean, modular directory structure for enterprise-scale management  
- Full compatibility with Nuclei workflows, headless mode, and automation  
- Built for seamless integration into CI/CD, ASM, and red team pipelines  

---

## Installation

```bash
git clone https://github.com/your-username/TEMPLATE-PLUS.git
cd TEMPLATE-PLUS
```

### Update Templates

```bash
git pull origin main
```

> Private high-value and zero-day templates are pushed frequently.

---

## Usage

Single target:
```bash
nuclei -t TEMPLATE-PLUS/ -u https://target.com
```

Multiple targets:
```bash
nuclei -t TEMPLATE-PLUS/ -l targets.txt -c 100
```

Large-scale / production scanning:
```bash
nuclei -t TEMPLATE-PLUS/ -l targets.txt -c 200 -rl 300 -silent -severity critical,high -headless -bulk-size 50
```

---

## Template Structure

```
TEMPLATE-PLUS/
├── cves/              # CVE-specific & zero-day detections
├── vulnerabilities/   # Generic vulnerability classes
├── exposures/         # Tokens, backups, panels, configs
├── misconfiguration/  # Cloud, container & infrastructure misconfigs
├── technologies/      # Advanced tech fingerprinting
├── network/           # Custom network-layer checks
├── takeover/          # Subdomain & service takeover
├── token-spray/       # Secret & token validation
├── workflows/         # Multi-step attack chains
└── helpers/           # Reusable helpers & payloads
```

---

## Contributing

This is a **private repository** for authorized/internal use only.

Contributions are welcome under strict review and must comply with organizational security policies.  
External contributions, forks, or redistribution of these templates are strictly prohibited.

---

## Disclaimer

These templates are intended **exclusively** for authorized security testing and research on systems you own or have explicit written permission to test.

The authors and contributors assume **no liability** for any misuse, unauthorized scanning, or resulting damage.

---

## License

**Private License** – All rights reserved.  
Unauthorized distribution or use is prohibited.

<div align="center">
  <sub>Crafted for elite security teams.</sub>
</div>
