# VytoHack-2.0
## 💀 Project E.L.L.I.O.T. Protocol

### *The Sentient Cyber-Defense Initiative & Autonomous Neural Interface*

[![Python](https://img.shields.io/badge/Language-Python%203.x-blue.svg)](https://www.python.org/)
[![AI](https://img.shields.io/badge/Core-Gemini%201.5%20Flash-magenta.svg)](https://deepmind.google/technologies/gemini/)
[![Security](https://img.shields.io/badge/Capabilities-Offensive%20%26%20Defensive-red.svg)]()
[![Status](https://img.shields.io/badge/System-OPERATIONAL-brightgreen.svg)]()

> *"Control is an illusion. But ELLIOT is real."*

---

## 🚀 Introduction

**Project ELLIOT** is not just a virtual assistant; it is a **weaponized, voice-activated cyber-intelligence platform**. 

Born from the need to bridge the gap between biological intent and digital execution, ELLIOT fuses the cognitive supremacy of Google's **Generative AI** with a ruthless arsenal of low-level cybersecurity tools. It is designed to act as an autonomous co-pilot for security analysts, penetration testers, and developers, executing complex technical operations through simple voice commands.

---

## ⚔️ The Arsenal (Key Features)

ELLIOT is equipped with a hyper-advanced suite of modules designed for total information dominance:

### 🧠 1. The Neural Core (Advanced AI Mode)
* **Powered by Gemini 1.5 Flash:** Engage in deep, contextual technical discussions. ELLIOT remembers conversation history, strategizes attack vectors, and writes code.
* **Voice-First Interface:** Powered by `SpeechRecognition` and ultra-realistic `edge-tts` synthesis.

### 🦠 2. Autonomous Malware Analysis
* **Static Binary Deconstruction:** Instantly parses PE headers, extracts hidden strings, and identifies file magic.
* **Threat Grid Integration:** Automatically queries the **VirusTotal API** (File Hash, IP, & URL) to provide real-time threat intelligence and global detection rates.

### 📡 3. Network Reconnaissance
* **Hunter-Killer Port Scanner:** A multi-threaded engine that maps target infrastructure, identifying open ports and fingerprinting operating systems (OSINT).
* **Live Packet Sniffer:** Deploys an interception probe to capture and analyze real-time network traffic via a dedicated web dashboard.

### 💻 4. System & OS Dominance
* **Command & Control:** Launch development environments (VS Code), execute shell commands (Powershell, CMD), and manage system states.
* **Automated Productivity:** Read PDFs aloud, fetch global tech news, scrape Wikipedia, and automate social media profiling (Instagram).

---

## 🛠️ Technology Stack

* **Core Logic:** Python 3.10+
* **Generative AI:** Google Generative AI (`google-generativeai`)
* **Speech Services:** `speech_recognition`, `pyttsx3`, `edge-tts`, `pydub`
* **Security Modules:** * `pefile` (PE Header Analysis)
    * `python-magic` (File Type Detection)
    * `requests` (API Handling)
    * `scapy` (Packet Sniffing - external module)
* **Automation:** `pyautogui`, `winshell`, `instaloader`

---

## ⚡ Deployment Sequence

### Prerequisites
* Python 3.8 or higher.
* A Windows environment (preferred for OS automation features).
* **FFmpeg** installed and added to system PATH (for audio processing).

### Installation

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/yourusername/project-elliot.git](https://github.com/yourusername/project-elliot.git)
    cd project-elliot
    ```

2.  **Install the Dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
    *Note: You may need to manually install `python-magic-bin` on Windows.*

3.  **Configure API Keys:**
    Open `main.py` and insert your API credentials in the configuration section:
    ```python
    VT_API_KEY = "YOUR_VIRUSTOTAL_KEY"
    GENAI_API_KEY = "YOUR_GEMINI_API_KEY"
    # NewsAPI key inside the news() function
    ```

4.  **Initiate the Protocol:**
    ```bash
    python main.py
    ```

---

## 🗣️ Command Directives

Once ELLIOT is online, use the following voice triggers:

| Domain | Command Trigger | Action |
| :--- | :--- | :--- |
| **Security** | *"Start Port Scanner"* | Initiates multi-threaded network mapping. |
| **Security** | *"Analyse Malware"* | Begins interactive static & dynamic file analysis. |
| **Security** | *"Start Packet Sniffer"* | Launches the traffic interception dashboard. |
| **Security** | *"Analyse IP"* / *"Analyse URL"* | Queries VirusTotal for reputation checks. |
| **AI** | *"Advance Mode"* | Switches to Gemini 1.5 conversational context. |
| **System** | *"Open VS Code"* / *"Open CMD"* | Launches development tools. |
| **System** | *"Take a screenshot"* | Captures current display state. |
| **Utility** | *"Read PDF"* | Reads document text aloud. |

---

## ⚠️ Ethical Directive & Disclaimer

**This tool is a loaded weapon.**

Project ELLIOT is designed for **educational purposes, authorized security research, and defensive analysis only**. 

* Do not use the scanner or sniffer on networks you do not own or have explicit permission to test.
* Do not analyze files that may compromise your host system without a sandbox.
* The developers assume **no liability** for misuse of this technology. 

**With great power comes great responsibility.**

---

<div align="center">
  <sub>Built for the Smart India Hackathon 2025</sub>
</div>
