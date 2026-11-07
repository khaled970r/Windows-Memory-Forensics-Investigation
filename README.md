# Windows Memory Forensics Investigation

## Project Overview
This academic group project investigates suspicious activity on a Windows 10 system using digital forensic techniques. The investigation covers evidence acquisition, memory analysis, file examination, and suspicious process identification.

## Tools and Technologies
- **FTK Imager** – RAM acquisition and forensic disk imaging.
- **Autopsy** – Digital evidence examination and file metadata analysis.
- **Volatility 3** – Memory forensics and process investigation.
- **VirusTotal** – File hash reputation analysis.

## Investigation Scope
The investigation examined three suspicious executable files:

- `KMSAuto Net.exe`
- `DLLInjector v2.exe`
- `wap.exe`

The analysis included file metadata, MD5 and SHA-256 hashes, process information, and antivirus detection results.

## My Contributions
As the group leader, my assigned responsibilities included:

- Capturing volatile memory (RAM) using FTK Imager.
- Investigating `DLLInjector v2.exe` using forensic evidence and Autopsy.
- Examining file metadata, MD5 and SHA-256 hashes, and VirusTotal results.
- Contributing to the investigation conclusion and documentation.

## Key Findings
The investigation identified suspicious executables and documented their associated forensic artifacts. Autopsy examination of `DLLInjector v2.exe` showed nine recorded executions, while file hash reputation checks provided additional evidence for evaluating the file.

## Project Documentation
The investigation report is available in the `Report` directory.

**Project Type:** Academic Group Project  
**Focus:** Digital Forensics, Memory Acquisition, Suspicious Process Analysis
