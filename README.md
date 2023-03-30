# pwa-kit-codespace-template
Create a codespace from this repo to easily get an environment setup with the correct version of Node and NPM.

## Create a new project
```
npx pwa-kit-create-app@latest —outputDir MRT-PROJECT-ID
```

## Project Presets
When prompted to choose a project preset, select from one of the following options:

* retail-react-app-demo: Use the Retail React App storefront template and use the demo sandbox for the back end. No further configuration required.
* retail-react-app: Use the Retail React App storefront template and use your own B2C Commerce instance for the back end. You must provide configuration values.

## Configuration Values
| Configuration Value | More Information |
|---------------------|------------------|
| Project ID in Managed Runtime Admin | [Managed Runtime Administration](https://developer.salesforce.com/docs/commerce/pwa-kit-managed-runtime/guide/managed-runtime-administration.html) covers how to create a project and look up the project ID of an existing project. <br/> Example: example-project |
| URL for your B2C Commerce instance | Example: https://zzdc-001.sandbox.us01.dx.commercecloud.salesforce.com |
| Commerce API client ID | This identifier isn’t found in Account Manager anymore. See [Generate a Client ID for API Access](https://developer.salesforce.com/docs/commerce/pwa-kit-managed-runtime/guide/setting-up-api-access.html#3-generate-a-client-id-for-api-access). <br/> Example: 1adba44c-ee9b-41f9-b4bf-1bbc3dda1967 |
| Site ID in Business Manager | String used to identify a particular ecommerce site. To get a list of available sites and their associated site IDs in Business Manager, go to **Administration > Sites > Manage Sites**. <br/>Example: RefArch |
|Commerce API organization ID in Business Manager | String used to identify your organization for API access based on the realm and instance. To find the organization ID in Business Manager, go to **Administration > Site Development > Salesforce Commerce API Settings**. <br/> Example: f_ecom_zzdc_001 |
|Commerce API short code in Business Manager| An eight-character string assigned to a realm for routing purposes. The short code applies to your entire realm environment, across all instances. (The short code for all on-demand sandboxes is kv7kzm78). To find your short code in Business Manager, go to **Administration > Site Development > Salesforce Commerce API Settings**. <br> Example: kv7kzm78 |

Reference: https://developer.salesforce.com/docs/commerce/pwa-kit-managed-runtime/guide/setting-up-your-local-environment.html
