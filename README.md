# magento-export-products
This magento product export based on Aten Software Product Data Exporter for Magento.

How to use:

1. Open centralfeed.php and around line 91 add your password to const PASSWORD, and around line 94 add your company name to const CENTRALFEED_NAME 

2. Upload centralfeed.php file to your web server under public html folder (or any sub folder you want in it).

3. Load centralfeed.php file in your browser, for example http://www.mystore.com/centralfeed.php 
or by url http://www.mystore.com/centralfeed.php.php?Command=Export&Store=1&Password=ABCDEFG
