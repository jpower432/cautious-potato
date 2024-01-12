---
x-trestle-comp-def-rules:
  My Comp:
    - name: rule-cc-1
      description: Rule for cc-1
x-trestle-param-values:
  cc-1_prm_1:
    - '1.0'
x-trestle-global:
  profile:
    title: ACME Inc. level 1 controls profile.
    href: trestle://profiles/ACME_level_1_profile/profile.json
---

# cc-1 - \[Custom Controls\] Build provenance

## Control Statement

The build process must be fully automated and generate provenance compliant with SLSA schema version {{ insert: param, cc-1_prm_1 }}.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: cc-1 -->

### Rules:

  - rule-cc-1

### Implementation Status: planned

______________________________________________________________________
