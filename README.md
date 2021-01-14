# magentotest

# Installation
The modules are intended to be installed using composer. If you do not have composer installed (check by entering the command "composer --help" into your terminal), please install it using the following commands:

composer require salecto01web/bharat
After installing Salecto theme, you can verify that the installation succeeded by going to the Magento 2 back-end and navigating to Content -> Design -> Themes. If it listed there, you should be happy.

Normally, this theme will never be set as a the main theme for a client, but to set this theme for development purposes on the storefront, go to: Content -> Design -> Configuration and set the Optimus theme on the Store View you wish to use. Do not forget to flush the cache afterwards.

# For custom Attribute

Create custom attribute with the Code"custom_link" in Magento backend under STORES->Attributes->Product.
To Display, the new attribute in List Page, set the value “YES” to “Used in Product Listing” under storefront Properties while creating the attribute.

Assign the newly created Attribute to Default attribute set in STORES->Attributes->Attribute Set.

Now you can see the attribute ‘custom_link’ in the manage product section. You can enter the appropriate value


