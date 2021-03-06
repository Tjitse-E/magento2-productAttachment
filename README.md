# Magento2 Product Attachment

The Product Attachments extension for Magento 2 equips product pages with a special attachments block where you can upload numerous documents such as user guides, extra images, pdf, certificates, licenses and many others.

# Installation Instruction

- Copy the content of the repo to the <b>app/code</b>
- Run command: <b>php bin/magento setup:upgrade</b>
- Run command: <b>php bin/magento setup:static-content:deploy</b>
- Now flush cache: <b>php bin/magento cache:flush</b>

# How to Change Attachment Icons

<b>Frontend Attachments Icons:</b>

You can find all frontend attachment icons from here `Prince\Productattach\view\frontend\web\images`
Just replace icon images with your icon image. Image file must be in png format.

<b>Admin Attachments Icons:</b>

You can find all admin attachment icons from here:`Prince\Productattach\view\adminhtml\web\images`
Just replace icon images with your icon image. Image file must be in png format.

<b>Run This Commands After changes icon images</b>

php bin/magento setup:static-content:deploy

php bin/magento cache:flush

# Screenshot

<h3>Product Page</h3>
<img src="https://raw.githubusercontent.com/mageprince/all-module-screenshots/master/Product-Attahments/prduct-view-page.png" alt="Product Page">

<h3>Attachment Admin Grid</h3>
<img src="https://raw.githubusercontent.com/mageprince/all-module-screenshots/master/Product-Attahments/2-admin-grid.png" alt="Attachment Admin Grid" />

<h3>Add/Edit Attachment</h3>
<img src="https://raw.githubusercontent.com/mageprince/all-module-screenshots/master/Product-Attahments/1-add-edit-attachment.png" alt="Add-Edit Attachment" />

<h3>Select Products</h3>
<img src="https://raw.githubusercontent.com/mageprince/all-module-screenshots/master/Product-Attahments/3-select-products.png" alt="Select Products On Add-Edit Attachment" />

<h3>Attachment Settings</h3>
<img src="https://raw.githubusercontent.com/mageprince/all-module-screenshots/master/Product-Attahments/4-settings.png" alt="Attachment Settings" />

