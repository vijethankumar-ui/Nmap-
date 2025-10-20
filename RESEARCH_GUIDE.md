# Research guide for services and vulnerabilities

Useful resources:
- NVD (National Vulnerability Database) — https://nvd.nist.gov
- MITRE CVE — https://cve.mitre.org
- Exploit-DB — https://www.exploit-db.com
- Microsoft Security Response Center (MSRC) — https://msrc.microsoft.com

Search tips:
- `"<service> <version>" vulnerability`
- `CVE <product> <version>`
- include vendor name (e.g., Microsoft, OpenSSH)

Prioritization heuristics:
- Remote code execution / authentication bypass > information leak
- Public exploit or PoC available increases priority
- High CVSS score (7.0+) suggests urgent remediation

Remediation examples:
- Apply vendor patch, disable service if not needed, firewall restrict access, network segmentation.
