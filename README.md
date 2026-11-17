# AI-Intrusion-Detection-System

## Advanced AI-Based Intrusion Detection and Cybersecurity Monitoring System

### Project Overview
AI-Intrusion-Detection-System is a Python-based cybersecurity project designed to identify suspicious activities and potential security threats using intrusion detection techniques.

The system analyzes authentication logs, detects repeated failed login attempts, identifies suspicious login behavior, checks indicators of compromise (IOC), and monitors file integrity using SHA-256 hashing.

### Key Features
- AI-oriented intrusion detection framework
- Brute-force login attempt detection
- Suspicious login activity identification
- Indicator of Compromise (IOC) checking
- File Integrity Monitoring using SHA-256
- Security alert generation
- JSON and CSV report generation
- Command-line interface

### Technologies Used
- Python 3.10+
- Artificial Intelligence concepts
- Cybersecurity techniques
- SHA-256 hashing
- JSON and CSV
- Git and GitHub

### Installation

```bash
git clone https://github.com/your-username/AI-Intrusion-Detection-System.git
cd AI-Intrusion-Detection-System
```

### Run the Project

```bash
python main.py --help
```

Analyze authentication logs:

```bash
python main.py analyze data/sample_logs/auth.log
```

Create a file integrity baseline:

```bash
python main.py baseline data/sample_files
```

Verify file integrity:

```bash
python main.py verify data/sample_files
```

Check indicators of compromise:

```bash
python main.py ioc data/sample_logs/auth.log --indicators config/iocs.json
```

### Testing

```bash
python -m unittest discover -s tests -v
```

### Future Enhancements
- Machine-learning-based intrusion detection
- Real-time network traffic monitoring
- AI-based anomaly detection
- Web-based security dashboard
- Email alerts for critical threats
- Integration with threat intelligence services

### Project Domain
Cybersecurity | Artificial Intelligence | Intrusion Detection

### Responsible Use
This project is intended for educational and authorized defensive cybersecurity purposes only.

---

**AI-Intrusion-Detection-System – Detect. Analyze. Defend.**
