# TurnKey Linux PHP Upgrade Script

## Overview
This enhanced script is tailor-made for upgrading PHP versions on servers running TurnKey Linux. It is a critical tool for maintaining and updating PHP versions on these servers, ensuring both compatibility and security. The script now includes support for various web servers, anticipating the transition to PHP-FPM. The original script, developed by JedMeister, has been significantly modified and improved by Marcos Méndez from PopSolutions.

## Features
- Interactive selection of the new PHP version to install.
- Automatically detects and upgrades the PHP version, retaining existing modules.
- Handles configuration updates for multiple web servers, including Apache, Nginx, and Lighttpd.
- Prepares for the transition to PHP-FPM.
- Checks for compatibility of PHP modules with the selected new version.

## Supported TurnKey Linux Applications
This script is compatible with a range of TurnKey Linux applications that use PHP, such as:
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
- NextCloud
- And others that rely on PHP

## Usage
1. Download or copy the script to your TurnKey Linux server.
2. Make the script executable: `chmod +x upgrade_php.sh`.
3. Run the script as root or using `sudo`: `./upgrade_php.sh`.
4. Follow the interactive prompts to select the desired PHP version.

**Note:** It's highly recommended to back up your server before running the script.

## Web Server Compatibility
- The script automatically detects and configures the PHP module for Apache.
- For servers using Nginx or Lighttpd, the script restarts PHP-FPM with the new PHP version.
- Ensure the correct configuration of your web server to work with the new PHP version post-upgrade.

## Contributing
Contributions to this script are welcomed to enhance its functionality, improve compatibility, or address any issues. If you'd like to contribute, please fork the repository, make your changes, and submit a pull request.

## Authors
- **Marcos Méndez / PopSolutions** - *Enhancement and Adaptation*
- **JedMeister** - *Original Concept and Work* - [JedMeister on GitHub](https://github.com/JedMeister)

## Acknowledgments
Special thanks to JedMeister for his foundational work, which has been invaluable to the TurnKey Linux community. This script builds upon his original concept to offer broader compatibility and forward-looking features.

---

This script is provided "as is", without warranty of any kind. Use at your own risk.
