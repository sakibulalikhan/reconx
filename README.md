# ReconX - Advanced Reconnaissance and Analysis Script

![Author](https://img.shields.io/badge/Author-@sakibulalikhan-blue)
![GitHub last commit](https://img.shields.io/github/last-commit/sakibulalikhan/reconx)
![GitHub](https://img.shields.io/github/license/sakibulalikhan/reconx)

ReconX is a powerful Bash script designed for advanced subdomain reconnaissance. It automates various subdomain discovery and analysis techniques to help you gather information about a target domain, including subdomains, alive domains, potential subdomain takeovers, open ports, JavaScript file scraping, Finding parameters, Taking automatic screenshots of the alive hosts, and more.

![image](https://github.com/sakibulalikhan/reconx/assets/75080608/3841c55e-984c-4021-a879-8f97a3539a4f)




## Table of Contents

- ### [Features](#features)
- ### [Requirements](#requirements)
- ### [Installation](#installation)
- ### [Usage](#usage)
- ### [Contributing](#contributing)
- ### [License](#license)

## Features

- Subdomain discovery using tools like Assetfinder, Amass, and crt.sh.
- Verification of alive domains with HTTP and HTTPS probing.
- Detection of potential subdomain takeover vulnerabilities.
- Scanning for open ports with Naabu.
- Scraping JavaScript files from discovered subdomains using Gau.
- Scraping API keys or credentials from JavaScript files.
- Gathering Wayback data to find hidden parameters and extensions.
- Capturing screenshots of discovered subdomains using Gowitness.
- Detecting technologies used on discovered subdomains.
- Fingerprinting The Web Application Firewall on discovered subdomains.

## Requirements

Before using ReconX, make sure you have the following tools installed:

|                                                             |                                                             |                                                             |
| ----------------------------------------------------------- | ----------------------------------------------------------- | ----------------------------------------------------------- |
| [assetfinder](https://github.com/tomnomnom/assetfinder)     | [nmap](https://github.com/nmap/nmap)                        | [subjack](https://github.com/haccer/subjack)                |
| [amass](https://github.com/owasp-amass/amass)               | [naabu](https://github.com/projectdiscovery/naabu)          | [waybackurls](https://github.com/tomnomnom/waybackurls)     |
| [jq](https://jqlang.github.io/jq/)                          | [gowitness](https://github.com/sensepost/gowitness)         | [httprobe](https://github.com/tomnomnom/httprobe)           | 
| [wafw00f](https://github.com/EnableSecurity/wafw00f)        | [whatweb](https://github.com/urbanadventurer/WhatWeb)       | [mantra](https://github.com/MrEmpy/Mantra)                  |
| [subfinder](https://github.com/projectdiscovery/subfinder)  |

You can install these tools using package managers or download them manually from their official sources.

## Installation

   ```bash
   wget clone https://raw.githubusercontent.com/sakibulalikhan/reconx/main/reconx && sudo mv reconx /usr/bin/ && sudo chmod +x /usr/bin/reconx && reconx
   ```

## Options:

  ```bash
  -t, --target <domain>    Scan a single domain
  -l, --list <file>        Scan a list of domains from a file
  -h, --help               Display this help message
  ```
## Usage
To use ReconX, just follow the below steps to run the script:

* For single domain
```bash
reconx -t terget.com
```
* For multiple or list of domains
```bash
reconx -l domainlists.txt
```
* Stuck? Want to know the script options?
```bash
reconx -h
```

Replace __target.com__ or __domainlists.txt__ with the domain or domain lists you want to perform reconnaissance on. ReconX will create a directory structure for your results and provide detailed information about the target domain.

## Contributing
Contributions are welcome! If you have any suggestions, improvements, or bug fixes, please create an issue or submit a pull request.

## License
This project is licensed under the [MIT License](https://github.com/sakibulalikhan/reconx/blob/main/LICENSE).

#### Follow me on Twitter [@sakibulalikhan](https://twitter.com/sakibulalikhan)

## Support Me:
<a href="https://www.buymeacoffee.com/sakibulalikhan" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: 41px !important;width: 174px !important;box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;-webkit-box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;" ></a>


[def]: #license
