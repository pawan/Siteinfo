Copy folder at app/code

Run:

php bin/magento setup:upgrade

php bin/magento cache:flush

You can call it like:

{{block class="Vendor\Siteinfo\Block\Siteinfo" name="site-info" as="site-info" template="Vendor_Siteinfo::storename.phtml" }}