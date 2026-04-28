# Bug Report: Duplicate Order Created on Page Refresh

## Summary
Multiple orders are created when the user refreshes the page after placing an order.

---

## Steps to Reproduce
1. Add item to cart
2. Proceed to checkout
3. Enter valid payment details
4. Click "Place Order"
5. Refresh the page immediately during processing or confirmation screen

---

## Expected Result
Only one order should be created per successful transaction.

---

## Actual Result
Duplicate orders are created when the page is refreshed during or immediately after order placement.

---

## Severity
Critical

---

## Impact
- Users may be charged multiple times
- Inventory inconsistency
- Poor user trust and financial risk
- Backend processing inconsistency under duplicate requests

---

## Notes
This issue suggests missing request idempotency or lack of proper handling of page refresh during transaction processing. It should be handled at backend level to prevent duplicate submissions.
