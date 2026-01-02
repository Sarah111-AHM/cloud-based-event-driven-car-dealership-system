# Microservices Design for Autosales DMS

## 1. Sales Service
- Handles vehicle sales
- Updates Inventory Service via events
- Generates invoices

## 2. Inventory Service
- Tracks all vehicles in stock
- Listens to Stock Arrival & Sales events
- Updates dashboard metrics

## 3. Customer Service
- Manages customer data
- Sends notifications for sales/service
- Integrates with AI chatbots
