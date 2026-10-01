# Indicators of Compromise (IOCs)

## What are IOCs
- Indicators of Compromise are pieces of forensic evidence that suggest a system or network has been breached or malicious activity has occurred.
- They are used by security teams to detect, investigate, and respond to incidents.
- IOCs provide clues about attacker behavior and help analysts confirm whether an environment has been compromised.
- They are critical in threat hunting, incident response, and building detection rules in SIEM and EDR platforms.

## Malicious IP Addresses
- Malicious IP addresses are network locations known to be associated with attackers, botnets, or command-and-control servers.
- They can indicate that a system is communicating with hostile infrastructure.
- For example, repeated failed login attempts from the same IP or outbound traffic to blacklisted ranges are strong signs of compromise.
- Security teams use firewalls and intrusion detection systems to block or monitor these IPs, reducing the risk of ongoing attacks.

## Domains
- Malicious domains are web addresses controlled by attackers.
- They are often used for phishing, malware distribution, or command-and-control communication.
- For instance, a domain may host fake login pages to steal credentials or deliver malicious software disguised as legitimate updates.
- Detecting requests to suspicious domains in proxy or DNS logs helps analysts identify compromised systems and prevent further damage.

## URLs
- Malicious URLs are specific web links that direct users to harmful content.
- Unlike domains, URLs point to exact resources such as phishing pages, malware downloads, or exploit kits.
- For example, a phishing email may contain a URL that looks legitimate but redirects to a fraudulent login page.
- Monitoring and blocking known malicious URLs helps prevent users from accessing dangerous content and reduces the risk of credential theft or malware infection.

## File Hashes
- File hashes are unique cryptographic fingerprints of files, generated using algorithms such as MD5, SHA‑1, or SHA‑256.
- Malicious file hashes identify malware, trojanized installers, or other harmful executables.
- For example, if a file hash matches one listed in a threat intelligence feed, it indicates that the file is malicious.
- Security teams use file hashes to detect malware across endpoints and ensure that infected files are quarantined or removed.

## Email Indicators
- Email indicators are signs of malicious activity within email communications.
- They include suspicious sender addresses, subject lines, attachments, or embedded links.
- For example, an email sent from a domain that closely resembles a legitimate company but contains a malicious attachment is a strong indicator of compromise.
- Analysts monitor email headers, attachment types, and embedded URLs to detect phishing campaigns and prevent users from falling victim to social engineering attacks.

## Summary
- Indicators of Compromise are essential tools for detecting and confirming security incidents.
- Malicious IP addresses reveal hostile network sources, domains and URLs expose phishing and malware distribution, file hashes identify known malware, and email indicators highlight social engineering attempts.
- By collecting and analyzing IOCs, organizations can strengthen their defenses, respond quickly to incidents, and reduce the impact of cyberattacks.
- IOCs act as the footprints left behind by adversaries, guiding defenders in uncovering and mitigating threats.
