# Enterprise AI Governance Architecture

A public companion repository for an enterprise AI governance portfolio project.

This project demonstrates how AI requests can be evaluated through a governance layer before accessing enterprise data or producing AI-generated responses.

## Core Concepts

- Enterprise AI governance
- Authorization before data access
- Prompt injection protection
- Policy-based AI decisions
- PostgreSQL-backed finance data
- Governed AI response patterns

## Governance Flow

```text
User Prompt
    ↓
Identity / Role Context
    ↓
Josh's AI Governance
    ↓
Policy Evaluation
    ↓
Allow / Deny / Block
    ↓
Enterprise Data Access
    ↓
AI Response
