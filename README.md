# PHP Switch

Change to any version of PHP installed on your machine

## Install

```
$ sudo wget https://raw.githubusercontent.com/00F100/phpswitch/master/phpswitch -O /usr/local/bin/phpswitch
$ sudo chmod +x /usr/local/bin/phpswitch
```

## Usage

### To PHP 7.2
```
$ phpswitch 7.2
Switch PHP version To (7.2):
/usr/bin/php7.2

$ php -v
PHP 7.2.5-0ubuntu0.18.04.1 (cli) (built: May  9 2018 17:21:02) ( NTS )
Copyright (c) 1997-2018 The PHP Group
Zend Engine v3.2.0, Copyright (c) 1998-2018 Zend Technologies
    with Zend OPcache v7.2.5-0ubuntu0.18.04.1, Copyright (c) 1999-2018, by Zend Technologies
```

### To PHP 7.0
```
$ phpswitch 7.0
Switch PHP version To (7.0):
/usr/bin/php7.0

$ php -v
PHP 7.0.30-1+ubuntu18.04.1+deb.sury.org+1 (cli) (built: May  2 2018 12:44:20) ( NTS )
Copyright (c) 1997-2017 The PHP Group
Zend Engine v3.0.0, Copyright (c) 1998-2017 Zend Technologies
    with Zend OPcache v7.0.30-1+ubuntu18.04.1+deb.sury.org+1, Copyright (c) 1999-2017, by Zend Technologies
```

### To PHP 5.6
```
$ phpswitch 5.6
Switch PHP version To (5.6):
/usr/bin/php5.6

$ php -v
PHP 5.6.36-1+ubuntu18.04.1+deb.sury.org+1 (cli) 
Copyright (c) 1997-2016 The PHP Group
Zend Engine v2.6.0, Copyright (c) 1998-2016 Zend Technologies
    with Zend OPcache v7.0.6-dev, Copyright (c) 1999-2016, by Zend Technologies
```

## To install PHP versions on Ubuntu 18...

```
$ sudo add-apt-repository ppa:ondrej/php
$ sudo apt-get update
$ sudo apt-get install php5.6 php7.0 php7.2 -y
```