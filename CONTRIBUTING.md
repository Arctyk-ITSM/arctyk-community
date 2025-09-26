# Contributing to Arctyk ITSM

Thank you for your interest in contributing to **Arctyk ITSM**!  
We welcome all contributions, whether it’s code, documentation, design, or ideas. This guide will help you get started.

---

## 📖 Table of Contents
1. [How to Get Involved](#-how-to-get-involved)
2. [Discussions](#-discussions)
3. [Issues](#-issues)
4. [Code Contributions](#-code-contributions)
5. [Development Setup](#-development-setup)
6. [Coding Standards](#-coding-standards)
7. [Pull Requests](#-pull-requests)
8. [Community Guidelines](#-community-guidelines)

---

## 🙌 How to Get Involved
There are many ways to contribute:
- Participate in [GitHub Discussions](https://github.com/Arctyk-ITSM/community/discussions).
- Report bugs and request features via [Issues](https://github.com/Arctyk-ITSM/arctyk-itsm/issues).
- Contribute code, docs, or tests with pull requests.
- Share your use cases and feedback to guide our roadmap.

---

## 💬 Discussions
Use [Discussions](https://github.com/Arctyk-ITSM/community/discussions) for:
- Asking questions
- Brainstorming new features
- Reviewing the roadmap
- Connecting with other users and contributors

---

## 🐛 Issues
- Search existing issues before creating a new one.  
- For bugs, include:
  - Steps to reproduce
  - Expected behavior
  - Actual behavior
  - Environment (OS, Python/Django version, etc.)
- For feature requests, describe the problem and the proposed solution.

---

## 💻 Code Contributions
We follow a modular approach:
- **arctyk-itsm** → full ITSM platform  
- **arctyk-tickets** → core tickets module
- **arctyk-inventory** → full asset inventory tracking system  
- Future apps (inventory, reports, etc.) will live in their own repos  

Contribute code to the relevant app repo, not the community repo.

---

## 🛠️ Development Setup
1. Fork the repo you want to contribute to (e.g., `arctyk-itsm` or `arctyk-tickets`).
2. Clone your fork locally:
   ```bash
   git clone git@github.com:your-username/arctyk-itsm.git
   cd arctyk-itsm
3. Create virtual environment:
    ```bash
     py -m venv .venv
     .\.venv\Scripts\activate
4. Install dependencies:
    ```bash
      pip install -r requirements.txt
5. Run tests:
    ```bash
      pytest
