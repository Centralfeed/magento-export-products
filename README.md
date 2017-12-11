# magento-export-products
This magento product export based on Aten Software Product Data Exporter for Magento.

How to use:

1. Open centralfeed.php and around line 99 add your password to const PASSWORD, and around line 102 add your company name to const CENTRALFEED_NAME 

2. Upload centralfeed.php file to your web server under public html folder (or any sub folder you want in it).

3. Load centralfeed.php file in your browser, for example http://www.mystore.com/centralfeed.php 
or by url http://www.mystore.com/centralfeed.php.php?Command=Export&Store=1&Password=ABCDEFG

4. To export only the stock from catalog you can send the "StockExport" value under the Command parameter, for example
http://www.mystore.com/centralfeed.php.php?Command=StockExport&Store=1&Password=ABCDEFG
