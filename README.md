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
- [View the full report (PDF)](W3-PM-FINAL-Password-Cracking-Report.pdf)

## 🎯 Key Learning Outcomes
- Extracting a crackable hash from an encrypted PDF
- Using John the Ripper to run a dictionary attack
- Using browser-based tools to achieve the same result with no software install
- Understanding why weak, common passwords are cracked almost instantly
- Documenting a cracking exercise clearly, with evidence and risk analysis

  ## Evidences collected
- 01-PM1-john-menu-search.png — John the Ripper found in Kali's menu
- 02-PM1-2john-scripts-list.png — confirming pdf2john exists
- 03-PM1-file-copied-to-kali.png — PDF copied into ~/week3/jtr
- 04-PM1-pdf2john-hash-extracted.png — hash extraction command + output
- 05-PM1-john-cracked-good-luck.png — john hash1.txt result
- 06-PM1-pdf-opened-congratulations.png — PDF opened with good-luck
- 07-PM2-password-cracker-access-denied.png — the wordlist error
08-PM2-password-cracker-success-password1.png — cracked with password1
09-PM2-pdf-opened-flag-captured.png — flag captured

## 👤Author
Clementina Oluchi A.
Cybersecurity Personnel || Aspiring Penetration Tester
