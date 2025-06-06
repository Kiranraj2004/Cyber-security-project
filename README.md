

## 🔍 Basic Port Scanner

A simple Python-based port scanner that checks for open TCP ports on a given IP address or domain. This project is built for learning purposes and demonstrates basic socket programming and network scanning concepts.

---

## 📌 Project Description

This tool takes a domain name or IP address as input and scans a range of TCP ports (by default 1 to 1024). It attempts to connect to each port using Python's socket module and prints out which ports are open.

✅ Educational purposes only
⚠️ Do not use against unauthorized targets

---

## 🚀 Features

* Scans ports in the range 1–1024
* Identifies open ports on a target host
* Uses socket programming with timeout handling
* Optional threading support for faster scans (planned as enhancement)

---

## 🛠️ Tech Stack

* Language: Python 3.x
* Modules Used:

  * socket (built-in)
  * time (optional, for measuring speed)
  * threading (optional, for concurrency)

---

## 📦 How to Use

1. Clone the repository or copy the script.
2. Run the script using Python:

   ```bash
   python port_scanner.py
   ```
3. Enter a valid IP address or domain name when prompted (e.g., scanme.nmap.org).
4. View the list of open ports.

---

## 🧪 Sample Output

```
Enter IP address or domain to scan: scanme.nmap.org
Scanning target: scanme.nmap.org
Port 22 is OPEN
Port 80 is OPEN
...
```


---

## 🧠 What You Learn

* Basics of TCP/IP and ports
* Socket programming in Python
* Network communication timeouts and error handling
* Ethical scanning and responsible cybersecurity practices

---


## ✅ Conclusion

This Basic Port Scanner project is a practical introduction to networking and cybersecurity using Python. It demonstrates how TCP port scanning works at a low level using socket programming and teaches important concepts like IP addressing, port numbers, and connection handling.

By building this tool, you gain hands-on experience in:

* Writing efficient Python code for network communication
* Understanding the structure of the internet and common service ports
* Practicing safe and ethical scanning methods

This project lays the foundation for more advanced tools like multi-threaded scanners, banner grabbers, or even custom vulnerability scanners. It is a great starting point for anyone interested in ethical hacking, cybersecurity, or network administration.

