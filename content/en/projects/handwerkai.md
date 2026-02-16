---
title: "HandwerkerAI – AI-assisted Business Platform"
date: 2026-01-01
description: "AI-assisted platform for craft and service businesses"
tags: ["nextjs", "fullstack", "ai", "typescript", "prototype"]
weight: 2
---

**Timeline:** 2026 · **Category:** 🏠 Personal

HandwerkerAI is a private fullstack prototype I developed in 2026 to support small craft and service businesses in handling everyday administrative tasks.

The goal was to explore how AI-assisted workflows (using Claude) could simplify processes such as offer creation, customer communication, and project organization.

The project evolved into a modular platform covering customer management, offer generation, invoicing, material planning, and scheduling.

## Key Features

- **AI-assisted offer generation** — structured prompts to create professional offers
- **Email reply generation** — AI-powered response drafts for customer communication
- **Customer management system** — full CRUD with search and filtering
- **Invoice and project calculation tools** — automatic price calculations
- **Material and resource management** — track project materials and costs
- **Appointment and deadline tracking** — scheduling and calendar integration
- **Authentication and session handling** — secure login via NextAuth
- **Premium feature system** — feature gating for monetization testing

## Architecture

The system was built as a modern fullstack web application.

**Frontend**
- Next.js App Router with React + TypeScript
- TailwindCSS for styling
- Dark / Light theme support
- Responsive sidebar navigation
- Structured forms for business data entry

**Backend**
- Next.js API Routes
- Authentication via NextAuth
- AI integration via Claude API
- Structured endpoints for chat, offers, and email generation

**Data Handling**
- LocalStorage for rapid prototyping (database migration planned)
- Structured data models: Customers, Appointments, Materials, Offers, Invoice positions, Company settings

## Development Focus

The project focused on learning and experimenting with:

- Fullstack workflow design from UI to API
- Feature modularization and clean separation
- Authentication flows with NextAuth
- AI API integration patterns
- Business process modelling
- Rapid prototyping without overengineering
- UX flows for structured data entry

## Challenges & Learnings

- Designing reusable API routes for different workflows
- Structuring business data flexibly for future database migration
- Handling feature gating (premium vs free)
- Balancing UI simplicity with feature richness
- Iterating rapidly without accumulating tech debt

## Current Status

The platform remains a private prototype, but successfully demonstrates how AI features can integrate into everyday business workflows.

**Planned improvements:**
- Database persistence (PostgreSQL)
- Payment integration
- Multi-user support
- Automated testing

## Tech Stack

Next.js · React · TypeScript · TailwindCSS · NextAuth · Claude API · LocalStorage
