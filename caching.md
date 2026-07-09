# Performance: Distributed Redis Caching Layer

Introduced an in-memory caching layer for heavily queried database assets 
that change infrequently, such as app configurations and product catalogs.

Drastically reduced database overhead and pulled average server response times 
down under 50ms.
