# Lab 2: Attribute-Based Access Control (ABAC) via Dynamic Groups

## 2.1 Security Objective
To implement an automated authorization boundary that eliminates manual group assignments. This reduces the risk of "Privilege Creep" and ensures that access is granted or revoked based on verified identity attributes in real-time.

## 2.2 Technical Procedure
- Security Group Configuration:
Navigated to Identity > Groups > All groups > New group.
Set Group type to Security and Membership type to Dynamic User.

- Dynamic Rule Engineering:
Configured the rule using the syntax: (user.department -eq "Finance").
This logic ensures that any user object with the "Finance" metadata is automatically processed into the group.

- Authorization Validation:
Verified the background synchronization process by auditing the Members tab of the group to confirm all 10 identities from Lab 1 were successfully identified.

## 2.3 Evidence
- Outcome:
Automated membership population verified; administrative overhead for access management reduced to zero.
