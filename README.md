AI Table Booking Agent

Overview
This project is an AI-powered table booking assistant built using n8n, Google Gemini, and Google Sheets.

The system uses a conversational AI agent to process booking requests, interpret natural language inputs, and record confirmed reservations directly into Google Sheets.

Problem Solved
Restaurants often rely on manual booking management, which leads to errors, missed entries, and slow response times.

This AI agent automates booking handling using intelligent language understanding without requiring complex backend infrastructure.

How It Works
1. User submits a booking request (chat-based interaction)
2. Google Gemini interprets the request (date, time, number of guests)
3. AI validates structured booking details
4. Booking data is written to Google Sheets
5. Restaurant staff can manage reservations from the sheet

Key Features
- Natural language understanding via Google Gemini
- Automated structured data extraction
- Google Sheets as live booking database
- Low infrastructure setup
- Scalable for small and mid-size restaurants

Tech Stack
- n8n (workflow automation)
- Google Gemini (AI agent)
- Google Sheets (data storage)

Architecture
AI Agent → Data Structuring → Google Sheets Database

Potential Extensions
- Availability validation logic
- SMS or WhatsApp confirmations
- Calendar sync
- Multi-location support
- CRM integration

Use Case
Designed for restaurants seeking a lightweight AI-powered booking solution without custom backend development.
