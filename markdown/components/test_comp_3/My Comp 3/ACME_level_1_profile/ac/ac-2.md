---
x-trestle-comp-def-rules:
  My Comp 3:
    - name: rule-ac-2
      description: Rule for ac-2
x-trestle-param-values:
  ac-02_odp.01:
  ac-02_odp.02:
  ac-02_odp.03:
  ac-02_odp.04:
  ac-02_odp.05:
  ac-02_odp.06:
  ac-02_odp.07:
  ac-02_odp.08:
  ac-02_odp.09:
  ac-02_odp.10:
  ac-2_prm_1:
  ac-2_prm_2:
  ac-2_prm_3:
  ac-2_prm_4:
  ac-2_prm_5:
  ac-2_prm_6:
  ac-2_prm_7:
  ac-2_prm_8:
  ac-2_prm_9:
  ac-2_prm_10:
x-trestle-global:
  profile:
    title: ACME Inc. level 1 controls profile.
    href: trestle://profiles/ACME_level_1_profile/profile.json
  sort-id: ac-02
---

# ac-2 - \[Access Control\] Account Management

## Control Statement

- \[a.\] Define and document the types of accounts allowed and specifically prohibited for use within the system;

- \[b.\] Assign account managers;

- \[c.\] Require {{ insert: param, ac-2_prm_1 }} for group and role membership;

- \[d.\] Specify:

  - \[1.\] Authorized users of the system;
  - \[2.\] Group and role membership; and
  - \[3.\] Access authorizations (i.e., privileges) and {{ insert: param, ac-2_prm_2 }} for each account;

- \[e.\] Require approvals by {{ insert: param, ac-2_prm_3 }} for requests to create accounts;

- \[f.\] Create, enable, modify, disable, and remove accounts in accordance with {{ insert: param, ac-2_prm_4 }};

- \[g.\] Monitor the use of accounts;

- \[h.\] Notify account managers and {{ insert: param, ac-2_prm_5 }} within:

  - \[1.\] {{ insert: param, ac-2_prm_6 }} when accounts are no longer required;
  - \[2.\] {{ insert: param, ac-2_prm_7 }} when users are terminated or transferred; and
  - \[3.\] {{ insert: param, ac-2_prm_8 }} when system usage or need-to-know changes for an individual;

- \[i.\] Authorize access to the system based on:

  - \[1.\] A valid access authorization;
  - \[2.\] Intended system usage; and
  - \[3.\] {{ insert: param, ac-2_prm_9 }};

- \[j.\] Review accounts for compliance with account management requirements {{ insert: param, ac-2_prm_10 }};

- \[k.\] Establish and implement a process for changing shared or group account authenticators (if deployed) when individuals are removed from the group; and

- \[l.\] Align account management processes with personnel termination and transfer processes.

## Control guidance

Examples of system account types include individual, shared, group, system, guest, anonymous, emergency, developer, temporary, and service. Identification of authorized system users and the specification of access privileges reflect the requirements in other controls in the security plan. Users requiring administrative privileges on system accounts receive additional scrutiny by organizational personnel responsible for approving such accounts and privileged access, including system owner, mission or business owner, senior agency information security officer, or senior agency official for privacy. Types of accounts that organizations may wish to prohibit due to increased risk include shared, group, emergency, anonymous, temporary, and guest accounts.

Where access involves personally identifiable information, security programs collaborate with the senior agency official for privacy to establish the specific conditions for group and role membership; specify authorized users, group and role membership, and access authorizations for each account; and create, adjust, or remove system accounts in accordance with organizational policies. Policies can include such information as account expiration dates or other factors that trigger the disabling of accounts. Organizations may choose to define access privileges or other attributes by account, type of account, or a combination of the two. Examples of other attributes required for authorizing access include restrictions on time of day, day of week, and point of origin. In defining other system account attributes, organizations consider system-related requirements and mission/business requirements. Failure to consider these factors could affect system availability.

Temporary and emergency accounts are intended for short-term use. Organizations establish temporary accounts as part of normal account activation procedures when there is a need for short-term accounts without the demand for immediacy in account activation. Organizations establish emergency accounts in response to crisis situations and with the need for rapid account activation. Therefore, emergency account activation may bypass normal account authorization processes. Emergency and temporary accounts are not to be confused with infrequently used accounts, including local logon accounts used for special tasks or when network resources are unavailable (may also be known as accounts of last resort). Such accounts remain available and are not subject to automatic disabling or removal dates. Conditions for disabling or deactivating accounts include when shared/group, emergency, or temporary accounts are no longer required and when individuals are transferred or terminated. Changing shared/group authenticators when members leave the group is intended to ensure that former group members do not retain access to the shared or group account. Some types of system accounts may require specialized training.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: ac-2 -->

### Rules:

  - rule-ac-2

### Implementation Status: planned

______________________________________________________________________
