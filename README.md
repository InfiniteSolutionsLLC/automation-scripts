# Automation Scripts

## Purpose
This repository contains **reusable automation scripts** used across Infinite Solutions to reduce manual work and improve operational consistency.

Scripts here are treated as **production assets**, not one-off utilities.

## What Belongs Here
- PowerShell scripts
- Shared PowerShell modules
- Remediation logic
- Automation utilities used by:
  - Intune
  - Power Automate
  - Monitoring tools
  - Operational workflows

## Requirements for Scripts
Every script must include:
- Clear description of purpose
- Inputs and outputs
- Expected behavior
- Error handling where applicable

## What Does NOT Belong Here
- Personal scripts
- Temporary troubleshooting scripts
- Client-specific hacks
- Scripts without documentation

## Usage Philosophy
Scripts should be:
- Idempotent where possible
- Safe to re-run
- Designed for automation, not manual execution

## Ownership
Company-owned. No personal ownership of scripts in this repository.
