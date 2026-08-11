Get Started
===============================
A clear, step-by-step integration flow designed to connect, synchronize, and operate Magento seamlessly with Odoo 19. Explore the complete feature coverage, operational flow, and system behavior in detail by reviewing the official integration overview below:

https://www.odoo.com/r/ecommerce-magento

Magento Connector Release Notes
===============================

* **Version 19.0.1.4 (2026-07-22)**

  - Optimized inventory synchronization to send stock updates more efficiently from Odoo to Magento.

* **Version 19.0.1.3 (2026-06-29)**

  - Added the "Magento" tag to every customer created from Magento.

* **Version 19.0.1.2 (2026-06-16)**

  - Implemented handling of fulfillments received from Magento using a backorder-based approach to ensure accurate inventory synchronization.
  - Added location on picking based on the location mapped to Magento fulfillment.
  - Synced inventory immediately after order synchronization and updated the scheduled action timings for order, inventory and picking sync.

* **Version 19.0.1.1 (2026-05-18)**

  - Improved the email structure sent to user when order pull, inventory push or delivery push operations fail.
  - During order pull failures, only one email is sent to the user containing all failed order references and the reasons of failure, instead of sending separate emails for each order.
