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
This likely indicates missing idempotency handling or lack of request protection on backend.
