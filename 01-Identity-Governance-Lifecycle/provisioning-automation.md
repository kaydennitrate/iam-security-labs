# Lab 1: Automated Identity Provisioning & Lifecycle Management

## 1.1 Security Objective
To establish a standardized identity baseline for a corporate department using automated bulk-ingestion techniques. This ensures data consistency across the tenant and prepares identity objects for downstream security automation and Attribute-Based Access Control (ABAC).

## 1.2 Technical Procedure
- Source Data Preparation:
  Constructed a CSV source file following the Microsoft Entra ID version:v1.0 schema.
  Defined 10 unique user objects with required attributes: displayName, userPrincipalName, passwordProfile, and accountEnabled.
  Assigned the string "Finance" to the department attribute for all objects to facilitate automated grouping.

- Bulk Ingestion Execution:
  Navigated to Identity > Users > All users > Bulk operations > Bulk create.
  Uploaded the validated CSV file and initiated the submission process.

- Verification:
  Monitored the Bulk operation results monitoring tool to ensure all 10 objects were provisioned without parity errors or domain conflicts.

## 1.3 Evidence
- System Status:
[![](Lab 1 - Enterprise Identity Lifecycle (Bulk Onboarding).png)](Lab 1 - Enterprise Identity Lifecycle (Bulk Onboarding).png)

- Outcome:
100% success rate; 10 managed identities established in the cloud directory.
