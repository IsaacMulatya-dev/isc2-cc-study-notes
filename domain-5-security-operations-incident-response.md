# Domain 5: Security Operations and Incident Response

## 1. Data Security (Objective 5.1)
* **Data Handling Lifecycle:**
  * **Classification:** Categorizing data based on sensitivity and business impact (Public, Internal, Confidential or Restricted for commercial organizations; Unclassified, Confidential, Secret or Top Secret for government).
  * **Labeling:** Applying physical tags or digital metadata markings so users and automated DLP tools recognize protection requirements.
  * **Masking:** Obfuscating sensitive fields (such as credit card numbers or PII) in non-production, analytics or AI training environments while preserving usable format.
  * **Sanitization and Disposal:** Permanently removing data before media reuse or disposal via cryptographic erasure, overwriting, degaussing or physical destruction (shredding or incineration).
* **Encryption and Cryptography:**
  * **Symmetric Encryption:** Uses a single shared secret key for fast bulk data encryption (AES); requires secure key exchange.
  * **Asymmetric Encryption:** Uses mathematically linked public and private key pairs (RSA or ECC) for key exchange, digital signatures and non-repudiation.
  * **Hashing:** One-way mathematical algorithms (SHA-256 or SHA-3) generating fixed-length digests to verify data integrity without reversing back to plaintext.
  * **Quantum-Resistant Cryptography:** Post-quantum cryptographic (PQC) algorithms designed to withstand attacks from large-scale quantum computers capable of breaking traditional RSA and ECC schemes.

## 2. Security Operations (Objective 5.2)
* **Logging and Monitoring:** Collecting centralized audit trails across endpoints, servers, firewalls and cloud platforms into a SIEM (Security Information and Event Management) system for real-time visibility.
* **Security Event Triage:**
  * **Correlation:** Linking related telemetry across multiple sources to distinguish true attacks from benign anomalies.
  * **Prioritization:** Ranking alerts by asset criticality, threat severity and potential business impact using defined incident use cases.
* **Threat Landscape and Intelligence:**
  * **Threat Actors and Motivations:** Nation-state actors (espionage or disruption), cybercriminals (financial gain), hacktivists (ideological causes), insider threats (malicious intent or negligence) and script kiddies.
  * **Cyber Threat Intelligence (CTI):** Actionable indicators of compromise (IoCs), tactics, techniques and procedures (TTPs) shared across feeds and ISACs to anticipate attacks.
  * **Threat Frameworks:** Structured knowledge bases (such as MITRE ATT&CK or the Cyber Kill Chain) used to map adversary behavior and identify defensive gaps.

## 3. Incident Response (Objective 5.3)
* **Incident Response Plan (IRP) Lifecycle:** Preparation, Detection and Analysis, Containment, Eradication, Recovery and Post-Incident Activity (Lessons Learned).
* **Data Handling Policy in IR:** Preserving digital forensics evidence integrity through strict chain-of-custody documentation, write-blockers and cryptographic hashing of captured images.
* **Incident Response Exercises:**
  * **Tabletop Exercises:** Discussion-based walkthroughs where stakeholders simulate an incident scenario to test decision-making and communication workflows without disrupting live systems.
  * **Functional and Full-Scale Simulations:** Hands-on technical drills testing SOC playbooks, containment procedures and escalation paths under realistic time pressure.

## 4. Asset Protection (Objective 5.4)
* **Asset Lifecycle Management:** Tracking hardware, software and cloud resources from procurement and baseline deployment through maintenance to secure decommissioning.
* **End-of-Life (EOL) and End-of-Support (EOS):** Identifying unsupported systems that no longer receive security patches and isolating, upgrading or replacing them to eliminate unmitigated exposure.
* **Configuration and Change Management:**
  * **Hardening and Baselines:** Disabling unnecessary services, removing default accounts and applying CIS Benchmarks to establish secure standard configurations.
  * **Change Management:** Requiring formal impact assessments, approvals, testing and rollback plans before modifying production systems.

## 5. Security Testing (Objective 5.5)
* **Security Readiness Testing:**
  * **Red Team:** Offensive specialists emulating real-world adversaries to test detection and response capabilities.
  * **Blue Team:** Defensive analysts monitoring, detecting and defending organizational infrastructure against intrusions.
  * **Purple Team:** Collaborative exercises uniting red and blue teams to rapidly tune detection rules and close defensive gaps.
* **Application Security Testing:**
  * **Vulnerability Scanning:** Automated inspection identifying known CVEs and misconfigurations across hosts and applications.
  * **Static Analysis (SAST):** White-box testing inspecting source code or binaries for flaws without executing the program.
  * **Dynamic Analysis (DAST):** Black-box testing evaluating running applications from the outside to uncover runtime vulnerabilities.
  * **Threat Modeling:** Proactively identifying architectural weaknesses and attack surfaces during application or AI system design.
* **Physical Penetration Testing:** Assessing facility perimeter and human defenses through pretexting, impersonation, tailgating or piggybacking and phishing assessments.
