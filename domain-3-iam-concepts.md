# Domain 3: Identity and Access Management (IAM) Concepts

## 1. Identity Life Cycle Management (Objective 3.1)
* **Roles Definition:** Grouping permissions into standardized job roles aligned with business functions before assigning access to individual users or non-human identities.
* **Provisioning:** Creating accounts, assigning initial credentials and granting approved access rights during onboarding or role changes.
* **Access Review (Recertification):** Periodically auditing active permissions with data owners and managers to verify access remains appropriate and prevent privilege creep.
* **Deprovisioning (Offboarding):** Promptly revoking credentials, tokens and system access when personnel leave the organization, transfer roles or finish contract engagements.
* **IAM Frameworks and Tools:**
  * **Single Sign-On (SSO):** Enables one authentication event to grant access across multiple connected applications.
  * **Federated Identity Management (FIM):** Extends authentication across separate organizational trust boundaries using standards such as SAML, OAuth 2.0 and OpenID Connect (OIDC).
  * **Directory Services:** Centralized identity repositories (such as Active Directory or LDAP) that store user attributes and enforce authentication policies.
  * **Privileged Access Management (PAM):** Secures, monitors and rotates high-privilege administrative credentials using just-in-time (JIT) elevation and session recording.
  * **Multi-Factor Authentication (MFA):** Requires two or more independent authentication factors from knowledge (something you know), possession (something you have) or inherence (something you are).

## 2. Logical Access Controls (Objective 3.2)
* **Principle of Least Privilege (PoLP):** Granting users, applications and AI agents only the minimum permissions necessary to perform authorized tasks for the required duration.
* **Separation of Duties (SoD):** Dividing critical or sensitive tasks across multiple individuals so no single person can complete a high-risk process or conceal fraud alone.
* **Core Access Control Models:**
  * **Discretionary Access Control (DAC):** The resource owner determines who can access an object and what permissions they hold (using Access Control Lists).
  * **Mandatory Access Control (MAC):** Access is strictly enforced by the operating system based on security labels (classifications) and user clearances; users cannot override permissions.
  * **Role-Based Access Control (RBAC):** Access permissions are assigned to organizational roles rather than individual identities, simplifying onboarding and access reviews.
  * **Attribute-Based Access Control (ABAC):** Dynamic access decisions evaluated at runtime using policies combining user attributes, resource properties and environmental context (such as time, location or device posture).

## 3. Non-Human and AI Identity Governance
* **Service Accounts and API Keys:** Automated machine identities requiring vaulting, regular secret rotation and strict scope limits.
* **AI Agents and Bots:** Autonomous AI tools must be governed as non-human identities with explicit ownership, least-privilege boundaries, activity logging and timely deprovisioning.
