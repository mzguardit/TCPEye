<div align="center">

# 👁️ TCPEye — Real-Time TCP/UDP & Threat Monitor

**Windows Network Visibility & Process Inspection Tool — Originally Created in 2006**

[![Platform](https://img.shields.io/badge/Platform-Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)](#)
[![Legacy](https://img.shields.io/badge/Since-2006-00f5d4?style=for-the-badge&labelColor=0f172a)](#)
[![Website](https://img.shields.io/badge/SoftEdition-TCPEye-3b82f6?style=for-the-badge&labelColor=0f172a)](https://www.softedition.com/tcpeye-3-0-tcp-udp-monitor-network-monitor/)
[![Releases](https://img.shields.io/github/v/release/mzguardit/TCPEye?style=for-the-badge&color=6366f1&labelColor=0f172a)](https://github.com/mzguardit/TCPEye/releases)

</div>

---

## 📌 Overview

**TCPEye** is a Windows network monitoring and security utility created in **2006** by **Vincenzo Chieppa (SoftEdition / MZGuard)**. It lists all active **TCP/IP and UDP ports** on the local system and maps every connection directly to the owning process—giving analysts, sysadmins, and security researchers immediate visibility into what is communicating on their machine.

Over its evolution (**v1.0 → v2.0 → v3.0**), TCPEye expanded from a lightweight classic port viewer into a security-focused monitor combining real-time socket inspection with anomaly detection and **YARA-based threat analysis**.

---

## 🖼️ Screenshots

### Modern Interface (AI & YARA Threat Analysis)
<div align="center">
  <img src="./assets/tcpeye-nextgen.png" alt="TCPEye Next-Gen Interface" width="90%" />
</div>

### Classic Edition (Historical Archive)
<div align="center">
  <img src="./assets/tcpeye-classic.png" alt="TCPEye Classic Interface" width="85%" />
</div>

---

## ✨ Key Capabilities

* **Real-Time TCP/UDP Monitoring:** View all open local/remote ports and active connections with configurable refresh intervals (down to 1 second).
* **Deep Process Attribution:** Inspect process name, full executable path, version metadata (product name, description), creation time, and owning user.
* **Suspicious Activity Highlighting:** Automatically flags unidentified processes lacking version info or icons, as well as suspicious patterns (beaconing, unusual destination ports like mining pools).
* **Active Response:** Close unwanted TCP connections, terminate offending processes, and block suspicious IPs.
* **Forensic & Threat Intelligence (v2.0 / v3.0):** Historical connection tracking, AI-powered anomaly detection, and custom **YARA rule** integration for threat hunting.
* **Multi-Format Export:** Save active TCP/UDP connection reports to **HTML**, **XML**, or **tab-delimited text**.

---

## 📦 Download & Releases

Pre-built binaries and historical releases are available in the **[GitHub Releases](https://github.com/mzguardit/TCPEye/releases)** section.

> Always verify the **SHA-256** checksum published in each release before running executables.

---

## 👤 Author & Heritage

Created by **Vincenzo Chieppa** ([SoftEdition](https://www.softedition.com/) / [MZGuard](https://mzguard.com/)).
* Part of the historical Windows security suite leading up to **MZGuard Zero Trust** and **Spectra**.
