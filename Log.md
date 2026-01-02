# Changelog

All notable changes to **Voltamind** will be documented in this file.

This project follows a pragmatic, engineering-driven evolution rather than
a marketing-driven release cycle. Versions reflect **conceptual maturity**
and **usage governance**, not feature count.

---

## [1.0.0] – Core Doctrine & Governance Lock
**Status:** Early Commercial / EDU-Ready  
**Date:** 2026-01

### Added
- Voltamind Core Doctrine v1.0 (internal standard)
- Clear definition of system purpose: decision-support, not decision-making
- Role-based access control (Free / Pro / EDU)
- Policy layer before AI execution (AI Gateway)
- VERSL (Voltamind Educational & Research Software License) v1.0
- Explicit usage boundaries and responsibility disclaimers
- Export disclaimer aligned with AI & simulation limitation

### Changed
- AI usage moved behind authorization and purpose checks
- Simulation outputs framed as trend and risk indicators, not final values
- System architecture aligned with controlled, accountable usage

### Notes
- v1.0 does NOT indicate feature completeness
- v1.0 indicates conceptual stability and governance readiness

---

## [0.9.0] – Product Boundary & Identity Integration
**Status:** Pre-Commercial Validation

### Added
- Netlify Identity integration
- User role separation (free / pro / edu_pro)
- Stripe checkout flow (test & live ready)
- Automated role upgrade via webhook
- Feature gating on frontend and backend
- AI access restricted by role and license

### Changed
- System transitioned from open research tool to gated platform
- AI treated as governed resource rather than direct feature

---

## [0.7.0] – AI-Assisted Analysis (Controlled)
**Status:** Research → Decision Support Transition

### Added
- AI-assisted analysis for interpretation and hypothesis generation
- Dedicated AI gateway (`ask-gemini.js`)
- Separation between simulation logic and AI explanation layer

### Changed
- Removed direct AI calls from UI
- Introduced policy-first execution path

### Notes
- AI explicitly positioned as assistant, not authority
- Human verification emphasized

---

## [0.5.0] – Boundary Awareness & Misuse Prevention
**Status:** Research Tool with Ethical Constraints

### Added
- Usage disclaimers and limitation notices
- Explicit non-production usage framing
- Early responsibility statements in outputs

### Changed
- Shifted focus from numerical accuracy to misuse prevention
- Simulation results framed as indicative, not definitive

---

## [0.3.0] – Educational & Research Orientation
**Status:** Learning and Teaching Tool

### Added
- Structured input profiles (JSON-based)
- Visualization for SOA, trends, and comparative analysis
- Example simulation profiles for teaching and demonstration

### Changed
- Refactored scripts into reusable simulation logic
- Improved readability for non-author users

### Observations
- User misinterpretation identified as key risk
- Sparked need for standards and boundaries

---

## [0.1.0] – Initial Simulation Prototype
**Status:** Personal Engineering Tool

### Added
- Script-based battery simulation
- Manual parameter tuning from datasheets
- Internal validation against engineering intuition

### Notes
- Single-user, no standard, no governance
- Served as cognitive extension for the author

---

## Philosophy of Versioning

- Versions reflect **intent clarity**, not UI polish
- A higher version means **less ambiguity**, not more features
- Governance and responsibility are treated as core functionality

---

**Maintainer:** Jesada Pholcharoen  
**Project:** Voltamind – Battery Simulation & Decision Support Platform
