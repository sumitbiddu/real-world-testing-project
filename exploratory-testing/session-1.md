# Exploratory Testing Session - Checkout Flow

## Objective
Understand system behavior beyond predefined test cases.

## Observations
- No loading indicator during payment processing
- Refreshing during payment causes inconsistent behavior
- System does not clearly prevent double submission

## Risks Identified
- Duplicate transactions
- User confusion during slow network conditions
- Backend inconsistency in order handling

## Suggestions
- Add loading indicator during processing
- Disable button after first click
- Implement duplicate request prevention
