# Threat Intelligence Frameworks

## MITRE ATT&CK Overview
- The MITRE ATT&CK framework is a globally recognized knowledge base that documents adversary tactics, techniques, and procedures (TTPs) observed in real-world attacks.
- It organizes attacker behavior into a matrix of tactics (the "why") and techniques (the "how"), covering platforms such as Windows, Linux, macOS, cloud, mobile, and industrial control systems. Security teams use ATT&CK to map detections, conduct threat hunting, and simulate adversary actions.
- For example, if an attacker uses credential dumping, analysts can reference ATT&CK Technique T1003 to understand detection methods and mitigation strategies.
- The framework provides a common language that aligns defenders, vendors, and researchers.

## Cyber Kill Chain
- The Cyber Kill Chain, developed by Lockheed Martin, is a model that describes the stages of a cyberattack from initial reconnaissance to achieving the attacker’s objectives.
- The seven stages are: reconnaissance, weaponization, delivery, exploitation, installation, command and control, and actions on objectives.
- The purpose of the kill chain is to help defenders identify opportunities to disrupt an attack at each stage.
- For instance, detecting phishing emails during the delivery stage can prevent exploitation and installation of malware.
- The model emphasizes breaking the chain early to minimize damage.

## Threat Modeling Concepts
- Threat modeling is the process of systematically identifying, analyzing, and prioritizing potential threats to a system or application.
- It involves understanding what assets need protection, who the adversaries are, and how they might attack.
- Common approaches include STRIDE (Spoofing, Tampering, Repudiation, Information Disclosure, Denial of Service, Elevation of Privilege) and DREAD (Damage, Reproducibility, Exploitability, Affected Users, Discoverability).
- Threat modeling helps organizations design security controls proactively rather than reactively.
- For example, modeling a web application may reveal that input validation is critical to prevent SQL injection attacks.

## Attack Mapping
- Attack mapping is the practice of aligning observed attacker behavior with established frameworks such as MITRE ATT&CK or the Cyber Kill Chain.
- It allows analysts to understand where an attack fits within known tactics and techniques, making detection and response more structured.
- For example, if logs show PowerShell execution followed by credential dumping, analysts can map these actions to ATT&CK techniques under the Execution and Credential Access tactics.
- Attack mapping provides clarity, helps identify gaps in detection, and supports incident response by showing the full picture of adversary activity.

## Threat Categorization
- Threat categorization is the process of classifying threats based on attributes such as actor type, motivation, capability, and impact.
- Categories may include cyber criminals, nation-state actors, hacktivists, insiders, or advanced persistent threats.
- Categorization helps organizations prioritize risks and tailor defenses to specific adversaries.
- For example, insider threats may require stronger access controls, while nation-state actors may demand advanced monitoring and resilience planning.
- By categorizing threats, defenders can allocate resources effectively and ensure that security strategies address the most relevant risks.

## Summary
- Threat intelligence frameworks provide structured approaches to understanding and defending against cyber threats.
- MITRE ATT&CK offers a detailed knowledge base of adversary techniques, the Cyber Kill Chain outlines the stages of an attack, threat modeling concepts help identify risks proactively, attack mapping aligns observed activity with known frameworks, and threat categorization organizes adversaries by type and motivation.
- Together, these frameworks enable organizations to anticipate attacks, strengthen defenses, and respond effectively to incidents.
- They serve as essential tools for SOC analysts, incident responders, and decision-makers in building a resilient cybersecurity posture.
