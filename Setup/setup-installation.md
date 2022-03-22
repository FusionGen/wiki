---
sidebar_position: 1
---

# Installation

## Minimum system requirements

FusionGen has some server requirements for web hosting:

1. PHP version 8.0 or higher
1. cURL PHP Extension
1. MySQLi PHP Extension
1. OpenSSL PHP Extension
1. Mbstring PHP Extension
1. ZipArchive PHP Extension
1. GD PHP Extension
1. SOAP PHP Extension
1. JSON PHP Extension
1. GMP PHP Extension

Some OS distributions may require you to manually install some of the required PHP extensions.

When using Debian/Ubuntu, the following command can be run to install all required extensions:

```bash
sudo apt-get update &&
sudo apt-get install php php-soap php-curl php-xml php-gmp php-gd php-json php-mbstring php-mysql php-mysqli php-zip
```