# Step-by-step network reconnaissance playbook (Windows, Git Bash)

This document assumes you've already:
- Installed Nmap and run an initial scan of your local network (e.g., `nmap -sS 192.168.1.0/24`).
- Collected pcap with Wireshark (optional).

Follow the one-step-at-a-time workflow (ask your assistant for the next step after completing each):

**Step 6 (research services)** — completed by you.
**Step 7 (identify & prioritize risks)** — next after your confirmation.

## What the repository provides
- `scripts/parse_nmap.sh` — extracts open ports and basic service info.
- `templates/host-research-template.md` — template for documenting CVEs and mitigations.
- `docs/RESEARCH_GUIDE.md` — how to look up CVEs, use NVD, Exploit-DB, vendor advisories.

## Safety and legal notes
- Only scan networks and hosts you own or have explicit permission to test.
- Treat any discovered credentials or sensitive data as confidential.
