# Upcoming Releases
[![Current Release](https://img.shields.io/github/release/epluno/changelog.svg?style=for-the-badge&logo=github&logoColor=white&colorA=101119&colorB=00b586)](https://github.com/epluno/changelog/releases/latest)



## Unreleased

##### `v0.6.0`

* e-commerce multi-site (start of feature - this is a sub-system has its own releases `v0.3.1`)
  - Custom Reporting
    - custom filters for report generation to export of csv
* Point-of-Sale
  - Back order handling
    - workflow and UX of how backorders will work.
    - custom order status of `Includes Backorder`
  - Performance improvements - query times
  - Re-evaluate the UX and UI
    - more user friendly UI for **touch only** interfaces
  - Program specific garment structure
    - Add MongoDB or Postgress data store integration for program data seperation
      - attempt to keep master data in-place without garment and sku duplication.
* Shop Builder (start of feature - this is a sub-system has its own releases  `v0.0.2`)
  * New store creation
    - Clone option
  * CSV product import - optimization for performance
    - Column Mapping
      - Ux/Ui modifications

##### `v0.7.0`

* Frontend Manager _(backoffice)_ (start of feature - this is a sub-system `v0.0.1`)
  * All store manager operations  without Stockroom management
* Storefront Manager (start of feature - this is a sub-system `v0.0.2`)
  * More controls over UI
  * Customer Account Centric UI
    * my accounts
    * abandon carts
    * reorder previous order
  * Additional Theme Options
    * template design for dynamic/smart components
    * template design for static/dumb components
    * Integrate Flightdeck /GoTemplates for future improvements to headless (API)

##### `v0.8.0`

* Inventory Management (start of feature - this is a sub-system)
  * location and bin management 
  * Intra-commerce transfers (warehouse to warehouse to retail transfers)
  * 3rd party vendor purchase-order management - better PO status - receivables 
* Product Services (start of feature - this is a sub-system)
  * update one to many from master
  * additional variant controls 
    * syncing selective variants to specific programs
* Customer Management (start of feature - this is a sub-system)
  * related to Oauth
  * betters CRUD - extensive systems control user to user, user to group, group to user, 

##### `v0.9.0`

* Remote Authentication Services
  * Oauth 
  * Active Directory / Single Sign On
* Order manager
  * automated notification emails with reporting 
  * custom metric dashboard widgets (saved configuration)
* Payment Gateway customization
  * program markup - breakout of percentage and/or fixed dollar amount garment markups (ie: fundraising - garment sale + cost of markup)
  * commission sales with breakpoints based on markup percentages

