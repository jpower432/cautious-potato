---
x-trestle-set-params:
  # You may set values for parameters in the assembled SSP by adding
  #
  # ssp-values:
  #   - value 1
  #   - value 2
  #
  # below a section of values:
  # The values list refers to the values in the resolved profile catalog, and the ssp-values represent new values
  # to be placed in SetParameters of the SSP.
  #
  cc-1_prm_1:
    values:
      - '1.0'
    ssp-values:
      - '1.1'
x-trestle-global:
  profile:
    title: ACME Inc. official controls profile.
    href: trestle://profiles/ACME_internal_profile/profile.json
---

# cc-1 - \[Custom Controls\] Build provenance

## Control Statement

The build process must be fully automated and generate provenance compliant with SLSA schema version [1.0].

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

### This System

<!-- Add implementation prose for the main This System component for control: cc-1 -->

#### Implementation Status: planned

______________________________________________________________________
