<H2>This script is still in alpha stage, it will be improved soon.</H2>

# mass
A wrapper script for subdomain enumeration in the amass tool

The OWASP Amass link: <a href="https://github.com/owasp-amass/amass">https://github.com/owasp-amass/amass</a>

# What this script does:

Checks if the target is online (via fping)
Bruteforces subdomains via the 'subdomains-top1million-5000.txt' in Seclists (Change it if needed)
Doesn't rely on public data, but rather interacts with the target

# What will be updated:
The port input() function

# How to use it:
1. Download the script, and do chmod +x
2. Copy it to /sbin (or whatever you like, just make sure it is in $PATH)
3. reopen the terminal

4. # Disclaimer:
5. <h3 style="color:grey;">Only use it for targets you have permission to test, I'm and the amass developers not responsible for any damage or misuse of the tool or the script</h3>
