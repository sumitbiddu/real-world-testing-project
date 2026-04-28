# Login Test Scenarios

## Objective
Validate login functionality under normal, negative, and edge conditions to ensure system reliability and proper validation handling.

---

## Functional Scenarios
- User logs in with valid credentials → successful login
- Invalid password → appropriate error message displayed
- Invalid username → login denied with error message
- Empty fields → validation messages shown

---

## Negative Scenarios
- SQL injection attempt in username field
- Script injection in input fields
- Invalid email format (if email-based login exists)
- Special characters in credentials

---

## Edge Cases
- Very long username/password inputs
- Rapid multiple login attempts
- Copy-paste password validation issues
- Session handling after repeated failed attempts

---

## Observations
Login functionality behaves correctly under standard inputs, but should ensure stronger validation against injection attempts and repeated failure handling.
