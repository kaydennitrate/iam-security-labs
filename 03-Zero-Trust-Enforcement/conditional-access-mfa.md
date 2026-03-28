# Lab 3: Zero Trust Posture: Conditional Access & MFA Enforcement

## 3.1 Security Objective
To enforce a "Never Trust, Always Verify" security model. This lab focuses on protecting high-risk departmental accounts by adding adaptive authentication layers that trigger based on dynamic group membership.

## 3.2 Technical Procedure
- Policy Scope Assignment:
Navigated to Protection > Conditional Access > Policies > New policy.
Targeted the 02-Access-Control-Automation group (Finance Security Group).

- Cloud App Inclusions:
Selected All Cloud Apps as the target resource for the policy trigger.

- Access Control Configuration:
Under the Grant menu, selected Require multi-factor authentication.
Set policy state to On to move from report-only to active enforcement.

## 3.3 Evidence
- Outcome:
Identity-based perimeter hardened; MFA requirement active for all targeted sessions to prevent unauthorized access via compromised credentials.
