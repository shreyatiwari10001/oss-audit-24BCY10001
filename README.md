# oss-audit-24BCY10001

Student Name: Shreya Tiwari
Registration Number: 24BCY10001
Course: Open Source Software
Chosen Software: Python (PSF License)

About This Project

This repository contains the technical implementation of an Open Source Software Audit Capstone Project.

The project presents a structured audit of Python as an open-source system, covering its origin and philosophy, license analysis, Linux footprint, ecosystem, and comparison with proprietary alternatives.

In addition, the repository includes five shell scripts that demonstrate practical knowledge of Linux systems and Bash scripting.

The complete written report (12–16 pages) has been submitted separately on the VITyarthi portal.

Repository Structure
oss-audit-24bce10196/
├── README.md
├── script1.sh
├── script2.sh
├── script3.sh
├── script4.sh
└── script5.sh
Scripts Overview
Script 1 — System Identity Report

File: script1.sh
Displays system information including Linux distribution, kernel version, current user, home directory, uptime, and operating system license.

Concepts Used: Variables, command substitution, formatted output

Execution:

chmod +x script1.sh
./script1.sh
Script 2 — FOSS Package Inspector

File: script2.sh
Checks whether Python is installed, retrieves version and package details, and provides a short note on its role in the open-source ecosystem.

Concepts Used: if-else statements, case statements, package inspection tools (dpkg/rpm), grep

Execution:

chmod +x script2.sh
./script2.sh
Script 3 — Disk and Permission Auditor

File: script3.sh
Audits important system directories and reports disk usage, ownership, and permissions.

Concepts Used: for loops, du, ls, awk

Execution:

chmod +x script3.sh
./script3.sh
Script 4 — Log File Analyzer

File: script4.sh
Analyzes a log file, counts occurrences of a specified keyword, and displays recent matching entries.

Concepts Used: while loops, grep, command-line arguments, counters

Execution:

chmod +x script4.sh
./script4.sh /var/log/syslog

Custom Keyword:

./script4.sh /var/log/syslog WARNING
Script 5 — Open Source Manifesto Generator

File: script5.sh
Collects user input and generates a personalized open-source philosophy statement saved to a text file.

Concepts Used: user input, string handling, file redirection

Execution:

chmod +x script5.sh
./script5.sh
Running All Scripts
chmod +x *.sh
Dependencies
Tool	Purpose
bash	Script execution
uname, uptime, whoami, date	System information
dpkg / rpm	Package inspection
du, ls, awk	Disk and permission analysis
grep	Log file analysis

Note:

On Debian/Ubuntu systems, use dpkg instead of rpm.
Python (python3) is typically pre-installed on most Linux distributions.
Final Note

All scripts are written in Bash and tested on a Linux environment. They rely only on standard GNU utilities and demonstrate practical understanding of open-source systems and Linux internals.
