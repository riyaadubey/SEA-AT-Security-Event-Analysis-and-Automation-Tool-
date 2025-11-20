# SEA-AT-Security-Event-Analysis-and-Automation-Tool-
The Security Event Analysis Automation Tool streamlines SOC investigations by automating IOC checks, phishing analysis, URL decoding, sandboxing, and brand monitoring. It integrates multiple threat-intel sources and secures API keys with encryption to speed up incident response.

# 🚨 Security Event Analysis Automation Tool

A comprehensive **SOC Analyst automation utility** designed to
streamline and accelerate the investigation of potential Indicators of
Compromise (IOCs). This tool automates common tasks such as threat
intelligence lookups, phishing analysis, brand monitoring, URL decoding,
and file sandboxing---ultimately reducing manual effort during incident
response.

It also implements **symmetric encryption** to securely store and
protect API keys, ensuring only users with the encryption key can modify
or view them.

## 📌 Features

### 🔍 IOC Reputation & Threat Intelligence Checks

Supports lookup of IPs, domains, URLs, and file hashes using: -
Virustotal - AbuseIPDB - AlienVault OTX - Spyse - Phishtank - URLScan.io

### 🌐 Network & DNS Intelligence

-   DNS lookup
-   Reverse DNS
-   WHOIS lookup
-   ISP identification

### 📧 Email Security & Phishing Analysis

-   Email address reputation (EmailRep.io)
-   Phishing URL analysis
-   File attachment sandboxing
-   Email header analysis
-   Phishing investigation guidelines

### 🔗 URL Decoding & Analysis

-   UTF-8 decoding\
-   Base64 decoding\
-   Office365 SafeLink decoding\
-   URL unshortening

### 🗂 File Analysis

-   Malware sandboxing\
-   Hash reputation checks

### 🛡 IOC Masking / Sanitization

Safely sanitize indicators before sharing.

### 🏷 Brand Monitoring

-   URL geography lookup\
-   UI comparison\
-   Reputation validation

## 🛠 Prerequisites

1.  Python 3.x\
2.  Install dependencies using `requirements.txt`\
3.  Obtain required API keys

## 🚀 How to Use

### 1️⃣ Clone the Repository

    git clone https://github.com/AzharAnwar9/Security-Event-Analysis-Automation-Tool/

### 2️⃣ Install Requirements

    pip install -r requirements.txt

### 3️⃣ Run the Tool

    python main_file.py

### 4️⃣ First-Time Setup

You will be prompted to enter API keys; they are stored securely with
symmetric encryption.

## 🤝 Pull Requests

Contributions are welcome!

## 📝 Change Log & Future Updates

-   Bulk IOC validation\
-   Red-team support tools

## 👤 Authors

**Riya Dubey, Rudra Potghan, Alfiya Khanam**
