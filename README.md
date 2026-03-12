# Shimano STEPS CAN Analysis Data

This repository stores captured CAN datasets and reverse-engineering analysis artifacts for Shimano STEPS systems.

## Goal

The goal is to build a structured, reproducible analysis base for Shimano CAN communication:

- Keep raw capture data and derived plots together.
- Track protocol hypotheses and validation notes over time.
- Separate analyses by component or subsystem for clarity.

## Structure

- `DarfonBatteryChargerCommunicationAnalysis/`: charger <-> battery communication captures, plots, and findings.

Additional component analyses can be added as new top-level folders following the same pattern.

## Related Tooling

Sniffing and routing are performed with the companion repository:

- [multican-sniffer-bridge](https://github.com/CapnDeCode/multican-sniffer-bridge)

Use that project to record traffic and generate artifacts that are then stored here for long-term analysis.
