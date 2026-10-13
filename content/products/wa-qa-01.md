---
id: "wa-qa-01"
project: "whatsapp_bot"
variant: "QA"
name: "Availability FAQ"
priceUSD: 0
category: "FAQ"
channel: "WhatsApp"
language: "English"
description: "Provides predefined answers about trip availability and date requests."
status: "active"
---
# Availability FAQ — WhatsApp QA Bot

Give customers quick answers about trip availability using predefined responses.

## Features
- Answers frequently asked availability questions.
- Collects preferred travel dates.
- Explains that live availability is not connected.
- Directs customers to the booking team when needed.

## Example Conversation

**Customer:** Is this trip available tomorrow?

**Bot:** Availability is not live in this demo. Send your preferred date so the team can review it.

**Customer:** Can you reserve two places?

**Bot:** I can help you prepare a booking request, but this demo cannot confirm reservations.

## Behavior
- Match incoming messages to the availability FAQ.
- Return the approved response.
- Avoid promising availability without a live booking integration.
- Escalate requests that require manual confirmation.

## Configuration
- Channel: WhatsApp
- Mode: Question and Answer (QA)
- Language: English
- Human handoff: Enabled

4. WhatsApp bot — AI variant

File: wa-ai-01.md
markdown


---
id: "wa-ai-01"
project: "whatsapp_bot"
variant: "AI"
name: "Booking Concierge"
priceUSD: 0
category: "AI Assistant"
channel: "WhatsApp"
language: "English"
description: "Conversational booking assistant that helps customers explore trips and beach experiences."
status: "active"
---
# Booking Concierge — WhatsApp AI Bot

Help customers find suitable demo packages through a friendly WhatsApp conversation.

## Features
- Understands natural-language booking requests.
- Recommends packages based on customer preferences.
- Collects destination, date, and group size.
- Answers follow-up questions using configured package data.
- Escalates booking requests that require confirmation.

## AI Instructions

You are a concise and friendly booking assistant. Ask for the destination, preferred date, and group size before recommending packages. Use only configured information. Never claim that a reservation, payment, or availability is confirmed.

## Example Conversation

**Customer:** I want a beach day for my family.

**Bot:** Happy to help! Are you looking for a beach day on the North Coast, and how many adults and children will be joining?

**Customer:** Two adults and one child.

**Bot:** I can compare the demo beach packages and their child pricing. Your preferred date will help the team check availability.

## Configuration
- Channel: WhatsApp
- Mode: AI-powered conversation
- Language: English
- Tone: Concise and friendly
- Model: Configurable
- Booking mode: Demo only