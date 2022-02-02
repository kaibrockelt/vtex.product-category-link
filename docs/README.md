📢 Use this project, [contribute](https://github.com/vtex-apps/product-summary) to it or open issues to help evolve it using [Store Discussion](https://github.com/vtex-apps/store-discussion).

# Product Summary category link

<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-2-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->

Product Summary addon providing a deeplink into a product's final category. It is supposed to be used within a [product summary](https://developers.vtex.com/vtex-developer-docs/docs/vtex-product-summary), alongside with components such as the [Shelf](https://vtex.io/docs/components/all/vtex.shelf/) and the [Minicart](https://vtex.io/docs/components/all/vtex.minicart/).

![image](https://user-images.githubusercontent.com/284515/70235170-1a503a80-1741-11ea-952d-07b178995f92.png)

## Configuration
1. install the app:
```shell
  vtex install 
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
+     "product-summay-category-link",
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
