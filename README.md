# Magento compatible Google APIs Client Library #

## Description ##
The Google API Client Library enables you to work with Google APIs such as Google+, Drive, or YouTube on your server.
This fork only mirrors the main repository and allows you to use the Google API Client Library with Composer ready Magento 1.x Versions.

Maintained by rayphi.

## Installation ##
Example:
```json
{
  "name" :              "vendor/magento-project",
  "description" :       "Magento Project",
  "license" :           "OSL-3.0",
  "minimum-stability" : "dev",
  "require" :           {
    "magento-hackathon/composer-command-integrator": "~1.2",
    "rayphi/google-apiclient":                       "~1.1",
    "magento-hackathon/magento-composer-installer":  "~3.0",
    "aydin-hassan/magento-core-composer-installer":  "~1.2",
    "firegento/magento":                             "~1.9.2"
  },
  "repositories" :      [
    {
        "type": "composer",
        "url": "https://packages.firegento.com"
    },
    {
        "type": "vcs",
        "url": "https://github.com/rayphi/google-api-php-client.git"
    }
  ],
  "extra" :             {
    "magento-root-dir" :       "./docroot",
    "magento-force" :          true,
    "magento-deploystrategy" : "copy",
    "disable-core-installer":  false,
    "package-xml":             "package.xml"
  }
}
```