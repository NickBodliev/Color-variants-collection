# Color-variants-collection

A collection template which will show all the color variations of the product as an individual product on the collection page. This task will be performed on the Debut theme.

## Purpose
If you have single product store and the product has different colors, you may want to keep it as one product, but to make your collection page look more 'full'. 
Here is how you can turn that one product into different ones on the collection page, but have the product page stay the same as one product with many variants.

## Getting started
If you do not have a Shopify sandbox account, you can create a trial Shopify store account for this purpose. **Do not** try to do this to your store without having made a **backup!**

## Implementation
There are few simple steps to make:
1. open the editor and search for collection-template.liquid
2. replace the code where you loop through products and show them (lines 140-177) with the [snippet](Section/snippet.liquid)
3. create 'product-card-grid-custom.liquid' in the 'Snippets' 
4. replace the assigned value to the preview_image with varinat.image (line 18)
5. add to the showed info {{ color }} in the line 45

## Authors
- MikeC0xl0ng

## Acknowledgments
- [The product object](https://shopify.dev/docs/themes/liquid/reference/objects/product)
- [The variant object](https://shopify.dev/docs/themes/liquid/reference/objects/variant)


