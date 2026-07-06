============================================
Reconnect the Shopify connector instructions
============================================

If you disconnect the Shopify account and want to reconnect it in Odoo, follow these steps:

#. Sign in to `the admin account <https://admin.shopify.com/>`_ and select the store that was
   disconnected from Odoo.
#. Open the **Settings** menu and select **App Development**.

   .. image:: reconnect-instructions/shopify-app-development.png
      :alt: Example of using the navigation search bar to find App Development.

#. Click **Build apps in Dev Dashboard** to access the dev dashboard.

   .. image:: reconnect-instructions/shopify-build-apps-dev-dashboard.png
      :alt: Build app in Dashboard button.

#. Select the app on the dev dashboard that connected the Shopify account to Odoo.
#. Click **Settings** in the navigation bar.
#. Copy the **Client ID** and **Client Secret** from the *Credentials* section.

   .. image:: reconnect-instructions/shopify-credentials.png
      :alt: Example of the Credentials section in the Settings page.

#. Paste these into the **Shopify Client Id** and **Shopify Client Secret** fields in the
   *Credentials* tab in the Odoo browser.

   .. image:: reconnect-instructions/odoo-credentials.png
      :alt: Add alt text.

#. Go back to the *Shopify* tab in the browser and click the app’s name.
#. Click **Install app**, then select the app to install in the Shopify store and click **Install**.

   .. image:: reconnect-instructions/shopify-install-app.png
      :alt: Installs section with the Install app button.

#. After reinstalling the app in the Shopify store, the page redirects to the Shopify account in
   Odoo. The account is now reconnected with Shopify. To verify, check the account's connection
   status and confirm that the *Shopify Access Token* has been fetched.

   .. image:: reconnect-instructions/shopify-access-token.png
      :alt: Example of a reconnected Shopify account form.

.. toctree::
   :titlesonly:
  - index
  - set-up-instructions
