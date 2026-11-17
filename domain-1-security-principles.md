# Domain 1: Security Principles

## 1. Core Information Assurance Concepts
* **Confidentiality:** Preventing unauthorized disclosure of sensitive information through encryption, access controls and data classification.
* **Integrity:** Ensuring data remains accurate, complete and unaltered by unauthorized parties using hashing, digital signatures and change controls.
* **Availability:** Guaranteeing reliable and timely access to systems and data for authorized users through redundancy, backups and fault tolerance.
* **Non-Repudiation:** Providing undeniable proof of the origin and integrity of a message or transaction so a sender cannot deny performing an action.

## 2. Authentication, Authorization and Accounting (AAA)
* **Authentication:** Verifying the claimed identity of a user, device or AI agent using passwords, tokens, biometrics or certificates.
* **Authorization:** Determining what resources an authenticated identity is permitted to access and what actions it can perform.
* **Accounting (Auditing):** Tracking, logging and reviewing user activities and system events to maintain accountability and detect anomalies.

## 3. Risk Management Fundamentals
* **Key Definitions:**
  * **Asset:** Anything of value to an organization requiring protection.
  * **Threat:** Any potential event or actor capable of exploiting a vulnerability to cause harm.
  * **Vulnerability:** A weakness or gap in a system, process or control that a threat can exploit.
  * **Risk:** The likelihood of a threat exploiting a vulnerability combined with the resulting business impact.
* **Risk Assessment Approaches:**
  * **Qualitative:** Uses descriptive scales (Low, Medium or High) based on expert judgment and scenario analysis.
  * **Quantitative:** Assigns concrete financial values using formulas such as $\text{SLE} = \text{Asset Value} \times \text{Exposure Factor}$ and $\text{ALE} = \text{SLE} \times \text{ARO}$.
* **Risk Treatment Options:**
  * **Mitigation (Reduction):** Implementing controls to lower likelihood or impact to an acceptable level.
  * **Transference (Sharing):** Shifting financial liability to a third party via cyber insurance or outsourcing agreements.
  * **Avoidance:** Discontinuing the high-risk activity, system or business process entirely.
  * **Acceptance:** Formally acknowledging residual risk when the cost of mitigation outweighs the potential loss.

## 4. Security Controls
* **By Function:**
  * **Preventive:** Stops an incident before it occurs (firewalls, locks and encryption).
  * **Detective:** Identifies and alerts on active or past incidents (IDS, CCTV and audit logs).
  * **Corrective:** Restores systems to normal operation after an incident (backups, patching and malware removal).
  * **Deterrent:** Discourages attackers from attempting an intrusion (warning banners, fencing and security guards).
  * **Compensating:** Alternative measures used when a primary control is impractical or unavailable.
* **By Implementation Type:**
  * **Technical (Logical):** Implemented via hardware or software mechanisms.
  * **Administrative (Managerial):** Implemented via policies, procedures, training and background checks.
  * **Physical:** Implemented via tangible barriers, environmental controls and facility security.

## 5. Governance Hierarchy and Legal Principles
* **Policies:** High-level mandatory statements of management intent and organizational direction.
* **Standards:** Mandatory specific technical or operational requirements that enforce policies.
* **Procedures:** Step-by-step tactical instructions for executing tasks consistently.
* **Guidelines:** Recommended best practices offering flexibility rather than strict enforcement.
* **Due Care vs. Due Diligence:**
  * **Due Care:** Taking reasonable, prudent actions to protect assets and act responsibly ("doing what is right").
  * **Due Diligence:** Continuously researching, monitoring and verifying that controls remain effective ("verifying what is right").

## 6. ISC2 Code of Ethics (Exact Mandatory Order)
1. **Protect society, the common good, necessary public trust and confidence and the infrastructure.**
2. **Act honorably, honestly, justly, responsibly and legally.**
3. **Provide diligent and competent service to principals.**
4. **Advance and protect the profession.**

## 7. Foundational AI Security Principles
* **Model Integrity:** Protecting training pipelines and weights against data poisoning and adversarial manipulation.
* **Data Confidentiality:** Preventing sensitive corporate or personal data exposure via unapproved prompts or training leaks.
* **Non-Human Identity Governance:** Treating autonomous AI agents as privileged identities subject to least privilege and continuous monitoring.
