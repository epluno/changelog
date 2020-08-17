# Unreleased Releases
[![Current Release](https://img.shields.io/github/release/epluno/changelog.svg?style=for-the-badge&logo=github&logoColor=white&colorA=101119&colorB=00b586)](https://github.com/epluno/changelog/releases/latest)

---

##### `v0.6.0` -  planned release date: 8/31/2020

* e-commerce multi-site (start of feature - this is a sub-system has its own releases `v0.3.1`)
  - Custom Reporting - (start of feature)
    - Integration of particle shippment order statuses
      - `Partially Shipped`
      - `Shipped` or `Complete`
      - `Not Shipped`
    - custom filters for report generation to export of csv
* Point-of-Sale
  - Back order handling - related to Partial Shipment order status
    - workflow and UX of backorder is now simplified.
      - add items to cart that are flagged as `Partially Shipped` _(these are items that physically have left the retail store)_
    - custom order status for Partial Shipments
    - customer account and shipping details are now **required** by default.
  - Performance improvements - query times
    - faster garment loading with variants and per school program
  - Re-evaluate the UX and UI
    - more user friendly UI for **touch only** interfaces
* Shop Builder (start of feature - this is a sub-system has its own releases  `v0.0.2`) 
  * ~~New store creation:~~ **added to release `v0.5.8`**
    - ~~Clone option~~
  * ~~CSV product import - optimization for performance:~~ **added to release `v0.5.8`**
    - Column Mapping
      - Ux/Ui modifications
  * Usability Guide / Tutorial - How to use
* ~~Email Notification Templates:~~ - **added to release `v0.5.8`**
  * ~~Additional information added for manual accounting processes.~~

---

##### `v0.7.0` -  planned release date: 10/09/2020

* Program specific garment structure **_(ideally this is to be released on `v0.6.5`)_**
  - Add MongoDB or Postgress data store integration for program data seperation
    - attempt to keep master data in-place without garment and sku duplication.
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

---

##### `v0.8.0` -  planned release date: 11/25/2020

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

---

##### `v0.9.0`-  planned release date: 1/22/2020

* Remote Authentication Services
  * Oauth 
  * Active Directory / Single Sign On
* Order manager
  * automated notification emails with reporting 
  * custom metric dashboard widgets (saved configuration)
* Payment Gateway customization
  * program markup - breakout of percentage and/or fixed dollar amount garment markups (ie: fundraising - garment sale + cost of markup)
  * commission sales with breakpoints based on markup percentages

