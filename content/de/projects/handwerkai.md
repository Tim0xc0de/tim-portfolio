---
title: "HandwerkerAI – KI-gestützte Business-Plattform"
date: 2026-01-01
description: "KI-gestützte Plattform für Handwerks- und Dienstleistungsbetriebe"
tags: ["nextjs", "fullstack", "ki", "typescript", "prototyp"]
weight: 99
---

**Zeitraum:** 2026 · **Kategorie:** 🏠 Privat

HandwerkerAI ist ein privater Fullstack-Prototyp, den ich 2026 entwickelt habe, um kleine Handwerks- und Dienstleistungsbetriebe bei alltäglichen administrativen Aufgaben zu unterstützen.

Das Ziel war zu erforschen, wie KI-gestützte Workflows (mit Claude) Prozesse wie Angebotserstellung, Kundenkommunikation und Projektorganisation vereinfachen können.

Das Projekt entwickelte sich zu einer modularen Plattform für Kundenverwaltung, Angebotsgenerierung, Rechnungsstellung, Materialplanung und Terminverwaltung.

## Hauptfunktionen

- **KI-gestützte Angebotserstellung** — strukturierte Prompts für professionelle Angebote
- **E-Mail-Antwortgenerierung** — KI-gestützte Antwortentwürfe für Kundenkommunikation
- **Kundenverwaltungssystem** — vollständiges CRUD mit Suche und Filterung
- **Rechnungs- und Projektkalkulationstools** — automatische Preisberechnungen
- **Material- und Ressourcenverwaltung** — Projektmaterialien und Kosten tracken
- **Termin- und Deadline-Tracking** — Planung und Kalenderintegration
- **Authentifizierung und Session-Handling** — sicherer Login via NextAuth
- **Premium-Feature-System** — Feature-Gating für Monetarisierungstests

## Architektur

Das System wurde als moderne Fullstack-Webanwendung gebaut.

**Frontend**
- Next.js App Router mit React + TypeScript
- TailwindCSS für Styling
- Dark / Light Theme Support
- Responsive Sidebar-Navigation
- Strukturierte Formulare für Geschäftsdaten

**Backend**
- Next.js API Routes
- Authentifizierung via NextAuth
- KI-Integration via Claude API
- Strukturierte Endpoints für Chat, Angebote und E-Mail-Generierung

**Datenhandling**
- LocalStorage für Rapid Prototyping (Datenbank-Migration geplant)
- Strukturierte Datenmodelle: Kunden, Termine, Materialien, Angebote, Rechnungspositionen, Firmeneinstellungen

## Entwicklungsfokus

Das Projekt fokussierte sich auf Lernen und Experimentieren mit:

- Fullstack-Workflow-Design von UI bis API
- Feature-Modularisierung und saubere Trennung
- Authentifizierungs-Flows mit NextAuth
- KI-API-Integrationsmuster
- Geschäftsprozessmodellierung
- Rapid Prototyping ohne Over-Engineering
- UX-Flows für strukturierte Dateneingabe

## Herausforderungen & Learnings

- Wiederverwendbare API-Routes für verschiedene Workflows designen
- Geschäftsdaten flexibel für zukünftige Datenbank-Migration strukturieren
- Feature-Gating handhaben (Premium vs. Free)
- UI-Einfachheit mit Feature-Reichhaltigkeit balancieren
- Schnell iterieren ohne technische Schulden anzuhäufen

## Aktueller Status

Die Plattform bleibt ein privater Prototyp, demonstriert aber erfolgreich, wie KI-Features in alltägliche Geschäftsabläufe integriert werden können.

**Geplante Verbesserungen:**
- Datenbank-Persistenz (PostgreSQL)
- Payment-Integration
- Multi-User-Support
- Automatisierte Tests

## Tech Stack

Next.js · React · TypeScript · TailwindCSS · NextAuth · Claude API · LocalStorage
