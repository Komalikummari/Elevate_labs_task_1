# Elevate_labs_task_1
# Task 1: Scan Your Local Network for Open Ports

## Objective
Discover open ports on devices in the local network using Nmap, and identify potential security risks. This is part of a basic cybersecurity reconnaissance exercise.

## Tools Used
- **Nmap** (Pre-installed on Kali Linux)
- **Wireshark** *(optional – not used for this task)*

---

## 🌐 Network Details
- **My IP Address:** `10.0.2.15`
- **Scanned Subnet:** `10.0.2.0/24`

---

## 🧪 Commands Used
sudo nmap -sS 10.0.2.0/24 -oN scan_results.txt
