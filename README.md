# The Security Sandbox: A Technical Cyber Security Journal

Welcome to **The Security Sandbox**, my technical cyber security journal and research blog, hosted live at:

> `https://bhattacharyaananya.github.io/Journal`

This repository powers the static site and serves as an open-source archive of deep dives, lab notes, tool walk-throughs, and security research write-ups. The goal is to break down complex security concepts into **highly technical, reproducible, and actionable** content for practitioners across blue teaming, offensive security, digital forensics, and applied cryptography.

---

## Repository Purpose

This repository serves as:

- The **backend source code** for the static site deployed via GitHub Pages.
- An **organized technical journal** of investigations, experiments, and research.
- A collection of **reproducible labs, scripts, and configurations** that others can clone, run, and extend.

If you are a SOC analyst, penetration tester, malware analyst, or security researcher, you can use this repository as both a reference and a lab notebook.

---

## Content Domains & Site Structure

The live site is structured into four core domains, exposed as logical paths.

### `/Blue-Team-SOC`

Focuses on defensive operations and SOC engineering:

- Incident response playbooks and runbooks.
- SIEM logging architectures (e.g., Wazuh, Splunk), log pipelines, and parsing.
- Detection engineering (rules, correlation searches, dashboards).
- Threat hunting methodologies and hypothesis-driven hunts.

### `/Offensive-Security`

Covers offensive tradecraft and red/purple teaming:

- VAPT (Vulnerability Assessment and Penetration Testing) write-ups.
- Custom exploit scripts and proofs-of-concept.
- Active defense mechanisms such as honeypots and deception infrastructure.
- Active Directory attack vectors, misconfigurations, and abuse paths.

### `/Digital-Forensics`

Dedicated to post-compromise analysis and forensic reconstruction:

- Host artifact analysis (registry, browser artifacts, event logs, etc.).
- Memory and disk forensics casework.
- Network packet analysis and `.pcap`-driven investigations.
- Blockchain ledger tracking and transaction analysis.

### `/Research-Crypto`

Explores cryptography and research-oriented topics:

- Explanations of cryptographic flaws and implementation weaknesses.
- Reverse engineering binaries and protocol implementations.
- Emerging paradigms such as post-quantum cryptography and hardware security.

---

## Tech Stack & Site Architecture

This journal is built as a **static site**, optimized for fast, distraction-free reading and code-heavy content.

- **Framework**  
  Built using GitHub Pages with native support for **Jekyll** (or replace with Hugo/Astro if applicable).

- **Styling**  
  Minimalist, markdown-focused theme optimized for:
  - Code block readability.
  - Syntax highlighting for scripts, configs, and PoCs.
  - Clean typography suitable for long-form technical reading.

- **Hosting**  
  Served via **GitHub Pages** as a project site at:  
  `https://yourname.github.io/your-repo-name`.

- **CI/CD**  
  Automated deployment via **GitHub Actions**:
  - On push to the `main` branch, the site is built and deployed to GitHub Pages.
  - Optional checks (linting/build) can be added to keep the site in a healthy state.

Update this section with the exact generator (Jekyll/Hugo/Astro), theme name, and workflow file paths you use.

---


## Example Directory Layout

A typical structure for this repository might look like:

- `/_posts` – Core blog posts and journal entries.
- `/Blue-Team-SOC` – SOC and blue-team focused content.
- `/Offensive-Security` – Offensive security labs and write-ups.
- `/Digital-Forensics` – Forensics case studies and artifacts.
- `/Research-Crypto` – Cryptography and research content.
- `/labs` – Reproducible lab environments, configs, and datasets.
- `/scripts` – Utility scripts, PoCs, and helpers.
- `/_config.yml` or equivalent – Static site configuration.
- `.github/workflows/` – GitHub Actions workflows for CI/CD.

Adjust names and paths to match your actual layout.

---

## Contributing

While this began as a personal technical journal, contributions and feedback are welcome:

- **Issues**  
  Open an issue to report bugs, broken links, or suggest new topics and improvements.

- **Pull Requests**  
  - Clearly describe the purpose and scope of your changes.
  - Follow existing writing style, formatting, and directory conventions.
  - Avoid including proprietary, confidential, or sensitive data in posts, code, or artifacts.

---

## Disclaimer

This repository may contain:

- Offensive security techniques, exploit proofs-of-concept, and malware-related analysis.
- Detailed forensic workflows applied to potentially malicious artifacts.

All material is provided **strictly for educational and defensive purposes**. Do not use any technique, script, or configuration from this repository against systems you do not own or lack explicit authorization to test. You are solely responsible for complying with all applicable laws, regulations, and organizational policies.

---

## License

Specify your license here, for example:

- [MIT License](https://opensource.org/licenses/MIT)
- [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0)

A clear license informs others how they can use, modify, and redistribute this work.
