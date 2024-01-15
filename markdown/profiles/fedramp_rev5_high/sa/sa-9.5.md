---
x-trestle-set-params:
    # This section contains the parameters that are part of this control.
  # Each parameter has properties. Only the profile-values and display-name properties are editable.
  # The other properties are informational.
  #
  # The values property for a parameter represents values inherited from the OSCAL catalog.
  # To override the catalog settings, use bullets under profile-values as shown below:
  #
  #   profile-values:
  #     - value 1
  #     - value 2
  #
  # If the "- <REPLACE_ME>" placeholder appears under profile-values, it is the same as if
  # the profile-values property were left empty.
  #
  # Some parameters may show an aggregates property which lists other parameters. This means
  # the parameter value is made up of the values from the other parameters. For parameters
  # that aggregate, profile-values is not applicable.
  #
  # Property param-value-origin is meant for putting the origin from where that parameter comes from.
  # In order to be changed in the current profile, profile-param-value-origin property will be displayed with
  # the placeholder "<REPLACE_ME>" for you to be replaced. If a parameter already has a param-value-origin
  # coming from an inherited profile, do no change this value, instead use profile-param-value-origin as follows:
  #
  #    param-value-origin: DO NOT REPLACE - this is the original value
  #    profile-param-value-origin: <REPLACE_ME> - replace the new value required HERE
  #
  sa-09.05_odp.01:
    alt-identifier: sa-9.5_prm_1
    profile-values:
    profile-param-value-origin: <REPLACE_ME>
  sa-09.05_odp.02:
    guidelines:
      - prose: locations where <SA-09(05)_ODP[01] SELECTED PARAMETER VALUE(S)> is/are
          to be restricted are defined;
    alt-identifier: sa-9.5_prm_2
    profile-values:
    profile-param-value-origin: <REPLACE_ME>
  sa-09.05_odp.03:
    guidelines:
      - prose: requirements or conditions for restricting the location of <SA-09(05)_ODP[01]
          SELECTED PARAMETER VALUE(S)> are defined;
    alt-identifier: sa-9.5_prm_3
    profile-values:
    profile-param-value-origin: <REPLACE_ME>
x-trestle-global:
  profile:
    title: FedRAMP Rev 5 High Baseline
  sort-id: sa-09.05
---

# sa-9.5 - \[System and Services Acquisition\] Processing, Storage, and Service Location

## Control Statement

Restrict the location of {{ insert: param, sa-09.05_odp.01 }} to {{ insert: param, sa-09.05_odp.02 }} based on {{ insert: param, sa-09.05_odp.03 }}.

## Control Assessment Objective

based on {{ insert: param, sa-09.05_odp.03 }}, {{ insert: param, sa-09.05_odp.01 }} is/are restricted to {{ insert: param, sa-09.05_odp.02 }}.

## Control guidance

The location of information processing, information and data storage, or system services can have a direct impact on the ability of organizations to successfully execute their mission and business functions. The impact occurs when external providers control the location of processing, storage, or services. The criteria that external providers use for the selection of processing, storage, or service locations may be different from the criteria that organizations use. For example, organizations may desire that data or information storage locations be restricted to certain locations to help facilitate incident response activities in case of information security incidents or breaches. Incident response activities, including forensic analyses and after-the-fact investigations, may be adversely affected by the governing laws, policies, or protocols in the locations where processing and storage occur and/or the locations from which system services emanate.

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
<!-- See https://oscal-compass.github.io/compliance-trestle/tutorials/ssp_profile_catalog_authoring/ssp_profile_catalog_authoring for guidance. -->
