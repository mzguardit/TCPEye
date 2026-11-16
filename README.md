<div align="center">

# TCPEye 3.0 - Advanced Network Monitor & Firewall

**Real-Time TCP/UDP Socket Visibility & Native WFP Firewall for Windows (Since 2006)**

[![Platform](https://img.shields.io/badge/Platform-Windows%2010%20%2F%2011%20(64--bit)-0078D6?style=for-the-badge&logo=windows&logoColor=white)](#)
[![Since](https://img.shields.io/badge/Created-2006-00f5d4?style=for-the-badge&labelColor=0f172a)](#)
[![Engine](https://img.shields.io/badge/Engine-Native%20WFP%20%7C%20Zero%20.NET%20Bloat-3b82f6?style=for-the-badge&labelColor=0f172a)](#)
[![Website](https://img.shields.io/badge/SoftEdition-TCPEye%203.0-6366f1?style=for-the-badge&labelColor=0f172a)](https://www.softedition.com/tcpeye-3-0-tcp-udp-monitor-network-monitor/)

</div>

---

## Overview

**TCPEye** is a Windows network monitoring and application firewall utility originally created in **2006** by **Vincenzo Chieppa (SoftEdition / MZGuard)**. Built as a high-performance 64-bit native Windows application with zero .NET bloat, TCPEye 3.0 delivers granular visibility into live TCP and UDP traffic, mapping every socket directly to the responsible binary, PID, digital signature, and remote GeoIP destination.

---

## Screenshots

### TCPEye 3.0 - Network Monitor & Per-App Firewall
<div align="center">
  <img src="./assets/tcpeye-3.0-dashboard.png" alt="TCPEye 3.0 Dashboard" width="92%" />
</div>

### Classic Edition (2006 - 2010 Archive)
<div align="center">
  <img src="./assets/tcpeye-classic.png" alt="TCPEye Classic Interface" width="85%" />
</div>

---

## Core Architecture & Features

### 1. Real-Time TCP & UDP Monitoring
* **Socket-to-Process Attribution:** Resolve every TCP/UDP stream to its exact executable name, directory path, PID, and digital signature status.
* **Live Bandwidth Graphs & GeoIP Telemetry:** Track upload and download curves down to the second and plot outbound connections on an interactive 3D globe and country map.
* **Port Scan & Intrusion Warnings:** Detect external port sweeps and unauthorized internal probes in real time before lateral movement occurs.

### 2. Native Windows Filtering Platform (WFP) Firewall
* **Dual Inbound & Outbound Enforcement:** Define independent bidirectional policies per application directly inside the Windows security stack, persisting even when TCPEye is closed.
* **CIDR, IP Range & Domain Blocking:** Blacklist malicious IPs, CIDR subnets, or entire domains across all software.
* **TCP/IP Stack Hardening & Kernel Safeguards:** Built-in profiles to disable NetBIOS exposure, drop spoofed traffic, mitigate SYN attacks, and prevent accidental termination of critical OS processes.

### 3. Local Subnet & IoT Vulnerability Scanner
* **Automated Subnet Discovery:** Catalog LAN endpoints (routers, IP cameras, smart TVs, printers, NAS, IoT sensors) with MAC vendors, hostnames, and open listening ports.
* **Proactive Vulnerability Audit:** Flag exposed Telnet ports, unsecured RTSP streams, outdated UPnP services, and default web admin panels.

### 4. Zero-Telemetry Privacy
* Core monitoring operates **100% offline**: no socket data, packet logs, or IP records leave your machine.

---

## Free vs Pro Comparison

| Capability | TCPEye 3.0 Free | TCPEye 3.0 Pro |
| :--- | :--- | :--- |
| Live TCP & UDP Traffic (App, Host, Port, GeoIP) | Included | Included |
| Traffic Graph & Interactive 3D Globe | Included | Included |
| Socket-to-Process Inspector (Path, PID, Signature) | Included | Included |
| Port Scan Intrusion Alerts | Included | Included |
| LAN Device & IoT Vulnerability Scanner | Included | Included |
| Per-App Inbound/Outbound WFP Firewall | No | Yes (WFP Native Engine) |
| Domain & IP Subnet Blacklisting | No | Yes |
| Persistent Activity History Logs | No | Structured Daily Logs |
| Optional AI Security Assistant | No | Up to 300 queries / month |

---

## Releases & Verification

Download official builds from **[GitHub Releases](https://github.com/mzguardit/TCPEye/releases)** or the [SoftEdition Official Page](https://www.softedition.com/tcpeye-3-0-tcp-udp-monitor-network-monitor/).

> Requirements: Windows 10 or Windows 11 (64-bit). Administrator privileges required for WFP firewall enforcement and socket inspection.## 👤 Author & Heritage

Created by **Vincenzo Chieppa** ([SoftEdition](https://www.softedition.com/) / [MZGuard](https://mzguard.com/)).
* Part of the historical Windows security suite leading up to **MZGuard Zero Trust** and **Spectra**.
