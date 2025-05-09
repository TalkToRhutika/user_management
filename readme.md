# User Management System — Final Project

## Closed Issues Documentation
Issue #1 — Email Verification

Description: The email verification process was not functioning correctly due to a misconfiguration with Mailtrap. As a result, verification emails were not being delivered, and users were marked as verified without completing the verification process. This issue was resolved by correctly integrating Mailtrap, enabling the system to send verification links to registered users. Users are now marked as verified only after successfully confirming their email addresses.

Issue #2 — Admin verification handling

Descripton: The first registered user—designated as the admin—was being marked as verified automatically without completing email verification through Mailtrap. Although the system assigns admin rights to the first user, the email verification step should still be enforced to ensure account authenticity

Issue #3 - Password logic implementation

Description: The password must contain at least one digit, one special character, one uppercase letter, one lowercase letter, and be a minimum of 10 characters long.

Issue #4 - Skip and Limit Values Validation

Description: When retrieving the user list, entering negative values for skip or limit does not trigger a validation error. Instead, the API incorrectly returns a 200 OK response, which could lead to unexpected behavior or security concerns. Proper validation should be enforced to reject negative input values.

