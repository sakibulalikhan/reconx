# ReconX - Advanced Reconnaissance and Analysis Script

![Author](https://img.shields.io/badge/Author-@sakibulalikhan-blue)
![GitHub last commit](https://img.shields.io/github/last-commit/sakibulalikhan/reconx)
![GitHub](https://img.shields.io/github/license/sakibulalikhan/reconx)

ReconX is a powerful Bash script designed for advanced subdomain reconnaissance. It automates various subdomain discovery and analysis techniques to help you gather information about a target domain, including subdomains, alive domains, potential subdomain takeovers, open ports, JavaScript file scraping, and more.

![image](https://github.com/sakibulalikhan/reconx/assets/75080608/e9473884-5003-4c20-a506-359d02e3cb36)


## Table of Contents

- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- Subdomain discovery using tools like Assetfinder, Amass, and crt.sh.
- Verification of alive domains with HTTP and HTTPS probing.
- Detection of potential subdomain takeover vulnerabilities.
- Scanning for open ports with Naabu.
- Scraping JavaScript files from discovered subdomains using Gau.
- Scraping Mantra API keys or credentials from JavaScript files.
- Gathering wayback data to find hidden parameters and extensions.
- Capturing screenshots of discovered subdomains using Gowitness.

## Requirements

Before using ReconX, make sure you have the following tools installed:

- [assetfinder](https://github.com/tomnomnom/assetfinder)
- [amass](https://github.com/owasp-amass/amass)
- [jq](https://jqlang.github.io/jq/)
- [httprobe](https://github.com/tomnomnom/httprobe)
- [subjack](https://github.com/haccer/subjack)
- [nmap](https://github.com/nmap/nmap)
- [naabu](https://github.com/projectdiscovery/naabu)
- [waybackurls](https://github.com/tomnomnom/waybackurls)
- [gowitness](https://github.com/sensepost/gowitness)
- [mantra](https://github.com/MrEmpy/Mantra)

You can install these tools using package managers or download them manually from their official sources.

## Installation

   ```bash
   git clone https://github.com/sakibulalikhan/reconx.git && cd reconx && sudo mv reconx /usr/bin && sudo chmod +x /usr/bin/reconx
   ```
## Usage
To use ReconX, simply provide the target URL as an argument when running the script:

  ```bash
   reconx target.com
  ```
Replace target.com with the domain you want to perform reconnaissance on. ReconX will create a directory structure for your results and provide detailed information about the target domain.

## Contributing
Contributions are welcome! If you have any suggestions, improvements, or bug fixes, please create an issue or submit a pull request.

## License
This project is licensed under the [MIT License](https://github.com/sakibulalikhan/reconx/blob/main/LICENSE).

#### Follow me on Twitter [@sakibulalikhan](https://twitter.com/sakibulalikhan)

## Support Me:
<a href="https://www.buymeacoffee.com/sakibulalikhan" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: 41px !important;width: 174px !important;box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;-webkit-box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;" ></a>
