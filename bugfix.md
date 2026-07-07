# Bug Fix: Session Expiry

Fixed a crash that occurred when a user's session expired
while they were actively using the dashboard.

Previously the app would throw an unhandled exception.
Now it gracefully redirects to the login page.
