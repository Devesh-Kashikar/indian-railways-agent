# indian-railways-agent

# 🤖 AI Agents using Cursor AI + Pipedream

This repository contains two AI agents built using [Cursor AI](https://www.cursor.so/) and [Pipedream](https://pipedream.com/) that demonstrate real-world automation using natural language processing and API integration.

---

## 🚀 Projects Overview

### 1. Indian Railways Info Agent
An AI agent that provides real-time Indian Railways data such as:
- Train schedules
- PNR status
- Seat availability
- Station codes and timings

🔧 **How it works**:
- User enters a natural language query like:  
  *"When does train 12951 reach Mumbai?"*
- Cursor AI processes the input and sends a request via Pipedream to Indian Railways APIs.
- The API response is parsed and returned in a human-friendly format.

💡 **Tech Used**:
- Cursor AI (Prompt logic, NLP handling)
- Pipedream (Serverless integration)
- Indian Railways API (Live train data)
