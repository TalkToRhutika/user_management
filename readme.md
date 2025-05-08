# User Management System — Final Project

## Closed Issues Documentation
Issue #1 — Email Verification

Description:
The email verification process was not functioning correctly due to a misconfiguration with Mailtrap. As a result, verification emails were not being delivered, and users were marked as verified without completing the verification process.


Resolution: This issue was resolved by correctly integrating Mailtrap, enabling the system to send verification links to registered users. Users are now marked as verified only after successfully confirming their email addresses.

Issue #2 — 
Title: Admin verification handling

Descripton: The first registered user—designated as the admin—was being marked as verified automatically without completing email verification through Mailtrap. Although the system assigns admin rights to the first user, the email verification step should still be enforced to ensure account authenticity.

Resolution: 
