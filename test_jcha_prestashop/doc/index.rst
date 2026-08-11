Get Started
===============================
A clear, step-by-step integration flow designed to connect, synchronize, and operate PrestaShop seamlessly with Odoo 19. Explore the complete feature coverage, operational flow, and system behavior in detail by reviewing the official integration overview below:

https://www.odoo.com/r/ecommerce-prestashop

PrestaShop Connector Release Notes
==================================

* **Version 19.0.1.6 (2026-07-22)**

  - Optimized inventory synchronization to send stock updates more efficiently from Odoo to PrestaShop.

* **Version 19.0.1.5 (2026-06-29)**

  - Added the "PrestaShop" tag to every customer created from PrestaShop.

* **Version 19.0.1.4 (2026-06-16)**

  - Added location on picking based on the location mapped to PrestaShop fulfillment.
  - Synced inventory immediately after order synchronization and updated the scheduled action timings for order, inventory and picking sync.

* **Version 19.0.1.3 (2026-06-02)**

  - Added a "Create Taxes" configuration at the account level to manage tax handling during order imports.
  - When enabled, taxes are automatically matched or created from imported data; otherwise, taxes are applied based on fiscal position or the product's default taxes.
  - Improved discount import handling by creating separate discount lines for each imported discount instead of combining them into a single discount line.

* **Version 19.0.1.2 (2026-06-01)**

  - Implemented functionality to fetch orders that were created or updated within a given date range.
  - Moved the button for fetching orders created or updated after a given date under Developer Mode.

* **Version 19.0.1.1 (2026-05-18)**

  - Improved the email structure sent to user when order pull, inventory push or delivery push operations fail.
  - During order pull failures, only one email is sent to the user containing all failed order references and the reasons of failure, instead of sending separate emails for each order.
