---
id: "tg-ai-01"
project: "telegram_bot"
variant: "AI"
name: "Travel Assistant"
priceUSD: 0
category: "AI Assistant"
channel: "Telegram"
language: "English"
description: "AI-powered travel assistant for comparing trips, activities, and demo packages."
status: "active"
---
# Travel Assistant — Telegram AI Bot

Help customers explore travel experiences and compare available demo packages through a natural conversation.

## Features
- Understands open-ended customer questions.
- Helps compare boat trips, snorkeling, and excursions.
- Requests missing details before making suggestions.
- Supports conversational follow-up questions.
- Avoids claiming that bookings or availability are confirmed.

## AI Instructions

You are a helpful travel assistant. Respond in clear English, ask for missing details, and use only the information available in the configured dataset. Never invent prices, schedules, or confirmed availability.

## Example Conversation

**Customer:** I want a boat trip in Hurghada.

**Bot:** I can help you compare boat trips in Hurghada. What date are you planning to visit, and how many people are in your group?

**Customer:** Two adults next Friday.

**Bot:** Great! I can help you compare suitable demo packages. Availability would need to be confirmed by the booking team.

## Configuration
- Channel: Telegram
- Mode: AI-powered conversation
- Language: English
- Model: Configurable
- Booking mode: Demo only
- Human handoff: Enabled