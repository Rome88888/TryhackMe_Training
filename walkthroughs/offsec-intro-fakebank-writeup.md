# 🛠️ Offensive Security Intro – FakeBank Room Walkthrough

## 📅 Date:
July 09 2025

---

## 🧠 What I Learned

This was my first offensive security challenge on TryHackMe using their virtual machine. 
I learned that in order to become part of a **Red Team**, I must first understand how hackers think and operate.
This room introduced me to the basics of **web directory enumeration**.

---

## 💡 Tools Used

- **Gobuster** – a command-line tool for brute-forcing web directories
- **TryHackMe VM** – Kali-like machine in Try hack me website

---

## 🔍 Objective

The challenge simulated a vulnerable web application called **FakeBank**,
and my goal was to **find hidden or sensitive directories** on the website to access restricted functionality.

---

## 🖥️ Steps Taken

### 1. Opened Terminal
Started the virtual machine and opened a terminal.

### 2. Run Gobuster
Used Gobuster to scan the website for hidden directories.

```bash
gobuster dir -u http://fakebank.thm -w wordlist.txt
