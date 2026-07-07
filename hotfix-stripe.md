# Hotfix: Stripe Webhook Timeout Patch

Fixed a critical issue where the payment confirmation webhook 
timed out because it was awaiting a synchronous database update.

Moved the database entry to an asynchronous background task 
to instantly return a 200 OK response to Stripe.
