# Kafka Setup for Event-Driven Architecture

## 1. Topics
- sales-events
- inventory-events
- service-events

## 2. Producers
- Sales Service → sales-events
- Inventory Service → inventory-events

## 3. Consumers
- Analytics Service listens to all events
- Dashboard Service listens to relevant events

## 4. Reliability
- Replication factor = 3
- Partitioning for scalability
