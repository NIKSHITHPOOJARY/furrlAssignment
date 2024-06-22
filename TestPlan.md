# Furrl App Test Plan

## Scope of Testing
The goal is to ensure that the Furrl App functions correctly and provides a good user experience.

## Platform
- Web
- Mobile App

## Priority

### High Priority
1. Page failing to load functionality.
2. Critical user actions like Add to Cart, Buy Now.
3. Issues in payment and checkout processes.
4. Security vulnerabilities.
5. Compatibility issues in devices and browsers.

### Medium Priority
1. Filter and search functionality.
2. Sorting and pagination.
3. User reviews and review submission.
4. Performance and load testing.

### Low Priority
1. Visual and UI/UX elements.
2. Typography mistakes.
3. Navigation links which are not critical.
4. Error messages and prompts.

## Test Cases
- Verify that the category page loads successfully with all elements visible.
- Ensure that the search bar works as expected, and user is able to search the exact product.
- Verify that the products are displayed with correct images, names, prices, and discounted amount.
- Verify that the user can sort the products on the basis of - New In, Relevance, Price, and Discount.
- Verify that the Filter Popup opens when user clicks on the filter button.
- Verify that the user can filter on the basis of selection.
- Verify that when user clicks on the save icon the product is saved in the save page.
- Ensure that the user is able to share the product with others.
- Verify when the user clicks on the product it is redirected to the Product Detail Page.
- Verify that the user is able to view all the products in the checkout page after adding it to the cart.
- Verify if the user is able to remove and increase the product quantity in the checkout page.
- Ensure that the total MRP amount is visible in the checkout page.
- Verify after clicking the checkout button user is redirected to the Address page.
- Verify after user fills all the sections in address page he can click on the place order button.

## Edge Cases
- Verify the behavior when adding a product to the cart without selecting any options.
- Ensure the app can handle invalid quantity inputs.
- Check that the page loads within the acceptable time.
- Ensure the app is secure against vulnerabilities during the checkout process.
- Verify the app is user-friendly and easy to navigate.
- Ensure the app works across different devices and browsers.
- Ensure the app can handle traffic without performance issues.
- Verify that after the user has loaded the page and disconnects from the internet, the user should be able to view all the elements after reconnecting.
- Verify the user should not be able to proceed with the payment if he gets disconnected during payment.
