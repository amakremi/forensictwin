# ForensicTwin Ontology
The Forensic Twin Ontology is a structured knowledge framework designed to model and analyze cybersecurity incidents in cyber-physical systems (e.g., industrial IoT) by integrating digital twins with forensic investigation principles. It combines existing standards and novel components to enable automated detection of attacks, integrity validation, and compliance with forensic best practices.

## Key Features:

### Core Domains:

IoT/Industrial Systems: Models physical assets (e.g., PLCs, sensors) using IoT-Lite and SSN/SOSA for device metadata and sensor semantics.

Cybersecurity: Leverages UCO for observable objects (e.g., SecurityCheck, SecurityEvent) and role-based policies.

Forensic Logging: Extends CASE standards for tamper-evident logs (ForensicLog) with cryptographic chaining.

### Key Components:

- Digital Twin Representation:

- ForensicTwin: Digital replica of physical assets, linked to state hashes (hasStateHash, expectedStateHash).

- Security Verification: Classes like AuthenticityCheck, IntegrityViolation, and ReplayAttackDetected to classify incidents.

- Role-Based Access Control: Hierarchical roles (Admin, Auditor) and rules (hasAccess, restrictsAccessTo) for secure data access.

### Automation:

- SWRL Rules: Detect attacks (e.g., replay attacks via timestamp analysis, integrity violations via hash mismatches).

### Integration:

- Reuses CASE (logging), SSN/SOSA (sensors), UCO (cybersecurity semantics), and IoT-Lite (device metadata).

## Applications:
- Real-time integrity monitoring of industrial devices.

- Automated forensic analysis of cyber-physical incidents.

- Compliance with forensic standards for legal admissibility.

This ontology bridges IoT operations, cybersecurity, and digital forensics, enabling proactive defense and structured post-incident investigations.

## Citation :
Please refer to the following citation if you use the ontology or reference it:

### AMA Style
Akremi A. ForensicTwin: Incorporating Digital Forensics Requirements Within a Digital Twin. Computers. 2025; 14(4):115. https://doi.org/10.3390/computers14040115

### Chicago/Turabian Style
Akremi, Aymen. 2025. "ForensicTwin: Incorporating Digital Forensics Requirements Within a Digital Twin" Computers 14, no. 4: 115. https://doi.org/10.3390/computers14040115

### APA Style
Akremi, A. (2025). ForensicTwin: Incorporating Digital Forensics Requirements Within a Digital Twin. Computers, 14(4), 115. https://doi.org/10.3390/computers14040115
