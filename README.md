# Renesas RA8 – Production Guides

This repository contains production-oriented guides for Renesas RA family microcontrollers. The focus is on secure, repeatable provisioning and deployment suitable for manufacturing environments.

## Contents

### RA8M1 Secure Boot (Bare Metal)

**[RA8M1_Secure_Boot_baremetal.pdf](./RA8M1_Secure_Boot_baremetal.pdf)** — Guidelines for Original Equipment Manufacturers (OEMs) deploying RA8 family microcontrollers in production with **Secure Boot** enabled.

The guide describes:

- A **secure, repeatable provisioning process** for manufacturing
- **Protecting cryptographic keys** using a Hardware Security Module (HSM)
- A **reference provisioning approach** that integrates:
  - Secure key storage  
  - Firmware authentication  
  - Device configuration  

into a streamlined production workflow. The intent is to show how Secure Boot can be enabled and managed in an automated, repeatable way, avoiding unsecure manual file-based key handling and the overhead of switching between multiple tools—both of which are generally unsuitable for scalable, auditable production.

The document does not define the only valid provisioning strategy for RA8 devices; it presents one concrete, practical solution that balances security, automation, and flexibility. OEMs are expected to adapt the approach to their own manufacturing constraints, security policies, and threat models.

---

## License

See [LICENSE](./LICENSE) for terms.
