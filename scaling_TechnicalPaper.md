
# Scaling

Scaling improves a system's capacity to handle increased load by adjusting resources. It can be achieved through Vertical Scaling and Horizontal Scaling.

## 1. Vertical Scaling (Scaling Up)
Involves upgrading a machine’s hardware (e.g., CPU, RAM).

### Advantages
- Simple to implement.
- Avoids data synchronization challenges.

### Disadvantages
- Limited by hardware constraints.
- Expensive and may cause downtime.

### Use Cases
- Monolithic applications or predictable workloads.

### Example
- Adding more RAM to a server to enhance performance.

## 2. Horizontal Scaling (Scaling Out)
Adds machines and distributes the workload across them.

### Advantages
- Scalable without upper limits.
- High availability through redundancy.

### Disadvantages
- Requires load balancers and distributed management.
- Challenges with data consistency and network latency.

### Use Cases
- Distributed systems, microservices, or fluctuating workloads.

### Example
- Adding servers behind a load balancer for traffic spikes.

## Load Balancers
- Types: Layer 4 (IP-based) and Layer 7 (application-level).
- Benefits: Distributes traffic, detects failures, and ensures scalability.

## Conclusion
- Start with horizontal scaling, optimize with vertical scaling, and monitor using tools like Prometheus or AWS CloudWatch.

### References

- https://aws.amazon.com/autoscaling/
- https://learn.microsoft.com/en-us/azure/load-balancer/
- https://www.geeksforgeeks.org/system-design-horizontal-and-vertical-scaling/