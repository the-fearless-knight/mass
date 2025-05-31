<H2>This script is still in alpha stage, it will be improved soon.</H2>

# Mass
A wrapper script for the amass tool to enumerate subdomains

The OWASP Amass link: <a href="https://github.com/owasp-amass/amass">https://github.com/owasp-amass/amass</a>

# What this script does:

* Checks if the target is online (via fping)
* Bruteforces subdomains via the 'subdomains-top1million-5000.txt' in Seclists (Change it if needed)
* Interacts directly with the target, instead of relying on public data

# What will you need:
* python3, fping and amass (since this is just a wrapper, not a full program)

# What will be updated:
The port input() function

# How to use it:
1. Download the script, rename it to 'mass' and do chmod +x
2. Copy it to /sbin (or whatever you like, just make sure it is in $PATH)
3. Reopen the terminal
4. Type mass, then enter the domain and the ports (be sure not to put spaces between ports!)

# Disclaimer:
  <h3 style="color:grey;">Only use it for targets you have permission to test, I'm not responsible for any damage or misuse of the tool or the script.</h3>
