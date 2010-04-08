# PHP_CodeSniffer standard for the Symfony framework

The phpcs-symfony project builds a PHP_CodeSniffer standard for the symfony
framework and projects built using the symony framework.

## Installation

If you want to install the standard you have to copy the _PHP_ folder into the
folder where PHP_CodeSniffer is installed. Usually this is _/usr/share/php/_ if
PHP_Codesniffer is installed via PEAR.

## Usage

After installing the standard you are able to use it with the _phpcs_ standard:

    phpcs --standard=Symfony <files>
