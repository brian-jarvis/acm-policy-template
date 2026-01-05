Rules for policy formats:

1. No spaces at end of lines.  Enforced with git pre-commit hook
2. Must have blank line at end of document.  Enforced with git pre-commit hook
3. All yaml files/documents must start with `---`
4. OperatorPolicies should specify complete subscription definition.  This prevents issues where the policy fails because package api conflicts.  Channel should specify a release versioned channel such as "stable-1.23" where possible.
  ```
    subscription:
      channel: ""
      name: ""
      namespace: ""
      source: ""
      sourceNamespace: ""
  ```
5. Every Policy should have a README file.  This should contain any specific details of the policy implementation that might be of use for a user to know. Should use the following format where possible
   ```
    #  POLICY NAME
    Brief description of the policy

    ## Dependencies
    - A list of other policies this is dependent on

    ## Details
    ACM Minimal Version: 2.12

    Documentation: [LINK to DOCS](httos://docs.example.com)

    ---
    **Notes:**
      - Additional implementation notes
   ```
6. The name assigned to a manifest in the generator must be unique across all policies.
