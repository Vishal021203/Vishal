# Smart Home Energy Monitoring System

This project provides a comprehensive solution for monitoring and analyzing energy usage in a smart home environment. It consists of frontend dashboard work to collect, analyze, and visualize energy consumption data.

## 🔍 Project Overview

The Smart Home Energy Monitoring System allows homeowners to:

- Track real-time energy consumption across all connected devices
- Visualize energy usage patterns over time
- Set energy budgets and receive alerts when exceeded
- Identify abnormal energy consumption patterns
- Calculate energy costs based on different rate structures

## 🏗️ Architecture

The system is built with a modern, scalable architecture:

```
┌───────────────┐           ┌───────────────┐           ┌───────────────┐
│  Smart Home   │           │   Backend     │           │   Frontend    │
│   Devices     │ ◄─────────┤     API       │ ◄─────────┤  Dashboard    │
│ (IoT Sensors) │   MQTT    │  (Node.js)    │   REST    │   (React)     │
└───────────────┘           └───────────────┘           └───────────────┘
                                    ▲
                                    │
                                    ▼
                            ┌───────────────┐
                            │   Database    │
                            │  (MongoDB)    │
                            └───────────────┘
```
## 🚀 Frontend Features

The dashboard is built with React and provides:

- **Interactive Data Visualization**: Charts showing energy use patterns
