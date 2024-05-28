---
x-trestle-comp-def-rules:
  My Comp 3:
    - name: rule-ac-2.1
      description: Rule for ac-2.1
x-trestle-param-values:
  ac-02.01_odp:
  ac-2.1_prm_1:
x-trestle-global:
  profile:
    title: ACME Inc. level 1 controls profile.
    href: trestle://profiles/ACME_level_1_profile/profile.json
  sort-id: ac-02.01
x-trestle-rules-params:
  My Comp 3:
    - name: prm_1
      description: prm_1 description
      options: '{"default": "5%", "5pc": "5%", "10pc": "10%", "15pc": "15%", "20pc":
        "20%"}'
      rule-id: rule-ac-2.1
x-trestle-comp-def-rules-param-vals:
  # You may set new values for rule parameters by adding
  #
  # component-values:
  #   - value 1
  #   - value 2
  #
  # below a section of values:
  # The values list refers to the values as set by the components, and the component-values are the new values
  # to be placed in SetParameters of the component definition.
  #
  My Comp 3:
    - name: prm_1
      values:
        - 5%
---

# ac-2.1 - \[Access Control\] Automated System Account Management

## Control Statement

Support the management of system accounts using {{ insert: param, ac-2.1_prm_1 }}.

## Control guidance

Automated system account management includes using automated mechanisms to create, enable, modify, disable, and remove accounts; notify account managers when an account is created, enabled, modified, disabled, or removed, or when users are terminated or transferred; monitor system account usage; and report atypical system account usage. Automated mechanisms can include internal system functions and email, telephonic, and text messaging notifications.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: ac-2.1 -->

### Rules:

  - rule-ac-2.1

### Implementation Status: planned

______________________________________________________________________
