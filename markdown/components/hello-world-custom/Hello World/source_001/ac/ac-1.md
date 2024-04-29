---
x-trestle-comp-def-rules:
  Hello World:
    - name: example_rule_1
      description: My rule description for example rule 1
x-trestle-param-values:
  ac-1_prm_1:
  ac-1_prm_2:
  ac-1_prm_3:
  ac-1_prm_4:
  ac-1_prm_5:
  ac-1_prm_6:
  ac-1_prm_7:
x-trestle-global:
  profile:
    title: ACME Inc. official controls profile.
    href: profiles/ACME_internal_profile/profile.json
  sort-id: ac-01
x-trestle-rules-params:
  Hello World:
    - name: prm_1
      description: prm_1 description
      options: "{'default': '5%', '5pc': '5%', '10pc': '10%', '15pc': '15%', '20pc':
        '20%'}"
      rule-id: example_rule_1
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
  Hello World:
    - name: prm_1
      values:
        - 5%
---

# ac-1 - \[Access Control\] Policy and Procedures

## Control Statement

- \[a.\] Develop, document, and disseminate to {{ insert: param, ac-1_prm_1 }}:

  - \[1.\] {{ insert: param, ac-1_prm_2 }} access control policy that:

    - \[(a)\] Addresses purpose, scope, roles, responsibilities, management commitment, coordination among organizational entities, and compliance; and
    - \[(b)\] Is consistent with applicable laws, executive orders, directives, regulations, policies, standards, and guidelines; and

  - \[2.\] Procedures to facilitate the implementation of the access control policy and the associated access controls;

- \[b.\] Designate an {{ insert: param, ac-1_prm_3 }} to manage the development, documentation, and dissemination of the access control policy and procedures; and

- \[c.\] Review and update the current access control:

  - \[1.\] Policy {{ insert: param, ac-1_prm_4 }} and following {{ insert: param, ac-1_prm_5 }}; and
  - \[2.\] Procedures {{ insert: param, ac-1_prm_6 }} and following {{ insert: param, ac-1_prm_7 }}.

## Control guidance

Access control policy and procedures address the controls in the AC family that are implemented within systems and organizations. The risk management strategy is an important factor in establishing such policies and procedures. Policies and procedures contribute to security and privacy assurance. Therefore, it is important that security and privacy programs collaborate on the development of access control policy and procedures. Security and privacy program policies and procedures at the organization level are preferable, in general, and may obviate the need for mission- or system-specific policies and procedures. The policy can be included as part of the general security and privacy policy or be represented by multiple policies reflecting the complex nature of organizations. Procedures can be established for security and privacy programs, for mission or business processes, and for systems, if needed. Procedures describe how the policies or controls are implemented and can be directed at the individual or role that is the object of the procedure. Procedures can be documented in system security and privacy plans or in one or more separate documents. Events that may precipitate an update to access control policy and procedures include assessment or audit findings, security incidents or breaches, or changes in laws, executive orders, directives, regulations, policies, standards, and guidelines. Simply restating controls does not constitute an organizational policy or procedure.

## Control acme_guidance

Access control documentation should be at one centrally managed intranet site that is consistent across the corporation. Website should be indexed in intranet search engines.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: ac-1 -->

### Rules:

  - example_rule_1

### Implementation Status: planned

______________________________________________________________________
