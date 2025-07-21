# Python Scripts

## Overview
This folder contains Python scripts for automating cybersecurity tasks.

## Lab 1: Nmap Output Parser
- **Source**: Codecademy - Python for Cybersecurity
- **Objective**: Parse an Nmap XML output to extract open ports and services.
- **Steps**:
  1. Wrote a Python script to parse Nmap XML output.
  2. Tested the script on a sample Nmap scan from TryHackMe.
  3. Outputted results to a readable format.
- **Usage**:
  ```bash
  pip install -r requirements.txt
  python3 lab1_parse_nmap.py scan_output.xml
