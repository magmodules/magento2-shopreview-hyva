
![265448554-25bf88eb-c629-46e6-bcf3-3053bc6dbbca](https://github.com/magmodules/magento2-shopreview-hyva/assets/24823946/120a0c44-0d61-4110-88db-7fee011968fd)


# Shopreviews Hyvä Compatibility plugin


Shopreview is a powerful Magento extension for collecting and managing customer reviews. It offers full control over review forms, keeps reviews in-house, and provides customizable widgets for seamless integration into your store. With a one-time payment and no monthly subscription costs, it's a cost-effective solution for enhancing your online shop's reputation and customer trust.

The Shopreviews compatibility plugin for the Magento Hyvä theme has the following requirements:
- [Magento 2.4.+](https://github.com/magento/magento2)
- [Hyvä](https://github.com/hyva-themes)
- [Magmodules Shopreviews](https://www.magmodules.eu/magento2-shopreview.html) 


## About the Shopreviews Plugin

Enhance your Magento store's reputation with our comprehensive store reviews extension. Our Shopreview extension allows you to effortlessly collect, manage, and showcase customer feedback. With features like import and export functions, you have full control, ensuring reviews stay in-house. Positive customer reviews provide powerful 'Social proof' to boost trust and drive sales in your Magento store.

Shopreview for Magento empowers you to customize review forms to your liking. As an admin, you can add, modify, or remove fields, set mandatory requirements, and define placeholders. Our extension seamlessly integrates with default front-end styles, ensuring your review forms blend seamlessly with your template. Plus, there are no ongoing monthly subscription costs – it's a one-time purchase for long-term benefits. Elevate your store's reputation with Shopreview for Magento today.

## Installation

1. Install the module using composer: 

```bash
composer require magmodules/magento2-shopreview-hyva
```

2. Enable the module:

```bash
bin/magento module:enable Magmodules_HyvaShopreview
```

3. Upgrade the database:

```bash
bin/magento setup:upgrade
```

4. Let Hyvä know about the new module:

```bash
php bin/magento hyva:config:generate
```

5. Generate the CSS files:

```bash
npm --prefix vendor/hyva-themes/magento2-default-theme/web/tailwind/ run ci
npm --prefix vendor/hyva-themes/magento2-default-theme/web/tailwind/ run build-prod
```

Or from your theme:

```bash
npm --prefix app/design/frontend/<Vendor>/<Theme>/web/tailwind run ci
npm --prefix app/design/frontend/<Vendor>/<Theme>/web/tailwind run build-prod
```

## Shopreviews Magento plugin features

- Seamless integration
- Full Form control
- Customizable review widgets
- Rich snippet integration
- Review moderation and management
  
## Magento Support

If you have any questions, please fill out our secure contact form by clicking [here](https://www.magmodules.eu/support-form.html).

## Magmodules & Hyva

Magmodules and Hyva have established a strong partnership, working closely together to provide enhanced e-commerce solutions. As an official Hyva partner, we specializes in developing integrations for various platforms and services. 

We have created integrations for well-known providers such as Mollie, Sooqr, Paazl, and many more. This collaboration ensures seamless compatibility and optimized performance for online stores utilizing the Hyva theme. Through our partnership, Magmodules and Hyva strive to deliver comprehensive and tailored solutions to meet the diverse needs of e-commerce businesses.






## Checkout our other Hyva Plugins!

[- Magento 2 Hyvä Shopreview](#) 
 
[- Magento 2 Hyvä Product Review Reminder](#) 

[- Magento 2 Hyvä Mollie React Checkout](#) 

[- Magento 2 Hyvä Checkout](#) 

[- Magento 2 Hyvä Mollie React Checkout](#) 

[- Magento 2 Hyvä Paazl](#) 
