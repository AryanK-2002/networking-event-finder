# Networking Event Finder

## Overview :

Networking Event Finder is an AI-powered event discovery and intelligence system that automatically finds, filters, ranks, and summarizes high-quality networking events happening across Mumbai.

The platform aggregates events from multiple sources, extracts key information, removes duplicates, evaluates relevance and generates concise recommendations for students, professionals, founders, investors and startup enthusiasts.

---

## Problem Statement :

Finding valuable networking events is often a manual and time-consuming process. Event information is scattered across multiple websites, communities, and platforms, making it difficult to identify the most relevant opportunities.

Users typically spend significant time:

- Searching multiple event platforms
- Filtering irrelevant events
- Comparing opportunities
- Tracking registration links
- Staying updated on upcoming events

This project automates the entire event discovery workflow.

---

## Solution :

The system continuously discovers networking events from multiple online sources and uses AI to generate curated recommendations.

### Workflow

1. Search for networking events across multiple sources
2. Extract event information from event pages
3. Filter out irrelevant results
4. Remove duplicate events
5. Rank events based on networking value
6. Generate AI-powered summaries
7. Deliver a curated event report

---

## Key Features :

### Automated Event Discovery

- Multi-source event aggregation
- Automated web search
- Event information extraction
- Continuous event monitoring

### Intelligent Filtering

- Relevance-based filtering
- Duplicate detection
- Event categorization
- Noise reduction

### AI-Powered Ranking

Events are evaluated based on:

- Networking potential
- Audience quality
- Startup relevance
- Professional value
- Learning opportunities
- Community engagement

### Automated Event Intelligence

For every event, the system generates:

- Event summary
- Key highlights
- Target audience
- Networking opportunities
- Registration details
- Recommendation score

---

## Workflow Architecture :

```text
Data Sources
     │
     ▼
Serper Search API
     │
     ▼
Firecrawl Web Extraction
     │
     ▼
Event Information Processing
     │
     ▼
AI Analysis & Filtering
     │
     ▼
Event Ranking Engine
     │
     ▼
Summary Generation
     │
     ▼
Curated Event Report
```

---

## Tech Stack :

| Category | Technology |
|-----------|-----------|
| Workflow Automation | n8n |
| Search Engine | Serper API |
| Web Crawling | Firecrawl |
| AI Processing | OpenAI GPT |
| Data Transformation | JavaScript |
| Notifications | Gmail |


---

## System Components :

### Event Search Layer

Responsible for discovering networking events from online sources using automated search workflows.

### Event Extraction Layer

Extracts structured event information including:

- Event name
- Date and time
- Venue
- Description
- Registration link
- Organizer information

### AI Processing Layer

Uses Large Language Models to:

- Analyze event relevance
- Rank opportunities
- Generate summaries
- Improve recommendation quality

### Reporting Layer

Creates a clean and readable report containing:

- Top recommendations
- Event insights
- Networking opportunities
- Registration details

---

## Example Output :

### Top Recommendations

#### Startup Networking Mixer

**Why Attend ?**

- Strong founder presence
- Startup ecosystem exposure
- Networking opportunities with investors

#### Product & Growth Meetup

**Why Attend ?**

- Product management discussions
- Industry networking
- Practical learning sessions

#### Entrepreneur Community Event

**Why Attend ?**

- Founder networking
- Business collaboration opportunities
- Community building

---

## Use Cases :

### Students

- Discover career-focused events
- Attend startup meetups
- Build professional networks
- Explore industry opportunities

### Founders

- Connect with investors
- Meet potential partners
- Explore startup communities
- Discover collaboration opportunities

### Professionals

- Expand industry connections
- Attend workshops and conferences
- Stay updated with industry trends

### Investors

- Discover startup events
- Identify emerging founders
- Explore networking opportunities

---

## Benefits :

- Reduces manual event research effort
- Improves event discovery efficiency
- Identifies high-value networking opportunities
- Provides structured event intelligence
- Delivers actionable recommendations

---

## Future Enhancements :

- Personalized event recommendations
- WhatsApp notifications
- Calendar integration
- Location-aware recommendations
- Event attendance prediction
- AI-based networking matchmaking
- Multi-city expansion
- User preference learning

---


