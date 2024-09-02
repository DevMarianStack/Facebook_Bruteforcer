# Facebook Brute-Forcer

Welcome to the Facebook Brute-Forcer tool! This script is designed for educational purposes only. Learn how to understand security vulnerabilities and improve your knowledge of cybersecurity.

## Features

- **Brute-Force Attacks**: Attempt to gain access to Facebook accounts using a list of passwords or a single password.
- **Proxy Support**: Use HTTP/S proxies to anonymize your requests.
- **Profile ID Extraction**: Retrieve a user's Facebook profile ID from a profile URL.
- **Update Check**: Automatically update the script to the latest version.

## Requirements

- Python 3.x
- `requests` library
- `mechanize` library

You can install the required libraries using:
```bash
pip install requests mechanize

Usage

To use this script, run the following command:

python facebook_bruteforcer.py [OPTIONS...]

Options

	•	-t <target email/ID>: Specify the target’s email or Facebook ID.
	•	-w <wordlist path>: Path to the wordlist file for brute-forcing.
	•	-s <single password>: Specify a single password to test.
	•	-p <proxy IP:PORT>: Optional HTTP/S proxy.
	•	-g <profile URL>: Get the target’s Facebook profile ID from the profile URL.
	•	-u or --update: Update the script to the latest version.

Examples

python facebook_bruteforcer.py -t victim@example.com -w /path/to/wordlist.txt
python facebook_bruteforcer.py -t 100001234567890 -w /path/to/wordlist.txt
python facebook_bruteforcer.py -t victim@example.com -s Password123
python facebook_bruteforcer.py -g https://www.facebook.com/victimprofile

Important Note 🚨

This tool is intended for educational purposes only. Misuse of this tool for unauthorized access to accounts is illegal and unethical. Always have permission before testing the security of any system.

License

This tool is provided under the MIT License.

Contact

For any questions or support, please reach out to marianfsdev@gmail.com.

Happy Learning! 😊🔐

Dont skid and give credits
