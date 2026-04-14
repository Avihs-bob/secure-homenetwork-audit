# 🔐 Home Network Security Audit (Level 2)

## 📌 Overview
This project demonstrates a structured home network security assessment using Kali Linux and Nmap. The objective was to identify active devices, analyze exposed services, classify risks, and improve overall network security.

---

## 🛠️ Tools Used
- Kali Linux  
- Nmap (Network Scanning Tool)

---

## 🎯 Objectives
- Discover devices connected to the network  
- Identify open ports and services  
- Classify devices based on security risk  
- Reduce attack surface through hardening  

---

## 🌐 Methodology

### 1. Network Discovery
```bash
nmap -sn 192.168.x.0/24
