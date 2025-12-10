📘 IoT Security Lab – Data Encryption & Security Lifecycle Simulation
This repository contains two Python simulations developed for Lab Assignment No. 05 – IoT & Cyber-Physical Systems Security.
The project demonstrates secure IoT communication using symmetric encryption and simulates a complete IoT device security lifecycle.
________________________________________
🚀 Project Features
✅ 1. IoT Security Lifecycle Simulation
A full simulation of the 5 stages of an IoT/embedded system security lifecycle:
1.	Threat Modeling
2.	Secure Boot Verification
3.	Secure Key Injection
4.	OTA Firmware Update Check
5.	Secure Decommissioning
Each stage logs detailed status messages with timestamps.
________________________________________
✅ 2. IoT Device Data Encryption & Secure Transmission
A simulated IoT sensor generates temperature and humidity readings, encrypts them, and sends them to a simulated server.
Key Features:
•	Random sensor data generation
•	PBKDF2-HMAC-SHA256 for secure key derivation
•	Symmetric encryption using Fernet (AES-128 + HMAC)
•	Secure decryption and integrity validation on the server
________________________________________
🛠️ Technologies Used
•	Python 3.x
•	cryptography library
•	Fernet symmetric encryption
•	PBKDF2 for key derivation
•	Timestamps & event logging
📸 Example Output
🔐 Encryption & Transmission Simulation
•	Original plaintext sensor data
•	Encrypted ciphertext (Fernet token)
•	Successful decryption on the receiver
🔄 Security Lifecycle Simulation
•	Timestamped logs for each lifecycle stage
•	Valid secure boot verification
•	OTA update check results
•	Key wiping and device decommissioning
________________________________________
🔐 Security Concepts Demonstrated
•	IoT lifecycle security
•	Secure boot integrity checking
•	Key management & secure key injection
•	Lightweight symmetric encryption
•	OTA update verification
•	Confidentiality & integrity in IoT communication
________________________________________
👨🎓 Author Information
Student Name: Fraj Ameen Bin Abdat
Enrollment Number: 22202041030
Course: Special Topics in Information Security
Instructor: Prof. Ahmed Abuamer

