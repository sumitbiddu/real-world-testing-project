This exploratory session was performed without predefined test cases to simulate real user behavior and uncover unexpected system issues.


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
