---
title: ".NET Migration"
date: 2025-01-01
description: "Legacy .NET Framework → modernes .NET"
tags: ["dotnet", "migration"]
weight: 1
---

**Zeitraum:** 2025 · **Kategorie:** 💼 Beruflich

Im Laufe des Jahres 2025 migrierte ich mehrere Utility-Anwendungen von **.NET Framework 4.x** auf **.NET 9** mit stabilen Rollouts über DEV, QA und PROD Umgebungen.

Dies war eine kritische Modernisierungsmaßnahme, die zentrale Business-Utilities betraf, die jahrelang auf Legacy-Frameworks liefen.

## Die Ausgangslage

Mehrere interne Utility-Anwendungen liefen seit Jahren auf .NET Framework 4.x. Sie funktionierten, aber die Wartung wurde zunehmend aufwändig — veraltete Dependencies, Sicherheitsbedenken, und das Wissen, dass Microsofts Fokus längst auf modernem .NET lag.

Die Herausforderung: migrieren ohne etwas kaputt zu machen, während die Anwendungen in Production weiterlaufen.

## Was ich gemacht habe

**Analyse & Planung**
- Audit aller Dependencies und Identifikation von Migrations-Blockern
- Kompatibilitätsmatrix für Third-Party-Libraries erstellt
- Phasenweisen Rollout geplant um Risiken zu minimieren

**Technische Umsetzung**
- Projekte auf SDK-Style Format umgestellt
- Veraltete APIs durch moderne Äquivalente ersetzt
- NuGet-Pakete aktualisiert und Versionskonflikte gelöst
- Saubere Dependency Injection Patterns implementiert
- Konfiguration modernisiert (appsettings.json, Options Pattern)

**Rollout & Validierung**
- Gestaffeltes Deployment: DEV → QA → PROD
- Umfassende Regressionstests in jeder Phase
- Performance-Benchmarking um Regressionen zu erkennen
- Alle Änderungen für zukünftige Wartung dokumentiert

## Ergebnisse

- **40% schnellere Build-Zeiten** — SDK-Style Projekte und verbessertes Tooling
- **Vereinfachte Deployments** — Single-File Publishing, sauberere CI/CD
- **Zukunftssicher** — bereit für .NET 8, 9 und darüber hinaus
- **Bessere Wartbarkeit** — moderne Patterns, sauberere Code-Struktur

## Tech Stack

C# · .NET 6/8 · ASP.NET Core · MSBuild · NuGet · Azure DevOps · Git
