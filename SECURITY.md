# Security Policy

## Overview

The Analytical BB84 QKD Engine is a research and educational project
demonstrating Quantum Key Distribution concepts via simulation and
analytical modeling.

While it does not manage real cryptographic keys or production systems,
responsible security practices are essential.

---

## Supported Versions

Only the latest version of the repository is actively maintained.
Security-related fixes will be applied to the most recent release.

---

## Reporting a Vulnerability

If you discover a security issue or vulnerability, please do NOT open a
public GitHub issue.

Instead, report it responsibly by contacting the project maintainer
directly.

Please include:

- A clear description of the issue
- Steps to reproduce (if applicable)
- Potential impact or misuse scenario
- Relevant code snippets or screenshots (optional)

---

## In-Scope Issues

- Client-side vulnerabilities in the Streamlit application
- Unsafe handling of user-provided inputs
- Visualization logic that could lead to misleading or incorrect results
- Denial-of-service risks caused by unbounded computation

---

## Out-of-Scope Issues

- Vulnerabilities in third-party libraries (Qiskit, NumPy, Streamlit)
- Issues arising from incorrect local environment setup
- Attacks on hypothetical real-world QKD hardware (not modeled here)

---

## Responsible Disclosure

Security researchers are requested to:

- Act in good faith
- Avoid public disclosure before a fix is available
- Limit testing to what is necessary to demonstrate the issue

---

## Disclaimer

This project is intended for **education, visualization, and research**.
It must **not** be used as a production cryptographic system.
Real-world QKD deployments require certified hardware, authenticated
classical channels, and rigorous security proofs beyond the scope of this project.

---

Thank you for helping maintain a secure and trustworthy research codebase.
