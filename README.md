# jsonapi-installer
Use this to setup the jsonapi demo plugin for inpsyde via composer (*access to the private repo required*)

## 1. Download composer.json
Navigate to your WP root directory, then download composer.json   
`wget https://github.com/denisbosire/jsonapi-installer/blob/main/composer.json`

## 2. Then run:
`composer install`. 

This might take a few minutes, it will install a plugin called 'jsonapi' in wp-content/plugin/jsonapi

# 3. Issues
Sometimes the vendor folder doesnt get auto populated with all the packages
Navigate 'wp-content/plugin/jsonapi/vendor' then run;
`composer install` 

# 4. Activate the plugin
Navigate to admin dashboard > plugins, activate jsonapi.  
Navigate to https://YOURWPURL/custom_url on your browser.
