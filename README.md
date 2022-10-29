# FE-EDU-TASK

## describtion
1. Created theme 'Scandiweb/base'
2. Inserted a new container with 'Free Shipping' block and displayed it conditionally if free shipping method is enabled
3. “Newsletter Subscription” moved form right above the footer (with updated placeholder)
4. Removed “Related Products” block from Grouped Product Detail Page
5. Added the same custom <body> class to grouped and bundled products
6. Removed confirmation popup when deleting products from minicart

## code changes

1. Change #1
Separate div above header
![fix1](https://user-images.githubusercontent.com/81425551/198561608-9f92c721-bb09-4267-b58e-f1038f40989a.png)

2. Change #2
Moved form.subscribe out of footer container, change the place where "subscribe.phtml" was placed.
![fix2](https://user-images.githubusercontent.com/81425551/198569502-6ad515e3-753d-4e38-abd1-639b21357e81.png)

3. Change #3
Removed related products from Grouped Product Details Page, I have also moved the "catalog_product_view_type..." files to correct path following the instructions included in the feedback.

4. Change #4
Mixin is working fine hope I did it the way it is supposed to be done (I referred to the following [documentation](https://developer.adobe.com/commerce/frontend-core/javascript/mixins/), not sure if the files are in the correct path.

