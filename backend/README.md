# Backend - Decision-Consequence Agent Engine

This directory contains the core backend services, agent reasoning loops, impact modeling logic, and API endpoints.

## Structure
- `api/`: REST/WebSocket API endpoints.
- `agent/`: Decision-making and consequence reasoning engine.
- `models/`: Domain data schemas and impact assessment algorithms.
- `services/`: External integrations and state management.

## Getting Started
```bash
# From repository root
pip install -r requirements.txt
uvicorn backend.main:app --reload --port 8000
```
