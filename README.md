# Section AI Scholarship Portfolio

This repository contains a curated collection of core automation tools, data extraction pipelines, and strategic diagnostic modules developed under the Section AI scholarship curriculum. These projects span systems architecture, automated environment provisioning, cybersecurity reconnaissance, memory tracking, and academic tooling.

---

## 1. Enrollment Trends Analysis
### Overview
This project provides a data-driven diagnostic assessment of systemic friction points and behavioral patterns that cause registration drops during peak enrollment weeks. The resulting matrices and insights are designed to help academic administrators and systems infrastructure teams optimize recruitment strategies and streamline registration pipelines.

### Key Features
* **Multi-Source Aggregation:** Analyzes unstructured system trace logs, payment gateway timeout error sheets, and student interface drop-off data.
* **Isolated Analytical Pathing:** Strictly isolates internal analytical reasoning paths from documented facts, cleanly categorizing data by system performance, UI complexity, and upfront deposit barriers.
* **Empirical Diagnostics:** Rejects vague, generalized assumptions about student behavior in favor of strict, raw data validation.

### Tech Stack & Formatting
* Markdown Comparative Matrices 
* System Log Analysis Pipeline

---

## 2. Linux Workstation Setup
### Overview
An environment-provisioning script that automates the post-installation setup of a fresh Linux distributionIt updates core packages, deploys customized visual desktop profiles, symlinks user configurations, and provisions development/privacy suites securely.

### Key Features
* **Core Provisioning & Security:** Run package manager updates and installs essential development libraries, a window manager, terminal emulators, and specified privacy applications.
* **Configuration Deployment:** Automates cloning of configuration dotfiles from a GitHub repository and symlinks them directly to their target paths (e.g., `~/.config/`).
* **Aesthetic Automation:** Relocates custom 4K desktop wallpapers (such as pixel art elements) to the system background directory and updates window manager environment theme variables.
* **Deployment Quality Check:** Executes a validation script to test tool availability and outputs a clean summary table confirming installation status.

### Tech Stack
* Shell Scripting (Bash / Zsh) 
* Linux Package Managers & Window Managers 

### Trigger Phrasing Patterns
* *"Help me spin up my personalized Linux development environment."* 
* *"Run the automation script to configure my custom desktop theme and privacy tools."* 

---

## 3. Network Security Reconnaissance Data Extraction
### Overview
A targeted parsing tool that transforms multiple unstructured network reconnaissance terminal outputs and error logs into a clean, structured Markdown security data reference table.

### Extracted Security Findings
The data parsing pipeline filters out system noise, unmappable packet drop entries, and timeout artifacts to isolate critical service vulnerabilities:

| Host IP | Port | Active Service | Version / Findings | Risk Profile |
| :--- | :--- | :--- | :--- | :--- |
| **192.168.1.50** | 22 | SSH | OpenSSH 7.6p1 (Susceptible to user enumeration)  | 🟡 Medium Risk  |
| **192.168.1.50** | 80 | HTTP | Apache httpd 2.4.29 (Permits cleartext traffic)  | 🟢 Low Risk  |
| **192.168.1.115** | 443 | HTTPS | nginx 1.14.0 (Secure web traffic active / valid SSL)  | 🔵 Informational |
| **192.168.1.201** | 445 | SMB | Microsoft-DS (EternalBlue patterns / MS17-010 detected) | 🔴 High Risk   |
| **192.168.1.201** | 3389 | RDP | ms-wbt-server (Network Level Authentication disabled)  | 🟡 Medium Risk  |

### Tech Stack
* Regex Data Wrangling
* Terminal Log Parsers

---

## 4. Peer Tutoring Study Guide Generator / Compiler
### Overview
An automated compilation framework designed to parse, sanitize, and restructure unstructured source texts, complex assignment sheets, and raw programming source code snippets into streamlined, beginner-friendly Markdown study guides optimized for peer mentoring.

### Key Features
* **Sanitization Engine:** Strips away disruptive terminal commands, redundant compiler warnings, and unparsed system error noise.
* **Logic Deconstruction:** Isolates core object-oriented architectural patterns (such as C++ class hierarchies) and core cybersecurity principles.
* **Accessible Simplification:** Translates abstract theories into real-world breakdowns while ensuring strict technical accuracy behind the accessible descriptions.
* **High Scannability:** Enforces a clean layout utilizing distinct heading hierarchies, selective bolding, and horizontal rules to separate concepts.

### Tech Stack
* C++ Standard OOP Reference Frameworks 
* Network Reconnaissance Playbooks (PortSwigger / TryHackMe styles) 

---

## 5. System Design SWOT Analyzer
### Overview
A rigorous architectural workspace that evaluates proposed technical changes, feature requests, and system design documents against foundational infrastructure layouts.

### Framework Execution Pipeline
Every proposed system update executes across an iterative Markdown analysis schema:
1. **Strategic SWOT Matrix:** A clear table mapping the Strengths, Weaknesses, Opportunities, and Threats of the feature proposal.
2. **System Architecture Impact:** A bulleted structural breakdown tracking performance thresholds, dependencies, and tech stack compatibility based on the project's System Architecture Description (SAD)[cite: 177, 190].
3. **Actionable Mitigation & Next Steps:** A numbered checklist prioritizing long-term system scalability and project roadmap alignment over short-term quick fixes.
---

## 6. C++ Memory Tracker CLI Tool
### Overview
A command-line prototyping tool built to parse raw C++ source files and visually map out active dynamic memory management patterns and pointer dependencies directly within the terminal console.

### Dynamic Auditing Scope
The tool parses source text to automatically identify and track three primary lifecycles:
* **Allocations:** Identifies memory initializations via `new`, `new[]`, or `malloc`.
* **Dependencies / Passes:** Traces assignments, reassignments, or cases where pointers are passed into running functions.
* **Deallocations:** Scans for where memory is freed using `delete`, `delete[]`, or `free`.

### Terminal Output Format
Outputs a clean, vertical visual tree via ANSI terminal colors mapping the pointer lifecycle:
* **Green:** Allocations (e.g., `[ALLOCATED] ptr -> line 14`).
* **Yellow:** Transfers and dependencies (e.g., `%%% [PASSED]`).
* **Red:** Deallocations (e.g., `%%% [FREED] -> line 45`).
* **Bold Red flag:** Pointers allocated but never freed within the scanned scope are explicitly flagged at the base of their tree execution map as a `[POTENTIAL LEAK]`.

### Tech Stack
* [cite_start]Python / Node.js standalone CLI environment [cite: 200]
* [cite_start]ANSI Terminal Color Protocols [cite: 206]
