# MobWeb_AnalyticsSalesFunnel extension for Magento

A simple Magento extension that sends page view event to Google Analytics for each step of the one page checkout. This event can be used to create a sales funnel with data for each individual checkout step.

## Configuration

No configuration required. Use the following URLs when creating the sales funnel in Google Analytics:

- Cart: /checkout/cart/
- Checkout: /checkout/onepage/
- Billing address: /checkout/onepage/billing/
- Shipping address: /checkout/onepage/shipping/
- Shipping method: /checkout/onepage/shipping_method/
- Payment method: /checkout/onepage/payment/
- Order review: /checkout/onepage/review/
- Order submitted: /checkout/onepage/success/

## Installation

Install using [colinmollenhour/modman](https://github.com/colinmollenhour/modman/).

## Questions? Need help?

Most of my repositories posted here are projects created for customization requests for clients, so they probably aren't very well documented and the code isn't always 100% flexible. If you have a question or are confused about how something is supposed to work, feel free to get in touch and I'll try and help: [info@mobweb.ch](mailto:info@mobweb.ch).