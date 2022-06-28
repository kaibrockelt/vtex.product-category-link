## 🚨 Disclaimer - Template Application
>:warning: **This project is not maintained by VTEX, and this app is provided as a working example on how this feature can be implemented. Improvements and fixes will be on the implementation team side.**
>
>All template applications provided are developed by the VTEX community, you can use them freely.

&nbsp;

📢 Use this project, [contribute](https://github.com/vtex-apps/product-summary) to it or open issues to help evolve it using [Store Discussion](https://github.com/vtex-apps/store-discussion).

# Product Summary category link

<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-2-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->

Product Summary addon providing a deeplink into a product's final category. It is supposed to be used within a [product summary](https://developers.vtex.com/vtex-developer-docs/docs/vtex-product-summary), alongside with components such as the [Shelf](https://vtex.io/docs/components/all/vtex.shelf/) and the [Minicart](https://vtex.io/docs/components/all/vtex.minicart/).

![categorylink](https://user-images.githubusercontent.com/93577143/152136528-6eb3a2a1-d6b2-47c0-85fc-c4c08155f6b9.jpg)

## Configuration
1. install the app:
```shell
  vtex install vtex.product-category-link@0.x
```
2. Import the `vtex.product-category-link` app to your theme's dependencies in the `manifest.json`:

```json
  "dependencies": {
    "vtex.product-category-link": "0.x"
  }
```

Now, you are able to add a category link to the `product-summary` app.




```json
  "product-summary.shelf": {
    "children": [
      "product-summary-name",
      "product-summary-description",
      "product-summary-category-link",
      "product-summary-image",
+     "product-summary-category-link",
      "product-summary-price",
      "product-summary-sku-selector",
      "product-summary-buy-button"
    ]
  }

```

## Customization

In order to apply CSS customizations in this and other blocks, follow the instructions given in the recipe on [Using CSS Handles for store customization](https://vtex.io/docs/recipes/style/using-css-handles-for-store-customization).

| CSS Handles                | 
| -------------------------- |
|  'categoryLink' |
|  'categoryLinkContainer'  |
|  'loading'                |
