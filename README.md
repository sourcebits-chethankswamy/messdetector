messdetector
============

PHP Mess Detector tool checks the PHP source code base and look for several potential problems within that source. These problems can be things like:  Possible bugs Suboptimal code Overcomplicated expressions Unused parameters, methods, properties

Requirements
============

1. PEAR package
2. phpmd/PHP_PMD requires PHP version 5.1.2 or greater.

Installation
============

1. Install PHP using XAMPP or MAMP etc
2. Install PEAR package using "php go-pear.phar" from terminal or command prompt (for more help check http://pear.php.net/manual/en/installation.getting.php on how to install).
3. Install phpmd/PHP_PMD using "pear install --alldeps phpmd/PHP_PMD" from terminal or command prompt (for more help check http://phpmd.org/download/index.html on how to install).
4. Download the messdetector tool source code from git (https://github.com/sourcebits-chethankswamy/messdetector) and place it in your htdocs.

How to use
==========

1. Open the website in your browser (ex: http://localhost/messdetector).
2. Select the file (php) which you want to check.
3. Click on submit.
4. The output will be the list of standards you need to change in you page. You can also download the complete report by clicking on the download link.