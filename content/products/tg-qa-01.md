---
id: "tg-qa-01"
project: "telegram_bot"
variant: "QA"
name: "Booking FAQ"
priceUSD: 0
category: "FAQ"
channel: "Telegram"
language: "English"
description: "Answers common booking questions using predefined responses."
status: "active"
---
# Booking FAQ — Telegram QA Bot

Help customers understand how to book trips and activities through Telegram.

## Features
- Answers predefined booking questions.
- Provides consistent, approved responses.
- Supports English-language inquiries.
- Escalates requests that need human assistance.

## Example Conversation

**Customer:** How do I book?

**Bot:** Choose a package and send your preferred date and group size.

**Customer:** Can I speak to someone?

**Bot:** I can help connect you with the support team.

## Behavior
- Match incoming messages against configured questions and keywords.
- Return the associated predefined answer.
- Escalate unmatched questions instead of inventing information.

## Configuration
- Channel: Telegram
- Mode: Question and Answer (QA)
- Language: English
- Human handoff: Enabled