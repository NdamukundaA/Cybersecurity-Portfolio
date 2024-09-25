# Botium Toys Security Audit Report

## 1. Introduction
This security audit assesses Botium Toys’ IT infrastructure and assets. The goal is to evaluate the existing security controls and compliance with industry standards, identifying gaps that need improvement.

## 2. Scope and Objectives
- **Scope**: All IT assets, internal network, and physical security measures managed by the IT department at Botium Toys.
- **Objectives**: Ensure compliance with PCI DSS, GDPR, and SOC Type 1 and 2. Review current security controls such as access management, encryption, and disaster recovery planning.

## 3. Key Audit Findings

### 3.1. Least Privilege
- **Status**: Not implemented.
- **Issue**: Employees have unrestricted access to sensitive customer data (PII and credit card information).
- **Risk**: High risk of data breach or unauthorized access.

### 3.2. Encryption
- **Status**: Not in use for sensitive customer data.
- **Issue**: Encryption is not applied to credit card data during processing, transmission, or storage.
- **Risk**: High exposure to data theft and compliance violations.

### 3.3. Disaster Recovery and Backups
- **Status**: No disaster recovery plans or data backups in place.
- **Issue**: Lack of business continuity planning in case of a disaster or data loss.
- **Risk**: Critical data loss could severely impact operations.

## 4. Compliance Checklist
- **PCI DSS Compliance**: No (lacks encryption and access control).
- **GDPR Compliance**: Partial (data breach response plan exists, but privacy protections are inadequate).
- **SOC Type 1 and 2 Compliance**: Partial (data integrity and availability measures are in place, but access controls are insufficient).

## 5. Conclusion
Botium Toys has several gaps in their security controls, particularly in areas like encryption, access management, and disaster recovery planning. These gaps expose the company to potential risks, including data breaches, compliance fines, and operational disruption.

