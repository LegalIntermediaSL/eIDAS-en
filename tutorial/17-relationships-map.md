# 17. Relationship Map Between Signature, Seal, Certificate, and Wallet

## Introduction

Some of the most frequent confusion in eIDAS comes from concepts that are connected but not equivalent.

```mermaid
flowchart LR
    A["Digital identity"] --> B["European wallet"]
    B --> C["Credentials and attributes"]
    C --> D["Authentication"]
    C --> E["Signing in some contexts"]
    F["Certificate"] --> G["Electronic signature"]
    F --> H["Electronic seal"]
    G --> I["Natural person"]
    H --> J["Legal person"]
    K["Timestamp"] --> L["Temporal evidence"]
    M["Registered delivery"] --> N["Proof of sending and receipt"]
    O["Provider"] --> F
    O --> K
    O --> M
    P["Trusted list (TSL)"] --> O
```

## Key Idea

Certificates, signatures, seals, timestamps, delivery services, and wallets are related pieces of the same ecosystem, but each serves a different function.

## Summary

The map helps show how identity, certificates, evidence, and trust services fit together without collapsing them into the same concept.
