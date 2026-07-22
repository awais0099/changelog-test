# Bugfix: Unbounded External Request Deadlocks

Wrapped external third-party communication layers in strict timeout wrappers and circuit-breaker conditions.

Prevents slowed downstream tracking partners from consuming internal connection threads and causing service delays.
