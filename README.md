# 🔐 Week 3 – Password Cracking with JTR & Networkwalks Tools (WK3-PM1 & PM2)

![Skill](https://img.shields.io/badge/Skill-Cybersecurity-red)
![Tool](https://img.shields.io/badge/Tool-John_the_Ripper-blue)
![Tool](https://img.shields.io/badge/Tool-NW_Password_Cracker-teal)
![OS](https://img.shields.io/badge/OS-Kali_Linux-black)
![Focus](https://img.shields.io/badge/Focus-Password_Security-orange)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

## 📌 Project Overview
This repository contains my Week 3 report for the Networkwalks Cybersecurity Internship (Batch B084). It covers cracking the password of a lab-provided locked PDF file using two different methods.

## 🧩 Modules Completed
| Module | Activity | Tool |
|---|---|---|
| W3-PM1 | Password cracking with a hash-cracking tool | John the Ripper (`pdf2john` + `john`) on Kali Linux |
| W3-PM2 | Password cracking with browser-based tools | Networkwalks Hash Calculator + Password Cracker |

## 🔎 What I Did
- **PM1:** Extracted the hash of `My Locked PDF1.pdf` with `pdf2john`, then cracked it with John the Ripper. Password found: `good-luck`, cracked in under 1 second using John's default wordlist.
- **PM2:** Used Networkwalks' own web tools on a separate file provided for this exercise, `My Locked PDF1 (for NW Tools).pdf`. After correcting a wordlist selection error, cracked the password `password1` and captured the exercise's flag.

## ⚠️ Findings
Both passwords were cracked almost instantly because they are common, dictionary-based words. The full risk analysis and recommendations are in the report below.

## 📄 Full Report
[View the full report (PDF)](WK3%20-%20PASSWORD%20CRACKING.pdf)

## 🎯 Key Learning Outcomes
- Extracting a crackable hash from an encrypted PDF
- Using John the Ripper to run a dictionary attack
- Using browser-based tools to achieve the same result with no software install
- Understanding why weak, common passwords are cracked almost instantly
- Documenting a cracking exercise clearly, with evidence and risk analysis

 ## EVIDENCE
View the full Screenshots Evidence
[📂 WK3.pm1&2](./wk3.pm1%262/)

## 👤Author
Clementina Oluchi A.
Cybersecurity Personnel || Aspiring Penetration Tester
