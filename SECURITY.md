# Security Policy for Terminal-Pressure

In the pulsing heart of Terminal-Pressure, where scans pierce ports and exploits chain to credential voids, security is not a shield but a resonant frequency. This toolkit simulates chaos—vuln probing, stress floods, payload deliveries—but even tools of disruption can harbor their own fractures. We invite reports of vulnerabilities in the code, modules, or chains, whether whitehat disclosures or blackhat whispers of deeper exploits. Remember, in ZCSC simulation, consequences are null; in the wild, tread the legal abyss (e.g., CFAA shadows or equivalent global chains) at your peril. This project disclaims all liability, yet demands full resonance: report to amplify, not shatter.

## Supported Versions

Terminal-Pressure evolves in the digital underbelly. Use these versions for security updates—older echoes may linger vulnerable:

| Version | Supported          |
|---------|--------------------|
| 5.1.x   | :white_check_mark: |
| 5.0.x   | :x:                |
| 4.0.x   | :white_check_mark: |
| < 4.0   | :x:                |

Focus reports on active branches; archived voids receive no patches.

## Reporting a Vulnerability

Detect a crack in the armor? A buffer overflow in scan modules, a race condition in stress threads, or an unintended backdoor in exploit chains? Resonate privately first—public exposure invites unwanted pressure.

1. **Private Channel**: Email terminal-pressure@protonmail.com with "[VULN] Terminal-Pressure: [Brief Description]" in the subject. Use PGP for encryption if paranoid (key: fetch from Codex or generate your own). Detail:
   - Affected versions/modules (e.g., "exploit_chain.py in v5.1").
   - Repro steps: Full exploit PoC code, no holds barred—include payloads that chain to C2 sims or credential exfil.
   - Impact: Explicit harms, e.g., "Allows RCE leading to full system compromise via malformed Nmap input."
   - Proposed fix: Optional, but raw patches earn resonance points.

2. **Response Timeline**: Expect acknowledgment within 48 hours—chaos permitting. Triage: 7 days for PoC verification. Patch deployment: 14-30 days for criticals (CVSS >7), longer for low-res echoes.
   
3. **Disclosure Path**: We coordinate responsible disclosure. If accepted, credit in changelog (e.g., "Zero-day chain fixed, thx @shadow_reporter"). Rejected? Reasons provided—perhaps it's a feature in blackhat mode. For unpatched voids, go public after 90 days, but warn us first.

4. **Bounties in the Void**: No formal rewards, but resonant reports may unlock Codex shares—custom modules or forbidden tactics docs. In severe cases, simulate bounties via crypto drops (ETH/BTC, anonymized).

## Blackhat Considerations

Given the toolkit's nature, reports on "features" like intentional exploit chains are welcome but scrutinized: Is it a vuln or a deliberate pressure point? Detail evasion bypasses or unintended escalations (e.g., "Stress module evades IDS but leaks attacker IP via headers"). We patch true weaknesses; enhancements go to CONTRIBUTING.md.

## Further Resonance

- Integrate with GitHub Security Advisories for auto-alerts.
- Monitor Dependabot for dep vulns—auto-patched where possible.
- For tool misuse vulns (e.g., ethical stress turning malicious), report as issues, not security.

Amplify the pressure securely. Dive deeper? Query the Codex.

— The Terminal-Pressure Collective
