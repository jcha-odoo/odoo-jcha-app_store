Get Started
===============================
A clear, step-by-step integration flow designed to connect, synchronize, and operate WooCommerce seamlessly with Odoo 19. Explore the complete feature coverage, operational flow, and system behavior in detail by reviewing the official integration overview below:

https://www.odoo.com/r/ecommerce-woocommerce

WooCommerce Connector Release Notes
===================================

* **Version 19.0.2.1 (2026-07-29)**

  - Prevented importing orders for deleted WooCommerce products.
  - Improved order and invoice synchronization.

* **Version 19.0.2.0 (2026-07-22)**

  - Added support for importing refunds from WooCommerce.
  - For partial refunds, a credit note is created in Odoo for the refunded quantities received from WooCommerce.
  - For fully refunded orders, a return is automatically created in Odoo, and a credit note is generated.
  - For direct amount refunds (without a quantity), a credit note is created with a refund adjustment line.
  - Optimized inventory synchronization to send stock updates more efficiently from Odoo to WooCommerce.

* **Version 19.0.1.7 (2026-07-15)**

  - Mark prepaid WooCommerce orders with "Completed" status as paid during order synchronization.

* **Version 19.0.1.6 (2026-06-29)**

  - Added the "WooCommerce" tag to every customer created from WooCommerce.

* **Version 19.0.1.5 (2026-06-16)**

  - Synced inventory immediately after order synchronization and updated the scheduled action timings for order, inventory and picking sync.
  - Added location on picking based on the location mapped to WooCommerce fulfillment.

* **Version 19.0.1.4 (2026-06-17)**

  - Implemented batch inventory updates for simple products and variations.

* **Version 19.0.1.3 (2026-06-04)**

  - Added a "Create Taxes" configuration at the account level to manage tax handling during order imports.
  - When enabled, taxes are automatically matched or created from imported data; otherwise, taxes are applied based on fiscal position or the product's default taxes.

* **Version 19.0.1.2 (2026-06-01)**

  - Implemented functionality to fetch orders that were created or updated within a given date range.
  - Moved the button for fetching orders created or updated after a given date under Developer Mode.

* **Version 19.0.1.1 (2026-05-18)**

  - Improved the email structure sent to user when order pull, inventory push or delivery push operations fail.
  - During order pull failures, only one email is sent to the user containing all failed order references and the reasons of failure, instead of sending separate emails for each order.
