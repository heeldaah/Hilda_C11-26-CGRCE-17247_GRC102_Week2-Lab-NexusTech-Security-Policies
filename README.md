# INTERNATIONAL CYBERSECURITY AND DIGITAL FORENSICS ACADEMY (ICDFA)

## Governance, Compliance, and Risk (GCR)

### GRC102 Information Security Governance

# Week 2 Lab: Developing Security Policies and Procedures

**Student:** Hilda Odein Joshua-Jack  
**Registration Number:** C11/26/CGRCE/17247  
**Course Code:** GRC102  
**Course Title:** Information Security Governance  
**Week's Title:** Developing Security Policies and Procedures  
**Credit Load:** 3 Credits  
**Cohort:** 11  
**Date:** 15th September, 2026

---

## 📋 Table of Contents

1. [Introduction](01-Introduction.md)
2. [Security Policy Development Lifecycle](02-Security-Policy-Development-Lifecycle.md)
3. [Evidence Bundle 1 – Security Policy Hierarchy](evidence-bundles/Evidence-Bundle-1-Security-Policy-Hierarchy.md)
4. [Evidence Bundle 2 – Acceptable Use Policy](evidence-bundles/Evidence-Bundle-2-Acceptable-Use-Policy.md)
5. [Evidence Bundle 3 – User Access Request Procedure](evidence-bundles/Evidence-Bundle-3-User-Access-Request-Procedure.md)
6. [Evidence Bundle 4 – Communication and Training Plan](evidence-bundles/Evidence-Bundle-4-Communication-and-Training-Plan.md)
7. [Evidence Bundle 5 – Policy Review and Maintenance Memo](evidence-bundles/Evidence-Bundle-5-Policy-Review-and-Maintenance-Memo.md)
8. [Overall Governance Considerations](07-Overall-Governance-Considerations.md)
9. [References](08-References.md)
10. [Conclusion](09-Conclusion.md)
11. [AI Assistance Declaration](10-AI-Assistance-Declaration.md)
12. [Appendix A – Student Completion Checklist](Appendix-A-Completion-Checklist.md)

---


# 1. Introduction

NexusTech Solutions has increased its workforce to a significant extent from 50 to 250 workers and deals with customers in the finance and health care industries. Thus, there is more information, the use of which is associated with more technologies, and there is an increase in security and compliance needs.

The main problem that was found in the scenario concerns the use of the outdated IT document "IT Rules" that is five years old. This document contains not only policy requirements but also technical instructions and recommendations. As a result, it is difficult for employees to distinguish between mandatory and recommended actions and the person responsible for them.

As the Information Security Manager, I believe it is necessary to implement the security documentation structure that includes four levels of policies - Policies, Standards, Guidelines, and Procedures. This way, it is possible to clarify the responsibilities and ensure maintenance of security requirements as they change.

The work done in this report refers to the Security Policy Development Lifecycle.

# 2. Security Policy Development Lifecycle

For NexusTech, the Security Policy Development Lifecycle can be applied through the following stages:

| Stage | Application at NexusTech |
|-------|--------------------------|
| 1. Identify the need | The outdated IT Rules document and inconsistent security practices demonstrate the need for a formal policy framework. |
| 2. Gather requirements | Review business needs, information assets, client requirements, security risks and relevant compliance expectations. |
| 3. Develop the policy | Draft clear policy requirements and separate them from technical standards and operational procedures. |
| 4. Review and approve | Relevant stakeholders review the document before approval by the appropriate authority. |
| 5. Communicate and implement | Employees receive communication and training appropriate to their roles. |
| 6. Monitor compliance | Security and management teams monitor implementation and address non-compliance. |
| 7. Review and maintain | Policies are reviewed periodically and whenever significant organisational, technological or security changes occur. |

This lifecycle prevents policies from becoming static documents that are forgotten after approval. It also gives NexusTech a repeatable approach for developing future policies.

# EVIDENCE BUNDLE 1
# 3.0 Security Policy Hierarchy

## 3.1 Security Documentation Hierarchy

NexusTech will use four main documentation levels.

| Document Type | Purpose | Authority | Mandatory / Recommended | Level of Detail |
|---------------|---------|-----------|-------------------------|-----------------|
| Policy | Defines management's expectations, security objectives and rules that employees must follow. | Highest | Mandatory | High-level |
| Standard | Defines specific mandatory requirements that support a policy. | Derived from policy | Mandatory | Medium |
| Guideline | Provides recommended good practices that help users meet security objectives. | Advisory | Recommended | Medium |
| Procedure | Explains the steps required to perform a specific activity consistently. | Derived from policy/standard | Mandatory where applicable | Detailed |

### Policy

A policy should state what NexusTech requires and the reason why it is necessary; it should not usually include detailed technical instructions.

**For example:**
> When accessing the corporate network from a remote location, all employees are required to use multi-factor authentication.

### Standard

A standard converts a policy requirement into a specific and measurable one.

**For example:**
> To access corporate systems remotely, it is necessary to use an approved MFA method which provides at least two authentication factors.

### Guideline

A guideline gives advice instead of setting out a strict requirement.

**For example:**
> When travelling, employees should refrain from connecting company equipment to public and unsecured Wi-Fi networks.

### Procedure

A procedure sets out how an activity should be carried out.

**For example:**
> To open the IT portal, click on 'MFA Setup', then scan the QR code that is displayed using the approved authenticator application and input the verification code.

---

## 3.2 Classification of the Eight Statements

| S/N | Statement | Classification | Justification |
|-----|-----------|----------------|---------------|
| 1 | All NexusTech employees must use MFA when accessing the corporate network remotely. | Policy | This establishes a mandatory security requirement without explaining the technical steps for implementing MFA. |
| 2 | To configure MFA on your mobile device, download the Authenticator app, scan the QR code provided in the IT portal, and enter the six-digit verification code. | Procedure | It provides specific step-by-step instructions for completing an MFA setup activity. |
| 3 | It is recommended that developers use parameterised queries to reduce SQL injection risk. | Guideline | The wording "recommended" makes this advisory rather than a mandatory organisational requirement. |
| 4 | NexusTech is committed to protecting the confidentiality, integrity and availability of all client data. | Policy | It expresses a high-level management commitment to information security and the protection of information assets. |
| 5 | All corporate laptops must have full-disk encryption enabled using BitLocker (Windows) or FileVault (macOS). | Standard | It defines a specific mandatory technical requirement that supports the broader objective of protecting company information. |
| 6 | Employees should avoid connecting to public, unsecured Wi-Fi networks when travelling. | Guideline | It provides recommended behaviour rather than an absolute mandatory requirement. |
| 7 | In the event of a suspected security breach, employees must immediately contact the IT Helpdesk at extension 5555. | Procedure | It gives a specific action users must take when a particular event occurs. |
| 8 | Passwords must be a minimum of 14 characters and contain at least one uppercase letter, one lowercase letter, one number and one special character. | Standard | It establishes measurable and mandatory password requirements rather than a general policy objective. |

### GOVERNANCE JUDGEMENT

The main distinction I used when categorising the statements was the level of decision being made. Policies establish organisational direction and mandatory expectations. Standards make requirements measurable, guidelines provide advice, while procedures tell people how to carry out a task.

This separation should reduce the problem currently experienced by NexusTech where one document contains everything from management requirements to technical instructions.

---

## 3.3 Policy Hierarchy Diagram

```mermaid
flowchart TD
    A[POLICY<br/>High-level mandatory direction<br/>Approved by CEO] --> B[STANDARD<br/>Specific mandatory requirements<br/>Derived from policy]
    B --> C[GUIDELINE<br/>Recommended good practice<br/>Advisory]
    B --> D[PROCEDURE<br/>Step-by-step instructions<br/>Mandatory where applicable]
    C --> E[Implementation]
    D --> E
