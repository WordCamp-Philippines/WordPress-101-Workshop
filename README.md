# WordPress 101: Build Your Own Website and Online Shop

Welcome to the official workshop repository for **WordPress 101: Build Your Own Website and Online Shop** at **WordCamp Philippines 2026 – Contributor Day**.

This repository contains the workshop materials, sample files, product images, and resources that participants will use during the hands-on session.

## Workshop overview

In this workshop, you will build a complete WordPress website with a simple online shop using **WordPress Studio**, **Storefront**, and **WooCommerce**.

By the end of the workshop, you will have:

* A working WordPress website
* A homepage
* An About page
* A Contact page
* A functioning online shop
* Products with categories and images
* A working cart and checkout flow

No coding experience is required.

## Before the workshop

### 1. Install WordPress Studio

Download and install WordPress Studio:

https://developer.wordpress.com/studio/

Make sure the application launches successfully before the workshop.

### 2. Create a new local WordPress site

Open WordPress Studio and create a new site.

### 3. Install the required theme

Inside WordPress:

* Go to **Appearance → Themes**
* Click **Add Theme**
* Search for **Storefront**
* Install and activate it

### 4. Install WooCommerce

* Go to **Plugins → Add New**
* Search for **WooCommerce**
* Install and activate it

## Repository contents

```text
wordpress-101-workshop/
│
├── README.md
├── workbook/
│   └── WordPress_101_Workshop_Workbook_WCPH2026.pdf
├── assets/
│   ├── logo.png
│   ├── homepage-banner.jpg
│   └── products/
├── woocommerce/
│   └── sample-products.csv
├── patterns/
│   └── homepage-pattern.json
└── resources/
    ├── WordPress-Cheat-Sheet.pdf
    └── Useful-Links.pdf
```

## Importing sample products

1. Go to **Products → Import**
2. Select `woocommerce/sample-products.csv`
3. Map the columns if prompted
4. Complete the import

After importing, assign the product images from the `assets/products/` folder.

## Workshop flow

### Module 1: Launch WordPress Studio

Create a new local WordPress site.

### Module 2: Explore the dashboard

Learn the basic WordPress interface.

### Module 3: Install Storefront

Activate the Storefront theme.

### Module 4: Create pages

Create:

* Home
* About
* Shop
* Contact

### Module 5: Customize Storefront

Update:

* Site title
* Logo
* Colors
* Homepage settings

### Module 6: Install WooCommerce

Configure the basic store settings.

### Module 7: Import products

Import the sample product catalog.

### Module 8: Build the homepage

Create a homepage using the Block Editor.

### Module 9: Test the online shop

Complete a demo purchase from product page to checkout.

## Recommended settings

| Setting        | Value                   |
| -------------- | ----------------------- |
| Theme          | Storefront              |
| Plugin         | WooCommerce             |
| Currency       | PHP                     |
| Store location | Philippines             |
| Payments       | Cash on Delivery (demo) |

## Troubleshooting

### Storefront is not visible

Go to **Appearance → Themes → Add Theme** and search for **Storefront**.

### WooCommerce pages are missing

Go to **WooCommerce → Status → Tools** and recreate the default WooCommerce pages.

### Product images are not showing

Edit the product and upload the corresponding image from the `assets/products/` folder.

## Resources

* WordPress: https://wordpress.org
* WooCommerce: https://woocommerce.com
* WordPress Studio: https://developer.wordpress.com/studio/
* WordPress User Group Philippines: https://www.facebook.com/groups/wpugph

## License

These workshop materials are provided for educational purposes for participants of **WordCamp Philippines 2026**.

Happy building, and welcome to the WordPress community!
