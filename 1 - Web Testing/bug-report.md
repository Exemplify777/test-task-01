### Web testing
#
# Details


|**Application**|Sweet Shop|
| :- | :- |
|**URL**|<https://sweetshop.netlify.app/>|
|**Testing** **Approach**|<p>Reactive approach where application</p><p>already developed, blackbox end to end</p><p>functional testing</p>|


# Bug Report
## Bug 1


|**Bug**|1|
| :- | :- |
|**Submit Date**|09-02-2023|
|**Summary**|Application allows login with not existent email and password|
|**Severity**|critical|
|**Product**|Sweet Shop|
|**Component**|Not applicable|
|**Version**|Unknown|
|**Platform**|PC|
|**OS**|Windows 11|
|**Browser**|Chrome|
|**URL**|<https://sweetshop.netlify.app/sweets.html>|
|**Environment**|UAT|
|**Description**|<p>Open the main page by the link[](https://sweetshop.netlify.app/sweets.html)</p><p><https://sweetshop.netlify.app/sweets.html></p><p>1. Click ‘Login’ link</p><p>2. Enter to ‘Email address’ field ‘notexisting@email.com’ value</p><p>3. Enter to ‘Password’ field ‘anypassword’ value</p><p>4. Press ‘Login’ button</p><p></p>|
|**Actual**|It authenticates and opens the user’s page after login|
|**Expected**|It should not allow authenticating users with non existence credentials and should display sufficient error message.|

## Bug 2

|**Bug**|2|
| :- | :- |
|**Submit Date**|09-02-2023|
|**Summary**|Wrong total price calculated in the basket|
|**Severity**|high|
|**Product**|Sweet Shop|
|**Component**|Not applicable|
|**Version**|Unknown|
|**Platform**|PC|
|**OS**|Windows 11|
|**Browser**|Chrome|
|**URL**|<https://sweetshop.netlify.app/sweets.html>|
|**Environment**|UAT|
|**Description**|<p>Open the main page by the link</p><p>[ ](https://sweetshop.netlify.app/sweets.html)<https://sweetshop.netlify.app/sweets.html></p><p>1. Click "Add to basket" for the item "Chocolate cups" with a price of</p><p>£1.</p><p>2. Click on "Basket" on the top right panel.</p><p>3. Click on “Standard Shipping” from the “Delivery” section.</p><p></p>|
|**Actual**|<p>It calculates the wrong total sum in ‘Total (GBP)’ field and</p><p>show £11.99.</p><p></p><p></p><p></p>|
|**Expected**|The 'Total (GBP)' field should show £2.99.|

## Bug 3

|**Bug**|3|
| :- | :- |
|**Submit Date**|09-02-2023|
|**Summary**||
|**Severity**|high|
|**Product**|Sweet Shop|
|**Component**|Not applicable|
|**Version**|Unknown|
|**Platform**|PC|
|**OS**|Windows 11|
|**Browser**|Chrome|
|**URL**|<https://sweetshop.netlify.app/sweets.html>|
|**Environment**|UAT|
|**Description**|<p>Open the main page by the link</p><p>[ ](https://sweetshop.netlify.app/sweets.html)<https://sweetshop.netlify.app/sweets.html></p><p>1. Click "Add to basket" for the item "Sherbert Straws" with a price of</p><p>£0.75.</p><p>2. Click on "Basket" on the top right panel.</p><p>3. Click on “Standard Shipping” from the “Delivery” section.</p><p></p>|
|**Actual**|<p>It calculates the wrong total sum in ‘Total (GBP)’ field and</p><p>show £NaN.</p><p></p>|
|**Expected**|The 'Total (GBP)' field should show £2.74.|

## Bug 4


|**Bug**|4|
| :- | :- |
|**Submit Date**|09-02-2023|
|**Summary**|"Promo code" does not work in the "Basket"|
|**Severity**|critical|
|**Product**|Sweet Shop|
|**Component**|Not applicable|
|**Version**|Unknown|
|**Platform**|PC|
|**OS**|Windows 11|
|**Browser**|Chrome|
|**URL**|<https://sweetshop.netlify.app/sweets.html>|
|**Environment**|UAT|
|**Description**|<p>Open the main page by the link</p><p>[ ](https://sweetshop.netlify.app/sweets.html)<https://sweetshop.netlify.app/sweets.html></p><p>1. Click "Add to basket" for the item "Sherbert Straws" with a price of</p><p>£0.75.</p><p>2. Click on "Basket" on the top right panel.</p><p>3. Click on “Promo code” field</p><p>4. Enter ‘a3adf3’ value and press “Redeem”.</p><p></p>|
|**Actual**|Page is reloaded and nothing is displayed.|
|**Expected**|<p>The page should display an error or success message</p><p>informing the user that the promo code was entered correctly or not.</p>|


## Bug 5


|**Bug**|5|
| :- | :- |
|**Submit Date**|09-02-2023|
|**Summary**|Checkout functionality is not working|
|**Severity**|critical|
|**Product**|Sweet Shop|
|**Component**|Not applicable|
|**Version**|Unknown|
|**Platform**|PC|
|**OS**|Windows 11|
|**Browser**|Chrome|
|**URL**|<https://sweetshop.netlify.app/sweets.html>|
|**Environment**|UAT|
|**Description**|<p>Open the main page by the link</p><p>[ ](https://sweetshop.netlify.app/sweets.html)<https://sweetshop.netlify.app/sweets.html></p><p>1. Click "Add to basket" for the item "Sherbert Straws" with a price of</p><p>£0.75.</p><p>2. Click on "Basket" on the top right panel.</p><p>3. Fill all fields in  on “Billing Address” section</p><p>4. Press the “Checkout to continue” button.</p>|
|**Actual**|Page is reloaded and nothing is changed.|
|**Expected**|<p>The page should display an error or success message informing the</p><p>user that the ordering process was completed correctly or not.</p>|


## Bug 6

|**Bug**|6|
| :- | :- |
|**Submit Date**|09-02-2023|
|**Summary**|There is no image for “Wham Bars” item|
|**Severity**|medium|
|**Product**|Sweet Shop|
|**Component**|Not applicable|
|**Version**|Unknown|
|**Platform**|PC|
|**OS**|Windows 11|
|**Browser**|Chrome|
|**URL**|<https://sweetshop.netlify.app/sweets.html>|
|**Environment**|UAT|
|**Description**|<p>Open the main page by the link</p><p>[ ](https://sweetshop.netlify.app/sweets.html)<https://sweetshop.netlify.app/sweets.html></p><p></p>|
|**Actual**|<p>Image for "Wham Bars" item has not been loaded</p><p></p><p></p>|
|**Expected**|<p>Visible Image of the item should be loaded.</p><p></p>|






# Summary

The app looks and feels simple, based on the Twitter Bootstrap css theme.

There should be bug fixes and additions:

1. The "About" page should be filled with well-described information about the company.
1. Add a "Terms and Conditions" page with information about the company's terms of service.
1. Add a 'Registration' page with the function of registering new users.
1. Add a 'Forgot password' function to the login page to enable the user to recover lost passwords.
1. Add a footer with links to ‘About’ and ‘Term and Conditions’ pages.



