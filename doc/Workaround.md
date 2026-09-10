# Release Notes — Version 2.4.0

**Status:** `Draft`  
**Owner:** Documentation Team  
**Last updated:** September 10, 2026

## What's New

This release introduces several improvements across the platform.

### 1. New Workflow

The new workflow follows these steps:

1. **Create** a new workspace.
2. **Configure** the required settings.
3. **Review** the generated output.
4. **Publish** when everything looks correct.

> **Important:** Publishing is irreversible once the workflow has been finalized.

### 2. Configuration

Use the following configuration:

```yaml
environment: production
version: 2.4.0
features:
  - search
  - analytics
  - notifications