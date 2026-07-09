# Feature: JWT Revocation & Redis Blacklisting

Implemented a token blacklisting mechanism using Redis to handle instant 
user logouts and session invalidation.

When a user logs out, their valid token is cached in Redis with a 
time-to-live (TTL) matching the remaining token expiration window. 
Subsequent requests check this blacklist before authorizing.
