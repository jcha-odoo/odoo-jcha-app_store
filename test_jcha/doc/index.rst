Shopify Connector Release Notes
===============================

* **Version 19.0.2.1 (2026-06-16)**

  - Implemented handling of fulfillments received from Shopify using a backorder-based approach to ensure accurate inventory synchronization.
  - Added location on picking based on the location mapped to Shopify fulfillment.
  - Synced inventory immediately after order synchronization and updated the scheduled action timings for order, inventory and picking sync.

* **Version 19.0.2.0 (2026-06-04)**

  - Added return and refund functionality.

* **Version 19.0.1.3 (2026-06-02)**

  - Added a "Create Taxes" configuration at the account level to manage tax handling during order imports.
  - When enabled, taxes are automatically matched or created from imported data; otherwise, taxes are applied based on fiscal position or the product's default taxes.

* **Version 19.0.1.2 (2026-05-29)**

  - Implemented functionality to fetch orders that were created or updated within a given date range.
  - Moved the button for fetching orders created or updated after a given date under Developer Mode.

* **Version 19.0.1.1 (2026-05-18)**

  - Improved the email structure sent to user when order pull, inventory push or delivery push operations fail.
  - During order pull failures, only one email is sent to the user containing all failed order references and the reasons of failure, instead of sending separate emails for each order.

.. toctree::
   :titlesonly:

   index
   set-up-instructions
   reconnect-instructions

