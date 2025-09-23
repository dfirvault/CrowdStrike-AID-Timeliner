# FalconAID - CrowdStrike Device Investigator

A secure tool for quickly looking up CrowdStrike Agent IDs (AIDs) from hostnames and generating direct investigation links.

## Features

- 🔒 **Secure credential storage** using system keyring
- 🚀 **Quick AID lookup** from hostnames  
- 🔗 **Direct investigation URL** generation
- 💻 **System-specific encryption** based on hardware identity
- ⚡ **Standalone executable** available (no Python required)

## Quick Start

### Download
- **Windows**: `CrowdStrikeAIDTimeliner.exe`

### First Run Setup
1. Run the executable
2. Enter your CrowdStrike API credentials:
   - Client ID
   - Client Secret  
   - Base URL (e.g., `https://api.crowdstrike.com`)
3. Credentials are encrypted and stored securely in your system keyring

### Usage
```bash
./CrowdStrikeAIDTimeliner.exe
Enter hostname: DESKTOP-ABC123
Enter lookback days: 30
````

### The tool will:

- Look up the AID for the hostname
- Generate a direct investigation URL
- Optionally open it in your browser

####API Requirements
- CrowdStrike Falcon API credentials with Device Read permissions
- Base URL for your region (US, EU, US-GOV-1)

###Security
- Credentials encrypted using system-specific keys
- Optional additional passphrase protection
- No credentials stored in plaintext

Support
Developer: Jacob Wilson
Email: dfirvault@gmail.com

License
See LICENSE file for details.

