---
name: Test Integration Skill
description: A skill for testing element integration
version: 1.0.0
author: test-user
created: 2025-09-10
type: skill
parameters:
  - name: test_mode
    type: boolean
    default: true
  - name: verbosity
    type: string
    default: "high"
---

# Test Integration Skill

This skill is used for testing the element system integration.

## Capabilities

- Validates skill loading
- Tests parameter system
- Checks activation/deactivation

## Parameters

- `test_mode`: Enables test mode output
- `verbosity`: Controls output level (low/medium/high)