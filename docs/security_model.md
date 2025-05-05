# PiCommOS Security Model

PiCommOS is designed to be secure by default.

## Core Principles
- Full disk encryption (LUKS2)
- RAM wiped on shutdown
- No network traffic without verified VPN
- Messaging secured with post-quantum cryptography

## Threat Models
- Physical device theft
- Passive network surveillance
- Metadata analysis
- State-level actors

Everything is locked down unless explicitly enabled by you.
