---
x-trestle-comp-def-rules:
  MyComp:
    - name: rule-ac-4.4
      description: Rule for ac-4.4
x-trestle-param-values:
  ac-4.4_prm_1:
  ac-4.4_prm_2:
  ac-4.4_prm_3:
x-trestle-global:
  profile:
    title: Example
    href: trestle://profiles/example/profile.json
  sort-id: ac-04.04
---

# ac-4.4 - \[Access Control\] Flow Control of Encrypted Information

## Control Statement

Prevent encrypted information from bypassing {{ insert: param, ac-4.4_prm_1 }} by {{ insert: param, ac-4.4_prm_2 }}.

- \[4_fr\]

  - \[Requirement:\] The service provider must support Agency requirements to comply with M-21-31 (https://www.whitehouse.gov/wp-content/uploads/2021/08/M-21-31-Improving-the-Federal-Governments-Investigative-and-Remediation-Capabilities-Related-to-Cybersecurity-Incidents.pdf) and M-22-09 (https://www.whitehouse.gov/wp-content/uploads/2022/01/M-22-09.pdf).

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
