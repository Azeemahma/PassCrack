PassCrack

A lightweight yet powerful password cracking and auditing tool designed for security researchers, penetration testers, and ethical hackers.

This project demonstrates how weak or common passwords can be identified using brute force and dictionary-based approaches, highlighting the importance of strong password policies.

🚀 Features

🔑 Supports multiple hash algorithms (MD5, SHA1, SHA256, SHA512)

📂 Dictionary-based and brute force attack modes

⚡ Optimized for fast cracking attempts

🛠️ Easy to extend with custom wordlists and hash types

📊 Generates simple reports for cracked passwords

📦 Installation

# Clone the repository
git clone https://github.com/your-username/PassCrack-fast.git
cd PassCrack-fast

# Install dependencies
pip install -r requirements.txt

🖥️ Usage

# Run dictionary attack
python passcrack.py --hash <hash_value> --wordlist wordlist.txt

# Run brute force attack
python passcrack.py --hash <hash_value> --mode brute --length 6


🔍 Example

python passcrack.py --hash 5f4dcc3b5aa765d61d8327deb882cf99 --wordlist wordlist.txt


🎯 Applications

Password strength auditing

Security awareness training

Demonstrating the risk of weak passwords in real-world systems

⚠️ Disclaimer

This project is for educational and ethical purposes only.
Do not use this tool against systems without proper authorization.