# Privacy Policy

**Effective Date:** November 23, 2026  
**Data Controller:** The Lunar Org (`https://github.com/The-Lunar-Org`)

---

## 1. Introduction and Scope

The Lunar Org ("we", "us", or "our") is committed to data privacy, minimal data collection, and transparency. This Privacy Policy outlines our legal obligations and practices concerning the collection, storage, processing, and protection of information across our repositories, GitHub webhooks, Discord integrations (`lunar-bot`), and community communication channels.

We operate under a fundamental privacy principle: **Collect only what is technically necessary to operate, and retain nothing extraneous.**

---

## 2. Information We Collect

### 2.1 Discord Bot Telemetry (`lunar-bot`)
When you interact with our Discord bot or open a support ticket/modmail thread, the following data may be processed in transient runtime memory:
- **Discord Metadata:** User ID, Guild/Server ID, Channel ID, and Message Timestamps.
- **Support / Modmail Content:** Message content submitted specifically through modmail direct messages or designated ticket channels for the sole purpose of resolving support requests.
- **Runtime Commands:** Execution records for slash commands (`/status`, `/reply`, `/close`).

### 2.2 GitHub Webhook Events
When GitHub webhook events are dispatched to our telemetry listener:
- Event payloads (commits, branch references, PR numbers, commit authors, CI status updates) are verified via cryptographic HMAC-SHA256 signatures and routed to Discord channels.
- We do **not** store or persist GitHub credentials, private repository tokens, or codebase intellectual property.

---

## 3. How We Use Information

Information processed by our software is strictly utilized for:
- Delivering automated notifications of code changes and pull requests.
- Facilitating direct communication between users and community maintainers via support tickets.
- Monitoring system latency, health, and gateway availability.

**We do NOT sell, lease, monetize, broker, or trade personal data or telemetry records to any third party for advertising, profiling, or analytical commercialization.**

---

## 4. Legal Basis for Processing (GDPR Compliance)

For individuals located within the European Economic Area (EEA) and United Kingdom, we process personal data under the following legal bases pursuant to Article 6 of the General Data Protection Regulation (GDPR):
- **Legitimate Interests:** To provide secure, reliable, and functional open-source operations and community support.
- **Consent:** When you voluntarily submit direct messages or support tickets to our modmail system.

---

## 5. Data Retention and Deletion

- **Transient In-Memory Data:** Bot memory objects, routing tables, and ephemeral event caches are purged automatically upon task completion or bot process restarts.
- **Discord Audit Logs:** Support ticket channel logs remain within the designated Discord server channels until archived or deleted by authorized administrators.
- **Right to Erasure (GDPR Art. 17 / CCPA):** You have the right to request deletion of any ticket history or records containing your Discord User ID. Such requests will be honored within thirty (30) days of receipt.

---

## 6. Security Safeguards

We implement industry-standard technical and organizational security measures, including:
- Cryptographic verification (`X-Hub-Signature-256` HMAC-SHA256) for all incoming webhooks to prevent spoofing or unauthorized payload delivery.
- TLS 1.3 encryption in transit for all external network communications.
- Principle of least privilege for Discord bot permissions (OAuth2 scopes restricted strictly to required actions).

---

## 7. Third-Party Services

Our software interfaces with third-party service providers subject to their respective privacy terms:
- **GitHub:** [GitHub Privacy Statement](https://docs.github.com/en/site-policy/privacy-policies/github-privacy-statement)
- **Discord:** [Discord Privacy Policy](https://discord.com/privacy)

---

## 8. Privacy Inquiries and Data Subject Requests

To exercise your privacy rights or request data deletion, contact:
- **Lead Maintainer:** Himanshu Raj (@ItsHimanshu-Raj)
- **Discord:** [discord.gg/hSvuG9bcFN](https://discord.gg/hSvuG9bcFN)
