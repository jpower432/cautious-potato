---
x-trestle-set-params:
  # You may set values for parameters in the assembled Profile by adding
  #
  # profile-values:
  #   - value 1
  #   - value 2
  #
  # below a section of values:
  # The values list refers to the values in the catalog, and the profile-values represent values
  # in SetParameters of the Profile.
  #
  pe-3_prm_1:
    values:
  pe-3_prm_2:
    values:
  pe-3_prm_3:
    values:
  pe-3_prm_4:
    values:
  pe-3_prm_5:
    values:
  pe-3_prm_6:
    values:
  pe-3_prm_7:
    values:
  pe-3_prm_8:
    values:
  pe-3_prm_9:
    values:
x-trestle-global:
  profile:
    title: Generic profile created by trestle named test_profile.
  sort-id: pe-03
---

# pe-3 - \[\] Physical Access Control

## Control Statement

- \[a.\] Enforce physical access authorizations at {{ insert: param, pe-3_prm_1 }} by:

  - \[1.\] Verifying individual access authorizations before granting access to the facility; and
  - \[2.\] Controlling ingress and egress to the facility using {{ insert: param, pe-3_prm_2 }};

- \[b.\] Maintain physical access audit logs for {{ insert: param, pe-3_prm_4 }};

- \[c.\] Control access to areas within the facility designated as publicly accessible by implementing the following controls: {{ insert: param, pe-3_prm_5 }};

- \[d.\] Escort visitors and control visitor activity {{ insert: param, pe-3_prm_6 }};

- \[e.\] Secure keys, combinations, and other physical access devices;

- \[f.\] Inventory {{ insert: param, pe-3_prm_7 }} every {{ insert: param, pe-3_prm_8 }}; and

- \[g.\] Change combinations and keys {{ insert: param, pe-3_prm_9 }} and/or when keys are lost, combinations are compromised, or when individuals possessing the keys or combinations are transferred or terminated.

## Control guidance

Physical access control applies to employees and visitors. Individuals with permanent physical access authorizations are not considered visitors. Physical access controls for publicly accessible areas may include physical access control logs/records, guards, or physical access devices and barriers to prevent movement from publicly accessible areas to non-public areas. Organizations determine the types of guards needed, including professional security staff, system users, or administrative staff. Physical access devices include keys, locks, combinations, biometric readers, and card readers. Physical access control systems comply with applicable laws, executive orders, directives, policies, regulations, standards, and guidelines. Organizations have flexibility in the types of audit logs employed. Audit logs can be procedural, automated, or some combination thereof. Physical access points can include facility access points, interior access points to systems that require supplemental access controls, or both. Components of systems may be in areas designated as publicly accessible with organizations controlling access to the components.

# Editable Content

<!-- Make additions and edits below -->
<!-- The above represents the contents of the control as received by the profile, prior to additions. -->
<!-- If the profile makes additions to the control, they will appear below. -->
<!-- The above markdown may not be edited but you may edit the content below, and/or introduce new additions to be made by the profile. -->
<!-- If there is a yaml header at the top, parameter values may be edited. Use --set-parameters to incorporate the changes during assembly. -->
<!-- The content here will then replace what is in the profile for this control, after running profile-assemble. -->
<!-- The current profile has no added parts for this control, but you may add new ones here. -->
<!-- Each addition must have a heading either of the form ## Control my_addition_name -->
<!-- or ## Part a. (where the a. refers to one of the control statement labels.) -->
<!-- "## Control" parts are new parts added after the statement part. -->
<!-- "## Part" parts are new parts added into the top-level statement part with that label. -->
<!-- Subparts may be added with nested hash levels of the form ### My Subpart Name -->
<!-- underneath the parent ## Control or ## Part being added -->
<!-- See https://ibm.github.io/compliance-trestle/tutorials/ssp_profile_catalog_authoring/ssp_profile_catalog_authoring for guidance. -->
