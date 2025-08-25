# FruitVendor AI – Inventory Manager

An AI-powered inventory manager for fruit vendors, built using **n8n**, **Google Gemini API**, and **Google Sheets**.  
This hosted AI agent can read, update, and analyze your fruit inventory in real time.

---

## Features

- **AI-driven inventory management** using Google Gemini  
- **Google Sheets integration** as the live database  
- **Hosted on n8n** – no local setup required  
- **Natural language interface** – ask things like:
  - *"How many apples do I have?"*
  - *"Update banana stock to 120."*
  - *"Show me low-stock fruits."*

---

## Tech Stack

- **n8n** (workflow automation + hosting)
- **Google Gemini API** (AI reasoning and conversation)
- **Google Sheets API** (real-time data storage)

---

## Workflow Overview

1. **Trigger** – AI agent receives a user query.  
2. **Gemini API** – Processes the request and determines intent.  
3. **Google Sheets Node** – Reads or updates inventory data.  
4. **AI Response** – Sends the user an intelligent reply.

---

## Setup Instructions

1. **Clone this repository**  
   ```bash
   git clone https://github.com/your-username/fruitvendor-ai.git
   cd fruitvendor-ai
