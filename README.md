# CampusCrave — Redeemer's University Food Delivery Demo

A static front-end prototype designed to be published with GitHub Pages.

## Included
- Student menu browsing, search, category filters, sorting, cart, and demo checkout
- Student order history and demo order status
- WhatsApp support link using 09169398221
- Checkout opens WhatsApp with an order summary for manual confirmation
- Restaurant dashboard for incoming orders and menu management
- Admin dashboard for order oversight, restaurant directory, CSV export, and demo reset
- Demo food ratings and completed-order reviews
- Local browser storage for prototype data

## Not included yet
- Delivery-agent portal (removed from the project scope)
- Real authentication or role-based permissions
- Shared live database or cross-device order updates
- Real payments
- Real email/SMS notifications
- Secure production handling of customer data

**Important:** All portal views are publicly accessible in this prototype. Do not use real customer data or treat it as a production system.

## Publish with GitHub Pages
1. Create a GitHub repository, for example `campuscrave`.
2. Upload `index.html` to the repository's root.
3. Open **Settings → Pages**.
4. Under build/deployment, choose **Deploy from a branch**.
5. Select your main branch and the `/ (root)` folder, then save.
6. Wait for GitHub Pages to publish the site; the URL will appear on the Pages settings screen.

## Customize
- Search for `CampusCrave` in `index.html` to change the brand name.
- Search for `initialFoods` to edit the sample menu.
- Search for the CSS variables at the top of the `<style>` block to change the colors.
