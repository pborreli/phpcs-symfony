# PHP_CodeSniffer standard for the Symfony framework

The phpcs-symfony project builds a PHP_CodeSniffer standard for the symfony
framework and projects built using the symony framework.

## Pre-requisites

Obviously, PHP_CodeSniffer has to be installed.

    sudo pear install PHP_CodeSniffer-1.3.0RC1

## Installation

If you want to install the standard you have to symlink this project root folder into the Standard folder where PHP_CodeSniffer is installed. Usually this is _/usr/share/php/PHP/CodeSniffer/Standard_ if
PHP_Codesniffer is installed via PEAR.

    sudo ln -s /folder/ayoub/git/form-sandbox/phpcs-symfony/ /usr/share/php/PHP/CodeSniffer/Standards/Symfony

## Usage

After installing the standard you are able to use it with the _phpcs_ standard, you can now go in Symfony root folder and execute :

    phpcs --standard=Symfony src/
