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
9. [Conclusion](09-Conclusion.md)
10. [References](08-References.md)
12. [AI Assistance Declaration](10-AI-Assistance-Declaration.md)
13. [Appendix A – Student Completion Checklist](Appendix-A-Completion-Checklist.md)

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

   The following diagram illustrates the flow from broad management direction to increasingly detailed implementation requirements:

```mermaid
flowchart TD
    A[Policy] --> B[Standard]
    A --> C[Guideline]
    A --> D[Procedure]
    B --> E[Implementation]
    C --> E
    D --> E

# EVIDENCE BUNDLE 2
# Acceptable Use Policy

---

## NEXUSTECH SOLUTIONS
## ACCEPTABLE USE POLICY

| Document Control | Details |
|------------------|---------|
| Document Title | Acceptable Use Policy |
| Document ID | NTS-ISP-AUP-001 |
| Version | 1.0 |
| Policy Owner | Information Security Manager |
| Approval Authority | Marcus Vance, CEO |
| Effective Date | 18 September 2026 |
| Review Date | 18 September 2027 |
| Status | Approved |

---

## 1. Purpose

The purpose of this Acceptable Use Policy is to establish clear expectations for the appropriate use of NexusTech's information systems, company devices, networks, applications and information.

The policy is intended to reduce security risks such as malware infections, unauthorised access, data leakage and inappropriate use of company resources.

## 2. Scope

This policy applies to:

- All NexusTech employees.
- Contractors, consultants and temporary staff.
- Interns and other authorised users.
- Company-owned laptops, desktops, mobile devices and other endpoints.
- Company networks and cloud services.
- Business applications and information systems.
- Company information accessed or processed using approved personal devices.

Third parties must comply with applicable NexusTech security requirements when they are given access to company systems or information.

## 3. Acceptable Use Requirements

Users must:

1. Use NexusTech systems primarily for legitimate business activities.
2. Protect their usernames, passwords, authentication devices and other credentials.
3. Lock or secure company devices when they are unattended.
4. Store company information only in approved locations and services.
5. Follow applicable information classification and handling requirements.
6. Report suspected security incidents, phishing messages, lost devices or accidental data disclosure promptly.
7. Use only software and applications that are authorised by NexusTech.
8. Respect access restrictions and use only systems and information they are authorised to access.
9. Comply with applicable laws, contractual requirements and NexusTech security policies.
10. Take reasonable care when accessing company systems from outside the office.

## 4. Prohibited Activities

Users must not:

1. Attempt to gain unauthorised access to NexusTech systems, accounts or information.
2. Share passwords, authentication tokens or other credentials with another person.
3. Install unauthorised software on company devices.
4. Disable, bypass or interfere with security controls without approval.
5. Use company systems to distribute malware or other malicious content.
6. Deliberately introduce vulnerabilities into NexusTech systems.
7. Access, copy, modify or distribute information without appropriate authorisation.
8. Store sensitive NexusTech or client information in personal cloud storage services.
9. Use company resources for unlawful activities.
10. Use company systems to harass, threaten or discriminate against others.
11. Connect unauthorised devices to corporate networks where doing so creates a security risk.
12. Attempt to bypass monitoring, logging or other security controls.
13. Use company systems to conduct unauthorised cryptocurrency mining or similar resource-intensive activities.
14. Share confidential client information through personal email, messaging applications or other unapproved services.

## 5. Reasonable Personal Use

Limited personal use of NexusTech systems may be permitted where it:

- Does not interfere with work responsibilities.
- Does not create a security or compliance risk.
- Does not consume excessive company resources.
- Does not involve prohibited activities.
- Does not involve unauthorised storage or sharing of company information.

NexusTech may restrict personal use where it creates operational, legal or security concerns.

## 6. Software and Applications

Users must not install software or browser extensions that have not been approved where administrative privileges or company information are involved.

Requests for business software should follow the appropriate IT request and approval process.

Users must not use unapproved applications to process sensitive company or client information.

## 7. Information Handling

Users are responsible for protecting information they access or handle.

Sensitive information must not be:

- Sent to personal email accounts.
- Uploaded to personal cloud storage.
- Shared with unauthorised individuals.
- Stored on unapproved devices or applications.
- Publicly disclosed without authorisation.

Where information is accidentally shared or exposed, the user must report the incident to the appropriate IT or Security contact immediately.

## 8. Remote Working

Users working remotely must take reasonable precautions to protect company information.

This includes:

- Using approved remote access methods.
- Protecting company devices from unauthorised physical access.
- Avoiding insecure networks where reasonably possible.
- Not allowing other people to use company accounts or devices.
- Reporting lost or stolen devices promptly.

## 9. Monitoring

NexusTech may monitor the use of its information systems for legitimate security, operational, compliance and investigation purposes, subject to applicable law and company requirements.

Users should not assume that activity performed using company systems is completely private.

## 10. Roles and Responsibilities

### Employees and Other Users

Users are responsible for:

- Understanding and following this policy.
- Protecting their credentials and devices.
- Using company systems appropriately.
- Reporting suspected security incidents.
- Completing required security awareness training.

### Information Security Manager

The Information Security Manager is responsible for:

- Maintaining the policy.
- Advising the organisation on acceptable use requirements.
- Monitoring security-related compliance.
- Coordinating reviews and updates.
- Supporting investigations into suspected violations.

### IT Team

The IT team is responsible for:

- Implementing appropriate technical controls.
- Managing approved software and devices.
- Supporting users with security-related issues.
- Maintaining relevant technical records.

### Managers

Managers are responsible for:

- Ensuring employees understand their responsibilities.
- Supporting security training and policy compliance.
- Reporting repeated or serious non-compliance.
- Approving access where required by the relevant process.

### Human Resources

HR may support the enforcement process where violations involve employee conduct or disciplinary action.

## 11. Compliance and Enforcement

Compliance with this policy is mandatory.

A violation may result in:

- Removal or restriction of system access.
- Additional security training.
- Formal investigation.
- Disciplinary action in accordance with company procedures.
- Contractual consequences for third parties.
- Legal or regulatory reporting where required.

The response will depend on the seriousness, impact and circumstances of the violation.

## 12. Exceptions

Exceptions may be permitted where there is a legitimate business requirement that cannot reasonably be met through the standard process.

An exception must:

1. Be documented.
2. Identify the business justification.
3. Identify the associated security risk.
4. Specify the duration of the exception.
5. Be approved by the appropriate authority.
6. Include compensating controls where necessary.

Permanent informal exceptions are not permitted.

## 13. Policy Review

This policy will be reviewed at least annually.

An earlier review may be initiated where there is:

- A significant security incident.
- A major technology change.
- A significant change in business operations.
- A new regulatory or contractual requirement.
- A material change in the organisation's risk profile.

## 14. Approval

| Role | Name |
|------|------|
| Policy Owner | Information Security Manager |
| Approval Authority | Marcus Vance, CEO |
| Version | 1.0 |
| Effective Date | 18 September 2026 |
| Next Scheduled Review | 18 September 2027 |

# EVIDENCE BUNDLE 3
# User Access Request Procedure

---

## NEXUSTECH SOLUTIONS
## USER ACCESS REQUEST PROCEDURE

| Document Control | Details |
|------------------|---------|
| Document Title | User Access Request Procedure |
| Document ID | NTS-PR-ACCESS-001 |
| Version | 1.0 |
| Procedure Owner | Information Security Manager / IT Operations |
| Approval Authority | IT Director |
| Effective Date | 18 September 2026 |
| Review Date | 18 September 2027 |

---

## 1. Purpose

This procedure provides a consistent process for requesting, approving, provisioning and documenting user access to NexusTech systems.

The aim is to make sure users receive only the access they need for their roles and that every access decision can be traced back to an authorised request and approval.

## 2. Scope

This procedure applies to:

- New user access.
- Additional access.
- Changes to existing access.
- Temporary access.
- Privileged access.
- Access removal where relevant to the request process.

It applies to employees, contractors and other authorised users.

## 3. Prerequisites

Before processing an access request, the Helpdesk technician should confirm that:

- An approved access request system or ticketing platform is available.
- The request identifies the user.
- The required system or application is clearly identified.
- The requested role or permission level is specified.
- The user's manager has approved the request.
- A data or system owner has approved access where required.
- The technician is authorised to provision the requested access.

Requests containing incomplete information should not be provisioned until the missing information has been provided.

## 4. Procedure

### Step 1 – Receive the Request

1. Receive the request through the approved IT service management system or access workflow.
2. Do not process access requests received only through informal chat messages, personal email or verbal instructions.
3. Record the request in the appropriate ticket.

The ticket should contain enough information to understand what access is being requested and why.

### Step 2 – Confirm User Details

Verify:

- User's full name.
- Employee or contractor identifier.
- Department.
- Job role.
- Manager.
- Requested system or application.
- Requested access level.
- Business justification.

If the user details cannot be verified, place the request on hold and obtain clarification.

### Step 3 – Verify Approval

Check that the user's manager has approved the request.

Where the application contains sensitive information or the requested access is privileged, verify approval from the relevant system or data owner as well.

Do not rely on an approval that cannot be traced to the authorised approver.

### Step 4 – Determine the Appropriate Role

Identify the standard role that matches the user's job responsibilities.

Use role-based access where available rather than creating individual permissions unnecessarily.

The requested access should follow the least-privilege principle, meaning that the user should receive only the permissions required to perform their duties.

### Step 5 – Perform a Conflict Check

Before provisioning, check whether the requested access could create an inappropriate combination of responsibilities.

For example, where applicable, a user should not receive permissions that allow them to both create and independently approve sensitive financial transactions without appropriate controls.

If a potential conflict is identified, refer the request to the relevant manager, system owner or Information Security Manager.

### Step 6 – Create or Update the Account

Once approval has been confirmed:

1. Create the account if it does not already exist.
2. Use the approved corporate identity.
3. Apply the appropriate role.
4. Configure required authentication controls.
5. Do not grant additional privileges simply because they are technically available.

For an existing account, modify only the permissions approved in the request.

### Step 7 – Apply Least Privilege

Review the resulting permissions before completing the request.

The technician should ask:

> "Does this user have more access than is necessary for the stated business purpose?"

If the answer is yes, remove the unnecessary permissions or refer the request back for clarification.

### Step 8 – Verify Access

Where practical, verify that:

- The account is active.
- The approved role has been assigned.
- Required authentication controls are enabled.
- The user can access the required system.
- Unapproved permissions have not been granted.

Verification should not involve accessing information that the technician is not authorised to view.

### Step 9 – Notify the User and Manager

Notify the user that the access request has been completed.

Where appropriate, notify the manager as well.

The notification should not disclose passwords or other sensitive authentication information.

### Step 10 – Capture Evidence

Update the ticket with evidence of:

- Request submission.
- Required approvals.
- Date and time of provisioning.
- Technician responsible.
- Access role assigned.
- Any relevant verification performed.
- Any exception or escalation.

Screenshots may be attached where permitted and where they do not expose passwords, tokens or unnecessary personal information.

### Step 11 – Close the Ticket

Before closing the ticket, confirm that:

- All required approvals are present.
- Access was provisioned as approved.
- Least privilege was considered.
- Evidence has been captured.
- The user or manager has been notified.

Record the final status and close the ticket.

## 5. Emergency or Exceptional Access

Emergency access may be provided where delaying access could cause significant operational or security impact.

Emergency requests must still be documented.

Where normal approval is not immediately possible:

1. Record the emergency reason.
2. Obtain approval from an authorised emergency approver where available.
3. Grant the minimum required access.
4. Make the access temporary where possible.
5. Document the action taken.
6. Obtain retrospective review and approval as soon as practical.

Emergency access must not become a replacement for the normal access request process.

## 6. Record Retention and Audit Trail

Access requests and associated approval records must be retained according to NexusTech's record-retention requirements.

The audit trail should allow an authorised reviewer to determine:

- Who requested the access.
- Who approved it.
- What access was granted.
- Who provisioned it.
- When it was granted.
- Why it was required.

# EVIDENCE BUNDLE 4
# Policy Communication and Training Plan

## 6.1 AUP Rollout Plan

The objective of the rollout is not simply to send employees the policy. Employees should understand the rules, know where to find the policy and understand what is expected of them.

| Audience | Key Message | Channel | Owner | Timing | Acknowledgement | Success Measure |
|----------|-------------|---------|-------|--------|-----------------|-----------------|
| All Employees | The AUP defines acceptable and prohibited use of NexusTech systems and information. | All-hands session, email, intranet, mandatory learning module | Information Security Manager | Week 1 | Digital acknowledgement | ≥95% training completion |
| IT Staff | IT staff must support the policy through technical controls, approved software and access management. | Technical briefing + training session | IT Director / Security Manager | Week 1 | Attendance + acknowledgement | 100% IT staff completion |
| Managers | Managers are responsible for reinforcing policy expectations and supporting compliance within their teams. | Management briefing + email | HR + Information Security | Week 1 | Manager attestation | ≥95% manager acknowledgement |
| HR | HR supports communication and appropriate disciplinary action where policy violations involve employee conduct. | HR briefing | Information Security Manager | Week 1 | Meeting record | 100% HR completion |
| New Employees | Understanding acceptable use is part of onboarding and is required before normal system use. | Onboarding training | HR + IT | Ongoing | Digital acknowledgement | 100% onboarding completion |
| Contractors | Company systems must only be used for authorised business purposes and according to agreed requirements. | Contractor onboarding | Contract Owner / IT | Before access | Signed/digital acknowledgement | 100% before system access |

## 6.2 Rollout Timeline

### Day 1 – Announcement

The CEO or senior management announces the new policy and explains why the change is being made.

The announcement should emphasise that NexusTech has grown considerably and needs consistent security practices across the organisation.

### Days 2–3 – Policy Distribution

The policy is published on the company intranet or approved document repository.

Employees receive an email directing them to the policy and explaining the required training.

### Days 3–7 – Training

Employees complete a short mandatory learning module.

The training should include practical examples such as:

- Installing unauthorised software.
- Sharing passwords.
- Sending company information to personal email.
- Uploading sensitive files to personal cloud storage.
- Reporting phishing messages.
- Using company devices for personal activities.

### Day 7 – Knowledge Check

Employees complete a short knowledge assessment.

A target score of 80% or above should be used to demonstrate basic understanding.

Employees who do not meet the target should be given an opportunity to retake the assessment.

### Week 2 – Follow-up

The Information Security team reviews:

- Training completion.
- Policy acknowledgement.
- Knowledge-check results.
- Common questions.
- Areas where employees appear to be misunderstanding the requirements.

A short FAQ can then be published based on the issues identified.

## 6.3 Acknowledgement Mechanism

Employees should acknowledge the policy through the approved learning or HR platform.

The acknowledgement should confirm:

> "I confirm that I have read and understood the NexusTech Acceptable Use Policy and agree to comply with its requirements."

The acknowledgement record should include the employee, policy version and date of acknowledgement.

## 6.4 Rollout Effectiveness Measures

The following measures will be used:

### 1. Training Completion Rate

**Target:** ≥95% of existing employees complete the required training within the rollout period.

### 2. Policy Acknowledgement Rate

**Target:** ≥95% acknowledgement within the required timeframe.

### 3. Knowledge Check

**Target:** Average score of at least 80%.

### 4. Follow-up Questions and Incidents

The Security team should monitor recurring questions and AUP-related incidents after implementation.

A high number of similar misunderstandings may indicate that the policy or training material needs clarification.

## 6.5 Handling Non-Compliance

Employees who do not complete the required training should receive reminders through their manager and HR where appropriate.

Repeated failure to complete mandatory training may be escalated to the employee's manager and HR.

Where an employee repeatedly violates the policy, the matter should be investigated based on the seriousness of the violation and managed through the appropriate disciplinary or corrective process.

The objective should be both accountability and improvement, rather than treating every minor mistake as a disciplinary issue.

# EVIDENCE BUNDLE 5
# Policy Review and Maintenance Memo

---

**To:** Information Security Steering Committee  
**From:** Information Security Manager  
**Date:** 18 September 2027  
**Subject:** Review of Acceptable Use Policy Following Cloud Migration and Security Incident

---

NexusTech's Acceptable Use Policy should be reviewed following two significant changes to the organisation's risk environment. First, the migration of the primary database to AWS introduces new cloud infrastructure, access arrangements, storage locations and responsibilities that were not present when the current AUP was approved. The policy should therefore be checked to confirm that its requirements cover the use of cloud services and the protection of company and client information in cloud environments. Second, the incident involving an employee sharing a sensitive document through a personal cloud storage account demonstrates a practical gap in user behaviour and reinforces the need for clearer restrictions around personal cloud services and the transfer of sensitive information.

I recommend that the review involve Information Security, IT Operations, Cloud/Infrastructure, Legal or Compliance, HR and relevant business owners. The review should examine the incident report, access logs where appropriate, training results, user feedback and any identified control weaknesses. The AUP should be updated to explicitly prohibit the storage or sharing of sensitive company or client information through personal cloud storage accounts and to clarify that approved corporate cloud services must be used for business information. The policy should also make the responsibilities of employees using cloud-hosted systems clearer.

The revised policy should remain owned by the Information Security Manager and follow the normal approval route to the Information Security Steering Committee and CEO where required by the governance structure. I recommend an annual formal review, supported by earlier reviews following major technology changes, significant security incidents, major regulatory changes or material changes in the organisation's risk profile.

# 7. Overall Governance Considerations

The policy overhaul should not be treated as simply replacing the old "IT Rules" document with several new documents.

The bigger improvement is the introduction of document governance.

NexusTech should maintain a central policy register containing:

| Field | Example |
|-------|---------|
| Policy Name | Acceptable Use Policy |
| Document Owner | Information Security Manager |
| Version | 1.0 |
| Approval Authority | CEO |
| Effective Date | 18 September 2026 |
| Review Date | 18 September 2027 |
| Status | Approved |
| Classification | Internal |
| Related Standards | Endpoint Security Standard, Access Control Standard |
| Related Procedures | User Access Request Procedure |
| Exception Required | Yes |
| Next Review Trigger | Annual / material change |

This makes it easier for management to identify which documents are current and prevents old policies from continuing to circulate.

# 8. Conclusion

The policy review enables NexusTech to establish a more organized method of managing information security governance. By separating out the policies, standards, guidelines and procedures it becomes easier to see which requirements are mandatory and which offer recommendations or operational instructions.

The Acceptable Use Policy lays down what is expected of users, and the User Access Request Procedure turns the access-control requirements into a process which Helpdesk staff can apply in a consistent way. The communication plan is designed to promote adoption rather than merely relying on employees getting a PDF, and the review memo shows how the policy should react when there are changes to the technology, business operations or security risks.

In summary, the framework offered to NexusTech provides a basis which can be kept as the company grows, and it also enables a more consistent method of security governance while offering valuable evidence for future ISO/IEC 27001 and SOC 2 readiness activities.

---
# 9. REFERENCES

AICPA. (n.d.). *Trust services criteria*. American Institute of Certified Public Accountants. https://www.aicpa-cima.com/resources/download/trust-services-criteria

International Organization for Standardization. (2022). *ISO/IEC 27001:2022: Information security, cybersecurity and privacy protection — Information security management systems — Requirements*. https://www.iso.org/standard/27001

International Organization for Standardization. (2022). *ISO/IEC 27002:2022: Information security, cybersecurity and privacy protection — Information security controls*. https://www.iso.org/standard/75652.html

National Institute of Standards and Technology. (2024). *The NIST Cybersecurity Framework (CSF) 2.0*. U.S. Department of Commerce. https://www.nist.gov/cyberframework

National Institute of Standards and Technology. (2020). *Security and privacy controls for information systems and organizations (NIST Special Publication 800-53, Rev. 5)*. U.S. Department of Commerce. https://doi.org/10.6028/NIST.SP.800-53r5

---
# 10. AI Assistance Declaration

I used AI tools as a support resource while completing this practical laboratory. The assistance was mainly used for brainstorming, organising the report structure, improving wording and checking that the required evidence for each task was covered.

I reviewed the generated content and made decisions based on the NexusTech Solutions scenario, the requirements in the assessment brief and my understanding of information security governance. I remain responsible for the accuracy, relevance and final content of the submitted work.

| Item | Details |
|------|---------|
| **AI tool used** | ChatGPT, DeepSeek |
| **Purpose** | Brainstorming, structure, language support and review |
| **Final responsibility** | The submitted work was reviewed and approved by me before submission |

---

# Appendix A – Student Completion Checklist

- [x] I defined Policy, Standard, Guideline and Procedure correctly.
- [x] I classified all eight draft statements and justified each classification.
- [x] I created a hierarchy diagram.
- [x] I completed a full Acceptable Use Policy.
- [x] I completed a sequential User Access Request Procedure.
- [x] I completed a Communication and Training Plan.
- [x] I completed a Policy Review Memo.
- [x] I labelled all five evidence bundles clearly.
- [x] I checked my sources and references.
- [x] I completed any required AI declaration honestly.
