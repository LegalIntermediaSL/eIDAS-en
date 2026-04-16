# 24. Visual Overview of the eIDAS Ecosystem

## Introduction

This diagram provides a compact visual overview of the main elements of the eIDAS ecosystem.

```mermaid
flowchart TD
    A["eIDAS Regulation"] --> B["Electronic identification"]
    A --> C["Trust services"]
    A --> D["Trust service providers"]
    D --> E["Qualified providers"]
    D --> F["Non-qualified providers"]
    E --> G["Trusted list"]
    C --> H["Electronic signature"]
    C --> I["Electronic seal"]
    C --> J["Timestamp"]
    C --> K["Registered delivery"]
    C --> L["Website authentication"]
    A --> M["eIDAS 2.0"]
    M --> N["European wallet"]
```

## Summary

The diagram helps readers see how legal, institutional, technical, and evidential elements fit together.
