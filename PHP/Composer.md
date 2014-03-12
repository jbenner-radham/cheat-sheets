# Composer - A Dependancy Manager for PHP

### Installation

#### Linux/Unix
```shell
curl -sS https://getcomposer.org/installer | php
mv composer.phar /usr/local/bin/composer
```
#### OS X Via Homebrew
```shell
brew tap josegonzalez/homebrew-php
brew install josegonzalez/php/composer
```

#### Windows
Download the installer from https://getcomposer.org/Composer-Setup.exe

### Global Packages

#### Install
```shell
composer global require <vendor>/<package>:<branch>
```

#### Update
```shell
composer global update
```

#### Self-Update (Update Composer Itself)
```shell
composer self-update
```
