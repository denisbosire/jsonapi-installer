# jsonapi-installer
Use to setup the jsonapi demo plugin for inpsyde
# download composer.json
Navigate to your WP root directory, then download composer.json
`wget https://github.com/denisbosire/jsonapi-installer/blob/main/composer.json`

## Then run:
`composer install`
This might take a few minutes, it will install a plugin called 'jsonapi' in wp-content/plugin/jsonapi

# issues
Sometimes the vendor folder doesnt get auto populated with all the packages
Navigate 'wp-content/plugin/jsonapi/vendor'
