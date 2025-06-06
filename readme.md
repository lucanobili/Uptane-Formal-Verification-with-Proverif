# Formal Verification of the Uptane Automotive OTA Framework

This project presents a formal verification of the Uptane protocol — a security framework designed to secure over-the-air (OTA) software updates in modern automotive systems. The verification is performed using **ProVerif**, a tool for formally analyzing cryptographic protocols.

The model focuses on a single update cycle and includes core Uptane entities:
- Primary and Secondary ECUs
- Director and Image Repositories
- Time Server

Key security properties analyzed include:
- Integrity and authenticity of software updates
- Protection against arbitrary software installation
- Cross-repository consistency verification

## Model File

The full ProVerif model is provided in the file:

uptane.pv