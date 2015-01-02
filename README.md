PHPMD-MAGENTO
=============

PHP Mess Detector rules for Magento 1.X code. Ruleset is taken from Magento 2.


How to use
----------

1. Install php_depend and php_pmd from pear
```
sudo pear channel-discover pear.phpmd.org
sudo pear channel-discover pear.pdepend.org
sudo pear install pdepend/php_depend
sudo pear install phpmd/php_pmd-1.5.0
```
2. Clone repository
```
git clone https://github.com/kubaceg/phpmd-magento.git
```
3. Use phpmd
```
phpmd /path/to/code text /path/to/ruleset.xml
```