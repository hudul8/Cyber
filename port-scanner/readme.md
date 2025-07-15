# 🔎 Port Scanner (Python)

This is a simple and fast **TCP port scanner** written in Python. It scans a target IP address for open ports within a specified range and displays the results in the terminal. It supports multithreading for high-speed scanning and requires **no external libraries**.

---

## 📌 Features

- ✅ Scan any target IP for open TCP ports
- ✅ Customizable port range
- ✅ Multithreaded scanning (fast!)
- ✅ Command-line interface (CLI)
- ✅ Built with Python standard libraries only

---

## ⚙️ Installation

1. **Clone the repository:**

bash
git clone https://github.com/hudul8/port-scanner.git
cd port-scanner

Run the script with Python 3:

python3 scanner.py --ip 127.0.0.1

No third-party libraries are required (uses only socket, argparse, and threading).
🧾 Parameters

Argument	Description	Required?	Default

--ip	Target IP address	✅	-

--start-port	Starting port number	❌	1

--end-port	Ending port number	❌	1024

--threads	Number of threads to use	❌	100

--timeout	Timeout per port in seconds	❌	1.0


💻 Usage Examples

Basic scan (default range):

python3 scanner.py --ip 192.168.1.1

Scan with custom port range and thread count:

python3 scanner.py --ip 192.168.1.1 --start-port 20 --end-port 1000 --threads 200

Scan with shorter timeout:


python3 scanner.py --ip 10.0.0.5 --timeout 0.5

📤 Sample Output

[+] Open port found: 22 (SSH)

[+] Open port found: 80 (HTTP)

[+] Open port found: 443 (HTTPS)

✅ Scan completed. Total open ports: 3


⚠️ Legal Disclaimer

⚠️ IMPORTANT: This tool is intended for educational and authorized testing purposes only.


Unauthorized scanning of systems you do not own or have explicit permission to test is illegal in many jurisdictions.

By using this tool, you take full responsibility for your actions. The developer is not liable for any misuse.

Stay ethical. Stay legal. 🛡️

📌 Roadmap / To Do

 UDP scanning support

 Banner grabbing

 JSON / TXT report output

 IP range scanning (multiple hosts)

👨‍💻 Author

GitHub: https://github.com/hudul8

Email: hudul8@tuta.io

