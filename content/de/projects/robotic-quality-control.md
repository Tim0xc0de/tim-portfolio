---
title: "Automatisiertes Roboter-Qualitätskontrollsystem"
date: 2026-02-01
description: "Robotik, Computer Vision und REST API für automatisierte Inspektion"
tags: ["robotik", "python", "opencv", "fastapi", "automatisierung"]
weight: 5
---

**Zeitraum:** Februar 2026 - April 2026 (voraussichtlicher Abschluss) · **Kategorie:** 🎓 Weiterbildung

Als Teil meines technischen Abschlussprojekts entwickle ich (Februar - April 2026) ein automatisiertes Roboter-Qualitätskontrollsystem, das Robotik, Computer Vision und Backend-API-Design kombiniert.

Dieses Projekt dient als Abschlussprojekt meiner technischen Ausbildung.

Das System führt objektive und reproduzierbare Qualitätsinspektionen von konfigurierbaren 3D-gedruckten Würfeln durch.

Es integriert Robotik, Bildverarbeitung und REST-basierte Systemarchitektur in einen einheitlichen Workflow.

## Systemziele

Das Projekt automatisiert die komplette Inspektions-Pipeline:

- Ein Roboterarm handhabt automatisch fertige Teile
- Ein kamerabasiertes Bilderkennungssystem erkennt Konfigurationsdetails
- Bilddaten werden mit OpenCV analysiert
- Erkannte Werte werden mit erwarteten JSON-Konfigurationen verglichen
- Teile werden automatisch basierend auf Inspektionsergebnissen sortiert
- Alle Ergebnisse werden in einer Datenbank protokolliert
- Eine REST API stellt Inspektionsdaten für externe Systeme bereit

## Architektur & Module

Das System ist in modulare Komponenten unterteilt:

**Konfigurationsmodul**
- JSON-basiertes Konfigurationssystem
- API-gesteuerte Parameterübergabe
- Unabhängige Testbarkeit

**Robotik-Modul**
- Automatisiertes Greifen und Positionieren
- Reproduzierbare Kameraausrichtung
- Sortierung basierend auf Inspektionsergebnissen

**Computer Vision Modul**
- OpenCV-basierte Bildanalyse
- HSV-Farberkennung
- Feature-Erkennung
- Strukturierte Datenextraktion

**Vergleichs-Engine**
- Automatisierte Validierung von Soll- vs. Ist-Werten
- Deterministische Inspektionsergebnisse

**Logging-System**
- SQLite-Datenbankspeicherung
- Zeitgestempelte Inspektionshistorie
- Nachvollziehbare Qualitätsprotokolle

**REST API Layer**
- FastAPI Backend
- JSON-Endpoints für externe Integration
- Systeminteroperabilität

## Engineering-Fokus

Behandelte Engineering-Herausforderungen:

- Zuverlässige Roboterpositionierung
- Reproduzierbare Bildaufnahme
- Computer Vision Genauigkeit (>95%)
- Modulare Softwarearchitektur
- API-basierte Systemintegration
- Hardware-Software-Interaktion
- Systemsicherheit und Fehlerbehandlung

## Ergebnisse & Impact

Das Projekt demonstriert:

- Integration von Robotik und Backend-Software
- Praktische Computer Vision Implementierung
- Modulare Systemarchitektur
- Automatisierte Qualitätssicherungs-Workflows
- Industrielle Automatisierungskonzepte
- Skalierbares API-basiertes Design

## Demonstrierte Skills

- Robotik-Programmierung
- Computer Vision Engineering
- Backend API-Entwicklung
- Systemarchitektur-Design
- Hardware-Software-Integration
- Automatisierungs-Engineering
- Strukturierte Projektplanung

## Tech Stack

**Software:** Python 3.11 · FastAPI · OpenCV · SQLite · JSON · Git

**Hardware:** Niryo Ned2 Roboterarm · USB-Kamera · Kontrollierte Beleuchtung · Custom Fixtures
