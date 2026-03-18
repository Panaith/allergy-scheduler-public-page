# Allergy Scheduler

A production-ready Flutter and Firebase application for meticulous tracking of allergen administration and dosage history.

## 🚀 Overview

Allergy Scheduler is designed for patients on active medical protocols who need to track precise dosages, health status, and reactions in real-time. It provides healthcare providers and patients with a unified view of historical data through denormalized tables and professionally generated PDF reports.

### ✨ Key Features

- **Real-time Tracking**: Log doses with health, medication, and reaction statuses.
- **Sequential Worker Queue**: High-consistency backend processing for dosage groups and statistics.
- **Smart Analytics**: Aggregated usage statistics (yearly, monthly, daily) with interactive charts.
- **Automated Scheduling**: end-of-day "Day Off" dose creation and smart countdown notifications for next allowed dose.
- **Multi-user Access**: RBAC membership system allowing doctors and caregivers to view patient data.
- **Premium Reporting**: Professional PDF exports for dosage history and usage stats (M3 Design).
- **Cross-Platform**: Full support for Android, iOS, macOS, Windows, and Web.

### 🛠️ Tech Stack

- **Frontend**: Flutter (Provider, Equatable, json_serializable)
- **Backend**: Firebase Cloud Functions (TypeScript), Firestore, FCM, Auth
- **Infrastructure**: Firebase Local Emulator Suite for local development
- **Subscription**: RevenueCat for multi-platform premium entitlement management
- **CI/CD**: GitHub Actions for automated testing, deployment, and project management

---

## 📚 Documentation

The project's documentation is divided into specialized files to ensure clear boundaries and ease of use:

- 🪄 **[SETUP.md](SETUP.md)**: Local environment setup, operational commands, and troubleshooting for developers.
- ⚙️ **[DEVELOPMENT.md](DEVELOPMENT.md)**: The technical source of truth. Details on architecture, design patterns, folder structure, and technical guidelines.
- 👁️ **[AGENTS.md](AGENTS.md)**: AI agent-specific memory, behavioral rules, and major architectural decisions.
- 📖 **[USER_MANUAL.md](USER_MANUAL.md)**: End-user guide for patients and staff. Features, subscription tiers, and app flows.

---
*Maintained by the Allergy Scheduler Team.*
