**Onboarding Solution Options – Home Assistant Case Study**

**Problem Recap**
New users struggle to reach their first successful automation, creating an activation gap early in the onboarding journey.

**Solution Options Considered**

Option 1: Guided onboarding checklist
A step-by-step checklist that guides users through:
- Connecting their first device/integration
- Creating their first automation
- Confirming the automation runs successfully

**Pros**
- Clear guidance for beginners
- Reduces cognitive overload
- Scales across integrations

**Cons**
- Requires careful UX design
- Risk of feeling prescriptive if not optional
**
Option 2: Pre-built automation templates**
A small set of curated automation templates that users can activate and learn from.

**Pros**
- Fastest path to early success
- Demonstrates product power quickly
- Reduces configuration errors

**Cons**
- Templates may not fit all setups
- Risk of over-reliance without understanding

**Option 3: Progressive disclosure**
Gradually introduce advanced features as users demonstrate readiness.

**Pros**
- Simplifies initial experience
- Matches complexity to user confidence

**Cons**
- Risk of frustrating advanced users
- Requires reliable behavioural signals

**Design Principles (incorporating feedback)**

- Onboarding should adapt to **behavioural signals** (e.g. skipping docs, rapid setup) rather than static persona labels.
- Guidance should act as **scaffolding**, not a mandatory path.
- Checklists and templates must be **optional, dismissible, and non-blocking**.
- Templates should be framed as **examples to learn from**, not shortcuts that abstract system understanding.
- Users should always be able to access the full interface immediately, preserving Home Assistant’s flexibility ethos.

**Prioritisation Decision**

**Primary approach:** Guided onboarding checklist  
**Secondary support:** Limited, high-confidence automation templates
**
Rationale**
- Highest expected impact on activation
- Lower risk than hard persona splits
- Preserves user control and transparency
- Aligns with community expectations
**
Success Measurement**
Success will be evaluated using the activation metric defined in `metrics.md`:
- % of new users reaching first successful automation within 24 hours
**
Risks & Mitigations**
- **Risk:** Advanced users feel constrained  
  **Mitigation:** Make onboarding fully optional and skippable
- **Risk:** Users complete steps without understanding  
  **Mitigation:** Emphasise learning-oriented templates and transparency

## Relationship to Product Metrics
This solution directly targets the activation gap defined in Issue #1.
