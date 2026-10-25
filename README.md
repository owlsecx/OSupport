# 🦉 OSupport

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux-0a0c10?style=flat-square"/>
  <img src="https://img.shields.io/badge/Category-OCore-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-1.0.0-cyan?style=flat-square"/>
</p>

> **OSupport** — Incident and system reporting tool with optional Telegram delivery (tokens via env, dry-run default)

---

> ⚠️ **AUTHORISED USE ONLY** — Use only on systems you own or have explicit written permission to test. Unauthorised use is illegal.

---

## 📌 Overview


OSupport is an incident and system-reporting tool that collects host and environment details into a structured report for support and triage. It gathers platform, resource and network information via psutil and can relay a report to a configured destination. It runs as a desktop application in the OWLSec theme.

---

## ✨ Features


- One-click collection of system and environment details (platform, resources, network)
- Uses psutil for live host metrics and socket information
- Incident-report composition for support and triage workflows
- Optional relay of reports to a configured endpoint (token/chat id via environment variables)
- Attachable screenshot/image support in the report
- Desktop UI in the OWLSec dark theme with an offline --self-test

---

## ⚙️ Requirements

- **Linux**
- **No Python installation needed** — runs as a standalone executable

---

## 🚀 Usage


```bash
./OSupport
./OSupport --self-test
./OSupport --help
```

---

## 📦 Part of OwlSec Toolkit

This tool is part of the **OwlSec** suite — a collection of 300+ security and privacy tools.

🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

MIT License — © Khaled S. Haddad

*Tools are distributed as pre-built executables. Source code is proprietary.*
