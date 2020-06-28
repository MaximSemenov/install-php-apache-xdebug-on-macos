# install-php-apache-xdebug-on-macos #

### This Guide was designed to help you set up PHP 7.4 and all that great stuff that comes with it. The Guide should work for other version as well

1. Install **Brew** first

`/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"`

_Brew is a package manager for MacOS. It helps you to save time. It helps you to keep your file structure clean. Having Brew will help you easily install or uninstall fresh packages and keep your MacOs clean and better organized._ 

2. Check where is your **Apache config** located

`httpd -V`

You should see something like this in your Terminal: *SERVER_CONFIG_FILE="/private/etc/apache2/httpd.conf*. When you see it copy the path and open this file in your VS Code by typing

`code -r /private/etc/apache2/httpd.conf `

_You path can be different than mine. Make sure you copied value from SERVER_CONFIG_FILE. I assumed you have VS Code installed if you use other code editor for example PHPStrom then open that Apache config file with it._ 



