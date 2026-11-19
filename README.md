# Threecommerce_Subscription: recurring orders for Magento 2 / Mage-OS

**Subscribe and save** for Magento 2 and Mage-OS: customers choose a delivery frequency on the product page, pay the first order with a card that is saved, and every next order is created and charged automatically, at the subscription price set by the merchant.

**Compatibility:** Magento Open Source / Adobe Commerce 2.4.4+ · Mage-OS 3.x – 4.x · PHP 8.2 – 8.5 · Frontend templates target Hyvä
**License:** commercial · coming soon

## Features

- **Subscription price per product**: a fixed subscription price (never higher than the regular price) or a percentage discount, and the frequencies allowed for each product. Simple, virtual, downloadable and configurable products.
- **Frequencies** from every week to every year: the store enables a list and a default.
- **Product page choice**: "One-time purchase" or "Subscribe and save", with the saving shown and the frequency select.
- **Cart and checkout**: subscription lines are kept apart from one-time purchases of the same product and show the chosen frequency; the subscription price follows the current price (special prices, catalog rules, tier prices). Mixed carts work.
- **Saved card only**: with a subscription in the cart only payment methods that save the card (Magento Vault) are offered, offline methods are hidden, the card is always saved and guest checkout is disabled.
- **Automatic recurring orders** with the same products, addresses and shipping method, charged on the saved card; products out of stock are left out, and the schedule never drifts.
- **Failed payments**: retries after a set number of days, suspension after the configured attempts, emails to the customer and to the shop. The customer restarts the subscription by choosing another saved card.
- **My Subscriptions** in the customer account: next order date, card, address, products and history; skip a delivery, pause, resume, cancel, change frequency, card or shipping address (each action can be switched off).
- **Admin** (Sales → Subscriptions): grid with filters, detail page with history and actions, including "place the next order now".
- **Emails**: reminder before the next order, payment failed, status changes, alert to the shop.

## Requirements

- Magento Open Source / Adobe Commerce 2.4.4+ or Mage-OS
- PHP 8.2 – 8.5
- A payment gateway with **saved cards (Magento Vault)** enabled, for example Braintree. Other gateways can be connected with a dedicated adapter.
- Package `threecommerce/m2-base` (installed automatically by Composer)

## Availability

This module is **not yet available to buy**. It is a commercial product and is coming soon. To be notified when it is released, or to ask for details, use the [product page](https://www.threecommerce.it/abbonamenti-ordini-ricorrenti-magento-2?utm_source=github&utm_medium=readme&utm_campaign=magento2-subscription) or [get in touch](https://www.threecommerce.it/contatti?utm_source=github&utm_medium=readme&utm_campaign=magento2-subscription).

## Configuration

*Stores → Configuration → Threecommerce Plugins → Subscriptions (Recurring Orders)*: frequencies, product page texts, customer self-service, payment retries and emails. The page also lists the payment methods usable for subscriptions.
