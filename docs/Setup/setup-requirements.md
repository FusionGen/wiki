---
sidebar_position: 1
---

# Requirements

## Apache Modules

- [mod_headers](https://httpd.apache.org/docs/2.4/mod/mod_headers.html)
- [mod_rewrite](https://httpd.apache.org/docs/2.4/mod/mod_rewrite.html)
- [mod_expires](https://httpd.apache.org/docs/2.4/mod/mod_expires.html)

FusionGen has some server requirements for web hosting:

## PHP

#### PHP version 8.0 or higher
- [curl](https://www.php.net/manual/en/book.curl.php)
- [gd](https://www.php.net/manual/en/book.image.php)
- [mbstring](https://www.php.net/manual/en/mbstring.installation.php)
- [mysqli](https://www.php.net/manual/en/book.mysqli.php)
- [openssl](https://www.php.net/manual/en/book.openssl.php)
- [soap](https://www.php.net/manual/en/class.soapclient.php)
- [gmp](https://www.php.net/manual/en/book.gmp.php)
- [json](https://www.php.net/manual/en/book.json.php)
- [zip](https://www.php.net/manual/en/intro.zip.php)

Some OS distributions may require you to manually install some of the required PHP extensions.

When using Debian/Ubuntu, the following command can be run to install all required extensions:

```bash
sudo apt-get update &&
sudo apt-get install php php-soap php-curl php-xml php-gmp php-gd php-json php-mbstring php-mysql php-mysqli php-zip
```