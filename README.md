# Calendar Assistant
An AI-powered daily planning assistant built with n8n that turns calendar events and email context into a personalized morning briefing, helping users understand what matters most each day.

## Overview

Calendar Assistant helps users start their day with a clear understanding of what matters most.

The workflow runs automatically at a scheduled time each morning, retrieves relevant calendar and email information, and uses an AI agent to generate a personalized daily briefing.

## Problem

Important meetings, events, and email context are often spread across different productivity tools.

This creates friction when trying to answer a simple question:

**"What do I actually need to focus on today?"**

## Solution

Calendar Assistant brings this information together and generates a concise morning briefing containing the user's important meetings, events, and priorities.

## How It Works

Schedule Trigger
↓
AI Agent
↓
Google Calendar + Gmail
↓
AI-generated daily briefing
↓
Email

## Key Features

- Automated morning briefing
- Google Calendar integration
- Gmail integration
- AI-powered prioritization
- Scheduled workflow execution
- Customizable briefing logic

## Tech Stack

- n8n
- AI Agent
- Groq
- Google Calendar
- Gmail

## Workflow

The complete n8n workflow is available in:

`CalendarAssistant.json`

## Product Perspective

The workflow focuses on reducing the effort required to understand a user's day by bringing fragmented productivity information into one personalized briefing.

## Note

This repository contains the exported n8n workflow. Credentials and sensitive configuration should be configured separately inside n8n according to individual preference and life choices.

