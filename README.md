# Controlled Remote-Access Attack on an Android Emulator

## Project Overview

This project investigates a controlled remote-access attack against an Android emulator within an isolated and authorised laboratory environment.

The project follows the Cyber Kill Chain and examines the attack from both Red Team and Blue Team perspectives, focusing on exposed Android Debug Bridge (ADB) services, remote access, persistence and defensive detection.

## Objectives

- Investigate security risks associated with exposed Android debugging services.
- Demonstrate the Cyber Kill Chain in a controlled environment.
- Analyse network traffic and identify indicators of compromise.
- Investigate Android application behaviour and persistence.
- Implement defensive measures against suspicious network activity.

## Tools & Technologies

Kali Linux, Android Emulator, ADB, Nmap, Wireshark, Metasploit, Apktool, Bash, iptables and MITRE ATT&CK.

## Key Findings

- Identified an exposed ADB service on TCP port 5555.
- Established remote access to the Android emulator.
- Investigated Android application startup and persistence behaviour.
- Analysed network traffic associated with reconnaissance and command and control.
- Implemented firewall rules to block suspicious outbound communication.

## Repository Contents

- **information/** – Technical report and supporting documentation.
- **scripts/** – Scripts developed and used during the project.

## Disclaimer

This project was conducted for educational purposes within an isolated and authorised virtual laboratory environment.
