# Project Scope

## Problem

Customer-service teams receive interactions through multiple disconnected channels.
This makes it difficult to understand the full customer journey, identify recurring
issues, evaluate agent performance, and act before problems escalate.

## Solution

Build an analytics and AI platform that consolidates omnichannel contact-centre data
and converts it into operational and customer-experience insights.

## In Scope

- Voice, chat, email, chatbot, and social-media interaction analysis
- Intent classification and topic discovery
- Sentiment analysis and dissatisfaction detection
- Contact-centre KPI dashboards
- Escalation-risk prediction
- Contact-volume forecasting
- Conversation summarization

## Out of Scope for Version 1

- Live production telephony integration
- Real-time streaming at enterprise scale
- Full speech-to-text pipeline for all audio files
- Commercial deployment

## Success Criteria

- A reproducible pipeline processes multi-channel data end to end.
- The dashboard presents at least 10 meaningful contact-centre KPIs.
- NLP models classify intents and sentiment with documented evaluation metrics.
- At least one predictive model is trained, evaluated, and versioned.
- The project can be launched locally using Docker Compose.