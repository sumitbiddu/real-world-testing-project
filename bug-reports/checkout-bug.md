# Bug Report: Duplicate Order Created on Page Refresh

## Steps to Reproduce
1. Add item to cart
2. Proceed to checkout
3. Enter valid payment details
4. Click "Place Order"
5. Refresh the page immediately

## Expected Result
Only one order should be created

## Actual Result
Multiple orders are created for a single transaction

## Severity
Critical

## Impact
- User may be charged multiple times
- Inventory mismatch risk
- Poor user trust experience

## Notes
This issue was identified during exploratory testing of the checkout flow. It appears under real user behavior such as refreshing the page during payment processing, which is a common scenario in production environments.
