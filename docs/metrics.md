# Activation Metrics – Home Assistant Case Study
## Purpose
Define a clear activation metric that represents early user value and predicts long-term retention for Home Assistant.

## North Star Activation Metric
**Percentage of new users who complete their first successful automation within 24 hours of setup.**

### Why this metric
- Represents meaningful value delivery
- Indicates product understanding
- Encourages habit formation
- Aligns with long-term retention

## Supporting Metrics
- Time to first device/integration connected
- Percentage of users who create at least one automation
- Time to first automation run
- Onboarding abandonment rate

## Definitions
- **First successful automation:** An automation that is created, enabled, and runs at least once without error.
- **Activation window:** First 24 hours post-setup (assumption for this case study).

## Measurement Approach (Simulated)
- Event-based funnel: setup → create → enable → run
- Public assumptions only
- No proprietary or internal data

## Risks & Limitations
- Power users may activate faster than average users
- Some users derive value without automations
- Simulated data limits precision

## Relationship to Product Problem
This metric directly measures success against the activation gap defined in Issue #1.
