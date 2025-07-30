<h3>This script is still in alpha stage, it will be improved soon.</h3>

## Mass
<h4>A wrapper script for the amass tool to enumerate subdomains.</h4>


The OWASP Amass link: <a href="https://github.com/owasp-amass/amass">https://github.com/owasp-amass/amass</a>

## What this script does:

* Checks if the target is online (via fping)
* Bruteforces subdomains using 'subdomains-top1million-5000.txt' in Seclists (Change it if needed)
* Interacts directly with the target (like directory enumeration), instead of relying on public data

## Drawbacks
It can't be used for internal/private targets

## What will you need:
* python3, fping and amass (since this is just a wrapper, not a full program)

## What will be updated:
The port input() function



## How to use it (ignore 1-3 if already installed):
1. Download the script, rename it to 'mass' and make it executeable (chmod +x)
2. Copy it to /usr/local/bin (or whatever you like, just make sure it is in $PATH, 'echo $PATH' to see, if not type 'export PATH=$PATH:/usr/local/bin')
3. Reopen the terminal (or 'source ~/.bashrc' for bash and 'source ~/.zshrc' for zsh)
4. Type mass, then enter the domain and the ports (be sure not to put spaces but ',' between ports!)


## One-liner install (Assuming no other files hold this name in ~/.local/bin) :
```
cd ~/.local/bin && curl https://raw.githubusercontent.com/the-fearless-knight/mass/main/mass.py -o mass && chmod +x mass && if [ "$SHELL" = "/usr/bin/zsh" ]; then echo "export PATH=~/.local/bin:$PATH" >> ~/.zshrc && source ~/.zshrc; elif [ "$SHELL" = "/usr/bin/bash" ]; then echo "export PATH=~/.local/bin:$PATH" >> ~/.bashrc && source ~/.bashrc; fi && cd && clear && echo "Now you can run 'mass'."
```


# Disclaimer:
### Only use it for targets you have permission to test, I'm not responsible for any damage or misuse of the tool or the script.
