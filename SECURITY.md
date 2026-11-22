# Vulnerability Disclosure and Security Policy

**Effective Date:** November 23, 2026  
**Organization:** The Lunar Org (`https://github.com/The-Lunar-Org`)

---

## 1. Commitment to Security

The Lunar Org considers the security and integrity of our open-source software, telemetry infrastructure, and community members paramount. We appreciate the invaluable contributions of security researchers and engineers who discover and report potential vulnerabilities in good faith.

---

## 2. Safe Harbor and Legal Immunity

The Lunar Org provides a comprehensive **Safe Harbor** for security research conducted in accordance with this policy:

### 2.1 Authorized Access
If you conduct vulnerability research and reporting in good faith and in full compliance with this policy:
- We consider your activities authorized under applicable computer fraud and abuse laws (including the U.S. Computer Fraud and Abuse Act (CFAA), 18 U.S.C. § 1030).
- We will not initiate, pursue, or support legal action against you for accidental, good-faith violations of this policy.
- We waive any anti-circumvention claims under copyright statutes (including Section 1201 of the Digital Millennium Copyright Act (DMCA)) for good-faith security research.

### 2.2 Conditions for Safe Harbor
To qualify for Safe Harbor protection, you must:
1. Cease research immediately upon confirming a vulnerability and do not access, alter, exfiltrate, or destroy user data or system integrity.
2. Maintain strict confidentiality regarding the vulnerability until public disclosure has been formally coordinated and remediated.
3. Not conduct denial-of-service (DoS/DDoS) attacks, spamming, social engineering, or physical security attacks against maintainers or hosting providers.
4. Report the issue promptly pursuant to Section 4 below.

---

## 3. Scope

### In Scope
- Repositories hosted under the official organization: `https://github.com/The-Lunar-Org/*`
- Official Discord telemetry gateways, webhooks, and bot services (`lunar-bot`)
- Community health configuration files and security workflows

### Out of Scope
- Third-party hosting infrastructure operated by GitHub or Discord.
- Issues without verifiable security impact (e.g., missing HTTP headers without practical exploitability).
- Denial of Service attacks or volumetric flooding against public endpoints.

---

## 4. Reporting Process

Please do **NOT** report security vulnerabilities through public GitHub issues, discussions, or public Discord channels.

### Preferred Reporting Channels
1. **GitHub Private Vulnerability Reporting**:
   Navigate to the **Security** tab of the impacted repository and select **"Report a vulnerability"**.
2. **Confidential Direct Disclosure**:
   Reach out directly to the Lead Maintainer:
   - **Dev:** [Himanshu Raj (@ItsHimanshu-Raj)](https://github.com/ItsHimanshu-Raj)
   - **Direct Inquiries:** Confidential communication channels designated on GitHub.

### Information Required
- Vulnerability description, severity classification (CVSS if available), and potential impact.
- Step-by-step reproduction instructions or a harmless minimal Proof-of-Concept (PoC).
- Proposed mitigation or patch code, if available.

---

## 5. Response Service Level Agreement (SLA)

- **Initial Acknowledgment:** Within forty-eight (48) hours of receipt.
- **Triage & Impact Assessment:** Within five (5) business days.
- **Remediation & Patch Deployment:** Target resolution within thirty (30) days depending on severity.
- **Public Disclosure:** Mutually coordinated following verification of the patch.

Thank you for upholding responsible disclosure and keeping our ecosystem secure.
