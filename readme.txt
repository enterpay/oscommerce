Installation instructions for Enterpay Lasku Yritykselle payment module


1. Unpack the zip file
2. Copy files to their respective directories in the web shop
* catalog/includes/modules/payment/enterpay.php   (payment module code)
* catalog/includes/languages/english/modules/payment/enterpay.php    (language file)

3. In the osCommerce admin, navigate to Modules / Payment

4. Click Install module

5. Select Enterpay Invoice to a company from the list of available modules.

6. Click Install Module

7. Click Edit

8. Enter the values for Merchant Identifier, Secret, Version, Key Version provided by Enterpay. Select Production in the environment section for live system. Ensure that debugging has value '0' for live system.

9. Optionally, you can set the sort order of display.

10. Optionally, you can set the reference number head, which you can use to identify which payments in the bank stamenent are from Enterpay.

11. Test the payment system before live use.

To see a video of the installation go to: http://youtu.be/kEmUDekmv_8


Other instructions

Reference number for the order can be found at the order comments.

At times payment is manually checked by Lasku Yritykselle. In that case the order will remain in pending state and a note of the check is added to order comments.
