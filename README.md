# Fault-tolerance---Microservices
@circuit breaker(name, fallbackmethod), @Retry(name), RateLimiter(name). The Circuit Breaker pattern is like a safety switch for microservices. If that service starts failing repeatedly, the circuit breaker “trips” and stops further calls for a while, preventing cascades and giving the service time to recover.
