# Exploratory Testing Session – Checkout Flow

## Objective
Explore the checkout process without predefined test cases to identify real user behavior risks and system weaknesses.

---

## Approach
I tested the flow by intentionally behaving like a real user instead of following structured test cases. This included refreshing pages, navigating back and forth, and simulating interruptions during payment.

---

## Observations

- No clear loading indicator during payment processing
- Page refresh during checkout can lead to inconsistent system behavior
- Multiple rapid actions on checkout button may cause unexpected results
- Error handling is not always user-friendly or clear

---

## Risks Identified

- Duplicate transactions under abnormal user behavior
- Poor user experience during slow network conditions
- Lack of protection against repeated submissions
- Unclear system state during payment processing

---

## Conclusion
The system works correctly under normal conditions, but shows potential instability under real-world unpredictable user behavior. These scenarios are important for production reliability.
