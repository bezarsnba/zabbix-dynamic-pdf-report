zabbix-dynamic-pdf-report
=========================

This originates from https://github.com/spy86/Zabbix_/zabbix-dynamic-pdf-report
and the goal of this fork is to create a standalone git repository
together with some installation instructions.

Also to make sure it works 100% with Zabbix 3.0 (LTS)
# Goals

* [ ] Make it work with 3.0 (LTS) - possibly
* [ ] Make it work with 3.4 - likely
* [ ] Make it work with 4.0 (LTS) - yes, please

Installation
------------
```
#copy sample to real config
cp config.inc.sample.php config.inc.php

#edit to match your environment
nano config.inc.php

```
 You might need to change timezone in `/var/www/html/zabbix-dynamic-pdf-report/createpdf.php`


develop
-------

* clone `https://github.com/kmpm/zabbix-dynamic-pdf-report`
* Install PHP `sudo apt-get install php7.0 php7.0-cli`
