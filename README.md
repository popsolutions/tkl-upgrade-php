# TurnKey Linux PHP Upgrade Script

## Overview
This script is specifically designed for upgrading PHP versions on servers running TurnKey Linux. It's an essential tool for maintaining and updating PHP versions on these servers, ensuring compatibility and security. The script is based on the work of JedMeister, with modifications and enhancements by Marcos Méndez from PopSolutions.

## Features
- Interactive selection of the new PHP version to install.
- Automatically detects and upgrades the PHP version while retaining existing modules.
- Handles Apache web server configuration updates.
- Checks for compatibility of PHP modules with the new version.

## Supported TurnKey Linux Applications
This script can be used with various TurnKey Linux applications that rely on PHP, including but not limited to:
- WordPress
- Joomla
- Drupal
- LAMP Stack
- LAPP Stack
- Magento
- PrestaShop
- SilverStripe
- PHPList
- OrangeHRM
- MediaWiki
- Moodle
- Zurmo
- SugarCRM
- ProcessWire
- SuiteCRM

## Usage
1. Download or copy the script to your TurnKey Linux server.
2. Make the script executable: `chmod +x upgrade_php.sh`.
3. Run the script as root or using `sudo`: `sudo ./upgrade_php.sh`.
4. Follow the interactive prompts to select the desired PHP version.

**Note:** It's highly recommended to back up your server before running the script.

## Contributing
We welcome contributions to this script to enhance its functionality, improve compatibility, or address any issues. If you'd like to contribute, please feel free to fork the repository, make your changes, and submit a pull request.

## Authors
- **Marcos Méndez / PopSolutions** - *Adaptation and Enhancement*
- **JedMeister** - *Original Work* - [JedMeister on GitHub](https://github.com/JedMeister)

## Acknowledgments
Special thanks to JedMeister for the foundational work upon which this script is built. His contributions to the TurnKey Linux community have been invaluable.

---

This script is provided "as is", without warranty of any kind. Use at your own risk.
