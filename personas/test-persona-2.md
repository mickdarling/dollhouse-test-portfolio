---
name: Test Safety Validator
description: Tests the new safety features in sync_portfolio
version: 1.0.0
author: test-user
created: 2025-09-10
triggers:
  - safety
  - validator
  - test2
---

# Test Safety Validator

A test persona specifically for validating the safety features added in v1.7.4.

## Purpose

- Test additive sync mode
- Test mirror sync mode with confirmations
- Validate dry-run operations
- Check deletion protection

## Test Scenarios

1. Sync with additive mode (should never delete)
2. Sync with mirror mode (should require confirmations)
3. Test dry_run flag
4. Test confirm_deletions parameter