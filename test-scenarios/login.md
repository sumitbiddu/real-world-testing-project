
# Login Test Scenarios

While testing login functionality, I focused on both expected and unexpected user behavior.

## Functional Scenarios
- User logs in with valid credentials → dashboard opens
- Invalid password → error message displayed
- Empty fields → validation message shown

## Negative Scenarios
- SQL injection attempt in username field
- Special characters in inputs
- Invalid email format

## Edge Cases
- Very long username/password
- Multiple failed login attempts
- Copy-paste password issues

## Observations
Error messages should be clear and consistent. In some cases, response time was slightly delayed under repeated login attempts.
