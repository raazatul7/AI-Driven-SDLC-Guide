# SCALABILITY_PLAYBOOK.md

---

# When to Introduce Caching

- Frequent read-heavy endpoints
- Repeated database queries

Use:
- Redis
- CDN

---

# When to Introduce Queue System

- Email processing
- Payment confirmation
- Heavy background jobs

Use:
- BullMQ
- RabbitMQ
- Kafka

---

# When to Split Microservices

Only when:
- Independent scaling needed
- Clear bounded contexts
- Team scaling required

---

# Database Scaling

- Index optimization
- Read replicas
- Sharding (high scale only)

---

# Performance Metrics

- API < 300ms
- P95 latency defined
- CPU threshold monitoring
