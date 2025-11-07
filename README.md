# VST-Cascade-Cipher-System
Vigenère + Substitution + Columnar Transposition

VST Cascade Cipher 🔐
Multi-Stage Classical Encryption System

A professional cryptographic system combining three classical encryption techniques in a cascading architecture for enhanced security.

🚀 Features
Triple-Layer Encryption: Vigenère + Substitution + Columnar Transposition

Web Dashboard: Gradio-based professional interface

Security Analysis: Built-in cryptanalysis tools

Performance Benchmarks: Comparative timing analysis

Step-by-Step Visualization: Real-time process tracking

🛠️ Quick Start
bash
# Install dependencies
pip install gradio plotly pandas

# Run the system
python cipher_system.py
🔐 How It Works
Encryption Flow:
text
Plain Text 
→ Vigenère Cipher (Key-based shifting)
→ Substitution Cipher (Alphabet mapping)  
→ Columnar Transposition (Position shuffling)
→ Final Ciphertext
Security Enhancement:
Vigenère: Breaks frequency patterns

Substitution: Hides character relationships

Transposition: Destroys word structures

Combined: Layered defense against cryptanalysis

📱 Interface Modules
🔒 Encryption: Step-by-step encryption process

🔓 Decryption: Reverse process with stage tracking

🔍 Security Analysis: Frequency analysis & attack simulation

⚡ Performance: Benchmarking vs simple ciphers

🎯 Usage Example
python
# Basic usage
cipher = CustomCipher()
encrypted, stages = cipher.encrypt("HELLO WORLD", "SECRETKEY123456789")
decrypted, _ = cipher.decrypt(encrypted, "SECRETKEY123456789")
⚠️ Requirements
Python 3.8+

Key: Minimum 10 characters

Dependencies: gradio, plotly, pandas

📊 Performance
Cipher Type	Speed	Security
VST Cipher	8x slower	🔒🔒🔒🔒
Shift Cipher	Faster	🔒
📜 License
MIT License - For educational and research purposes.

Single File Implementation - Complete system in cipher_system.py

"Three layers of classical cryptography for modern security"


