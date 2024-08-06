# AppleMan.pk - Warehouse theme

[Warehouse theme](https://themes.shopify.com/themes/warehouse/styles/metal), customized for the Appleman.pk shopify store


- [Liquid Reference](https://shopify.dev/docs/api/liquid)
- [Docs: Customize a theme](https://shopify.dev/docs/storefronts/themes/getting-started/customize)

```bash
npm install -g @shopify/cli@latest
# brew install ruby

# pull the live theme locally
shopify theme pull --store appleman-pk.myshopify.com

# preview the theme (Google Chrome only)
shopify theme dev
# http://127.0.0.1:9292

# upload theme changes to store
shopify theme push

# make theme live
shopify theme publish
```