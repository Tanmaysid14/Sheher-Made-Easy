# Design Document
# AI-Powered Smart Pune Travel & Public Access Assistant
# Project: Sheher Made Easy

## 1. Problem Overview

Citizens and tourists in Pune face difficulty accessing unified information about public transport, navigation, tourist attractions, and emergency services. Information is scattered across multiple platforms, leading to confusion, inefficiency, and reduced accessibility, especially for first-time visitors and users in low-bandwidth environments.

## 2. Proposed Solution

Sheher Made Easy is an AI-powered smart city assistant that integrates transport systems, tourist guidance, local essentials, and safety features into a single unified platform.
The system uses AI to provide intelligent navigation, route optimization, personalized travel planning, multilingual support, and emergency assistance.

## 3. Key Features

### 3.1 Navigation & Transport
- Smart navigation and route search
- Bus route and stops information
- Metro routes and station details
- Fare calculator (bus + metro)
- Ticket booking interface (UI prototype)
- Multi-modal route suggestions (Bus + Metro + Walk)

### 3.2 Tourist Spots Explorer
- Popular tourist spots listing
- Nearby attractions suggestions
- Entry fees and timings
- Best visiting hours
- Estimated visit duration

### 3.3 Local Essentials
- Nearby hospitals
- Police stations
- ATMs
- Public emergency contact numbers

### 3.4 Safety Features
- Dedicated Safety Mode
- Safe route suggestion at night
- Avoid low-lit or potentially unsafe areas
- Emergency quick-access button
- Emergency contact directory

### 3.5 Lost Tourist Rescue Feature
- “I’m Lost” quick option
- Detects current location
- Step-by-step guided navigation
- Nearest safe location suggestion

### 3.6 Accessibility & Inclusion
- Multi-language support
- Low-bandwidth optimized mode
- Lightweight text-based interface option

## 4. AI Integration

AI is the core intelligence layer of the system.

### 4.1 AI Travel Assistant
- Understands natural language queries
- Example: “How do I reach XYZ from ABC the cheapest way?”
- Combines Bus + Metro routes
- Simplifies public transport decisions

### 4.2 AI City Guide Chat
- Answers travel-related queries
- “Is metro available late night?”
- “Which bus goes to airport?”
- “Suggest places near me”

Acts as a conversational city concierge.

### 4.3 AI Trip Planner
- Personalized itinerary generation
- Example: “Plan a 1-day Pune trip under ₹800”
- Budget + time-based optimization

### 4.4 AI Accessibility Assistant
- Suggests routes with minimal walking
- Senior-friendly recommendations
- Simplified step-by-step instructions

### 4.5 AI Emergency Helper
- Example: “I got robbed”
- Suggests nearest police station
- Provides emergency contacts
- Guides user on immediate next steps

AI converts structured city data into an intelligent real-time assistant.

## 5. System Architecture

### Components

1. Frontend
   - Mobile-friendly web interface
   - Chat-based AI interface
   - Navigation dashboard

2. Backend Server
   - API handling
   - Query processing
   - Route calculation logic

3. Database
   - Bus route data
   - Metro data
   - Tourist places
   - Local essentials
   - Safety contact data

4. AI Module
   - Natural language processing
   - Query interpretation
   - Intelligent recommendation engine
   - Personalized planning logic

## 6. System Flow

User → Frontend  
Frontend → Backend Server  
Backend → Database + AI Module  
AI + Structured Data → Optimized Response  
Response → Frontend → User


## 7. Technology Stack

Frontend:
- HTML, CSS, JavaScript

Backend:
- Python (Flask)

Database:
- JSON / SQLite

AI:
- LLM API integration

Cloud:
- AWS (for deployment & scalability)

## 8. Future Enhancements

- Real-time bus tracking
- Live crowd density estimation
- Official ticket booking API integration
- Offline AI functionality
- Full voice assistant support
- Predictive safety alerts

## 9. Conclusion

Sheher Made Easy aims to simplify urban mobility and public access in Pune by combining structured city data with AI-driven intelligence. The solution enhances accessibility, safety, and usability while promoting inclusive smart city development aligned with the AI for Bharat vision.