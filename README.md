<div align="center">
  <img src="https://github.com/INTELEON404/Template/blob/main/tm%2B1.png" alt="Logo" />
</div>

# TEMPLATE-PLUS

[![Nuclei Version](https://img.shields.io/badge/nuclei-v3.3+-blue.svg)](https://github.com/projectdiscovery/nuclei)
[![License](https://img.shields.io/badge/license-MIT-red.svg)]()
[![Private](https://img.shields.io/badge/status-Private-important)]()

**TEMPLATE-PLUS** is a private, high-signal collection of premium Nuclei templates curated for professional penetration testing, red team operations, bug bounty hunting, and enterprise-grade automated security assessments.

This repository contains heavily optimized, low-false-positive, and stealth-oriented templates that go beyond the public nuclei-templates collection. All templates are battle-tested in real-world engagements and continuously refined for maximum detection accuracy and minimal noise.

---

## Features

- High-accuracy custom detection logic  
- Reduced false positives through advanced matchers & extractors  
- Stealth-focused payloads and request patterns  
- Regularly updated with zero-day and post-exploitation checks  
- Organized directory structure for large-scale template management  
- Compatible with Nuclei workflows and headless mode  
- Designed for integration into CI/CD, attack-surface monitoring, and red team pipelines  

---

## Installation

```bash
git clone https://github.com/your-username/TEMPLATE-PLUS.git
cd TEMPLATE-PLUS
```

### Update Templates

Keep the repository up to date with:

```bash
git pull origin main
```

(Private zero-day and high-value templates are pushed regularly.)

---

## Usage

Scan a single target:

```bash
nuclei -t TEMPLATE-PLUS/ -u https://target.com
```

Scan a list of targets:

```bash
nuclei -t TEMPLATE-PLUS/ -l targets.txt -c 100
```

Run with custom configuration (recommended for large scans):

```bash
nuclei -t TEMPLATE-PLUS/ -l targets.txt -c 200 -rl 300 -silent -severity critical,high
```

---

## Template Structure

```
TEMPLATE-PLUS/
├── cves/                  # CVE-specific detections (including 0-day)
├── vulnerabilities/       # Generic vulnerability classes
├── exposures/             # Tokens, backups, configs, panels
├── misconfiguration/      # Cloud, container, infra misconfigs
├── technologies/          # Advanced fingerprinting
├── network/               # Custom network protocol checks
├── takeover/              # Subdomain takeover patterns
├── token-spray/           # Secret & token validation
├── workflows/             # Multi-step attack chains
└── helpers/               # Reusable workflow helpers
```

---

## Contributing

This is a **private repository** intended for internal/authorized use only.

Contributions are accepted under strict organizational review. All submissions must follow internal security policies. External contributions or redistribution of these templates is strictly prohibited.

---

## Disclaimer

These templates are provided exclusively for authorized security testing and research on systems you own or have explicit permission to test.

The authors and contributors assume **no liability** for misuse, unauthorized scanning, or any damage resulting from the use of these templates.

---

## License

**MIT License** – All rights reserved.  
