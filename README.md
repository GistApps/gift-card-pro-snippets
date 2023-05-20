# Gift Card Pro - Snippets

This repository contains Shopify snippets for Gift Card Pro.
If you are using a Vintage theme on Shopify, these snippets are already added to your theme files when you install the app.

## Installation

Onboarding instructions are also avaliable in [Gift Card Pro's documentation](https://docs.giftcardpro.app/).

To create a new snippet from your Shopify admin dashboard:
1. Navigate to the Online Store Sales Channel and open your theme's code editor.
2. In the Snippets directory, select *Create a new snippet* and name the file.
3. Include the snippet in a template using a liquid render tag.

**`{% render 'my-snippet-name' %}`**

## Snippets

**gift-card-pro-cart-item-properties.liquid**

This snippet is required if you would like to display gift card information, such as the recipient name and deliery date, as part of the line item properties on the cart page.

For more information on displaying gift card line item properties, see [our documentation article](https://docs.giftcardpro.app/article/installing-gift-card-item-properties-snippets-making-gift-card-details-visible-on-the-cart-page-and-checkout/).
