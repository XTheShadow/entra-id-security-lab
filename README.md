# Entra ID & Azure Security Lab

A hands-on log of cloud identity and security configurations built while studying for Microsoft SC-500 (Cloud and AI Security Engineer Associate). Each entry documents a real configuration made in a live Azure/Entra ID tenant, the reasoning behind the design choices, and what I'd change for a production environment.

This isn't a tutorial rehash. The goal is to show applied understanding of enterprise identity, network, and AI workload security controls, not just completed checklist items.

## Why this exists

Most cybersecurity portfolios show either offensive tooling or certifications. This fills the gap: documented, reasoned, hands-on cloud security configuration work. It's the evidence behind the SC-500 study process, not just the credential itself.

## Structure

```
/identity-access       Conditional Access, PIM, MFA, managed identities, Key Vault, app registrations
/networking             NSGs/ASGs, Virtual Network Manager, Private Link/Private Access, Azure Firewall
/compute-ai-workloads    VM/container security, AI workload security (Defender for AI, Foundry guardrails)
/security-operations     Defender for Cloud, Microsoft Sentinel, KQL detections
```

Each write-up follows the same format: **Problem → Configuration → Reasoning → Production Considerations**.

## Notes on this lab

- All tenant IDs, subscription IDs, and resource names shown are redacted or replaced with placeholders.
- Test identities (e.g. "Delia Dennis") are Microsoft Learn sample accounts used for guided exercises, not real people.
- This is a personal training tenant, not a production or client environment.

## Background

Computer Engineering graduate targeting AI Security Engineer roles at the intersection of security, AI, and red teaming. See [ShadowZap](https://github.com/XTheShadow/ShadowZap) for offensive/AI security tooling work. This repo is the cloud/defensive counterpart, built in parallel with SC-500 exam preparation.

---

*Updated as each lab exercise is completed. Latest entry: see individual folders.*
