# LIBAAS.PK — Men's Unstitched Collection

A responsive storefront starter for LIBAAS.

## Current features
- White, dark-brown and muted-gold visual identity
- Responsive homepage and collection grid
- Cart saved in the customer's browser
- Checkout form with customer and delivery details
- WhatsApp order handoff to LIBAAS Business WhatsApp
- Flat Rs. 200 delivery fee

## Before launch
1. Replace the sample products and prices in `script.js` with the real catalogue.
2. Replace the fabric placeholder in `index.html` / product rendering with supplied product photos.
3. Add real fabric descriptions, availability and return/shipping policies.
4. Configure a secure order database and admin dashboard before treating this as a complete store.
5. For automatic WhatsApp image delivery or server-triggered messages, integrate the official WhatsApp Business Platform (Cloud API) with a secure backend. A normal `wa.me` checkout opens a prefilled text message; the customer must press Send, and it cannot attach product photos automatically.

## Deploy
This is a static front-end and can be hosted on a static hosting provider. The current checkout is a WhatsApp handoff, not an online payment gateway or server-side order system.
