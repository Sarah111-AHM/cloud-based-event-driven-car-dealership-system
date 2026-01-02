# Microservices Design for Autosales DMS

## 1. Sales Service
![Sales Service Visualization](https://drive.google.com/uc?export=view&id=1klupgBLcucO9u4VGu_mLxuCU1hYs5NvI)
- Handles vehicle sales
- Updates Inventory Service via events
- Generates invoices

## 2. Inventory Service
## 2. Inventory Service
- Tracks all vehicles in stock
- Listens to Stock Arrival & Sales events
- Updates dashboard metrics

![Inventory Service Visualization](https://drive.google.com/uc?export=view&id=1-Wt_xgfcrCWua31Zzh6VAtp_7V9NdNis)

- Tracks all vehicles in stock
- Listens to Stock Arrival & Sales events
- Updates dashboard metrics

## 3. Customer Service
- Manages customer data
- Sends notifications for sales/service
- Integrates with AI chatbots

![Customer Service Visualization](https://drive.google.com/uc?export=view&id=1A3Wf-gHN7AavhtHMc2_0YoAMWlaTfyPw)

- Manages customer data
- Sends notifications for sales/service
- Integrates with AI chatbots
