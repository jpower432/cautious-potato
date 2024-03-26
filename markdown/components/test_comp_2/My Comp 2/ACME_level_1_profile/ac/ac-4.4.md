---
x-trestle-comp-def-rules:
  My Comp 2:
    - name: rule-ac-4.4
      description: Rule for ac-4.4
x-trestle-param-values:
  ac-4.4_prm_1:
  ac-4.4_prm_2:
  ac-4.4_prm_3:
x-trestle-global:
  profile:
    title: ACME Inc. level 1 controls profile.
    href: trestle://profiles/ACME_level_1_profile/profile.json
  sort-id: ac-04.04
---

# ac-4.4 - \[Access Control\] Flow Control of Encrypted Information

## Control Statement

Prevent encrypted information from bypassing {{ insert: param, ac-4.4_prm_1 }} by {{ insert: param, ac-4.4_prm_2 }}.

## Control guidance

Flow control mechanisms include content checking, security policy filters, and data type identifiers. The term encryption is extended to cover encoded data not recognized by filtering mechanisms.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: ac-4.4 -->

### Rules:

  - rule-ac-4.4

### Implementation Status: planned

______________________________________________________________________
