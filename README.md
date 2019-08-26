# Scripts to import your products to OpenBazaar  

**Platforms Supported**

* Shopify
* More coming soon!


## Setup Instructions

1. If you have node.js installed then run "npm install" in the root folder

2. Upload your exported CSV sheet to the root folder

3. Edit "config.json" to update 

- Your OpenBazaar node settings. By default the settings will upload to your local node.

- The fileName of your CSV sheet in the root folder.

- In "defaultProductSettings" make sure to edit "shippingOptions" to reflect the shipping areas you will ship to. You can add multiple shipping options for this field.

- Under "defaultProductSettings" add any other default information you would like to include.

4. Run the import script by running the command "node index.js"


**Notes**

If you only ship to specific countries, refer to the "regions.json" file to see the acceptable OpenBazaar country formats.

Enjoy!