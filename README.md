# Vanta Control Set

## What is Vanta?

Vanta restores trust in internet businesses by giving startups an easy-to-use platform to improve and prove their security. Thousands of fast-growing companies rely on Vanta to automate their security monitoring and prepare for SOC 2, ISO 27001, or HIPAA compliance certifications in weeks instead of months.

## Vanta Control Set

The Vanta Control Set maps common compliance standards from their requirements to controls and provides them in an easy to consume machine-readable format.

- The SOC 2 controls represent a translation of the SOC 2 criteria into actionable controls
- The HIPAA control set is defined by HIPAA laws and is made available for the convenience of creating a consistent data format

## Data Format

The [controls](/controls) directory contains a JSON file for each standard. This JSON file contains two top-level keys:

- `standard` – detail about the standard including a list of Vanta control IDs per-section
- `controlDetail` – detail about each control with ids that appeared in the `standard` section.

We also provide a [JSON schema](/schema.json) which describes these files.
