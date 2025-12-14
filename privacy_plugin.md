# Privacy Policy (Plugin & Service) - Door to Isekai

**Version 1.7** | Last Updated: 2025-11-28

## Controller (Data Controller)
*   **Name:** Isekai Travel
*   **Country:** Republic of Korea
*   **Address:** Giheung-gu, Yongin-si, Republic of Korea

## 1. Introduction & No Account Policy
We do not require you to create an account or register to use the Portal. Our service operates on an **anonymous, session-based model**. Session IDs are temporary and are not linked to any personal profile or persistent user account.

## 2. Information We Collect

### Automatically Collected (Local & Server):
*   Session ID (temporary identifier)
*   Connection timestamps and status
*   Tool execution logs (metadata: tool name, success/fail, timestamp)

### User-Provided (Local-First):
*   **Unreal Engine Project Data:** Processed locally on your machine. It is **NOT** collected by our backend servers. It is transmitted to third-party External Services **ONLY** when you:
    *   Manually upload tool responses
    *   Use "Review & Send" or "Auto-Send" modes
*   **Commands & Prompts:** Sent to the External Service you selected.

## 3. Legal Basis for Processing
We process your information based on:
*   **Contract Performance:** To provide the Portal service you requested
*   **Legitimate Interest:** Service improvement, security monitoring, abuse prevention
*   **Consent:** For optional features or data processing beyond core service

## 4. How We Use Your Information
*   To facilitate portal activation and authentication
*   To route your requests to External Services only when you opt in (connectors) or manually upload MCP responses; otherwise processed locally
*   To monitor service health and performance
*   To detect and prevent abuse

## 4.1 Roles and Responsibilities
We act as the **Data Controller** for the local portal (session management, basic logs). Connected External Services (e.g., OpenAI, Anthropic) typically act as **independent controllers** for data you choose to transmit to their services via MCP tools.

## 5. Information Sharing & International Transfer
**We share your data with:**
*   **External Service Providers (e.g., LLM Services):** Your Unreal Engine project data (blueprints, C++ code, assets) may be transmitted to third-party External Services providers **ONLY** when you initiate transmission (manual upload, Review & Send, or Auto-Send).
    *   **OpenAI** (ChatGPT) - United States
    *   **Anthropic** (Claude) - United States
    *   **Google** (Gemini) - United States
*   **AWS:** Our backend infrastructure is hosted on AWS us-east-1 (United States) for portal activation and logging (metadata only).

### External Service Provider Data Usage Policies:
**Important:** Each External Service provider has independent control over your data.

## 5.1 MCP Tool Response Local Storage (Privacy-by-Design)
**Important:** To minimize data exposure risks, MCP tool responses are **saved locally** on your machine.

*   **Default Behavior:** No automatic transmission to any server.
*   **User Control:** Transmission occurs only via user action (Manual Upload, Review & Send, Auto-Send).
*   **Auto-Send Mode:** If enabled (opt-in), responses are sent automatically for a limited time (1 hour). This mode can be disabled at any time.
*   **Auto-Deletion:** Local files are deleted after 1 hour or on Editor shutdown.

### Clipboard Security Notice:
When using the Web UI's clipboard copy feature:
*   Clipboard is a shared OS resource accessible to other applications
*   First-use security warning dialog is shown
*   Post-copy reminder to clear clipboard after use
*   Your responsibility to manage clipboard security

Clipboard copy is a local-only feature. We do not send or store clipboard contents on our backend.

### Manual Clear Clipboard
The Web UI includes a **Clear Clipboard** button (in the History panel) so you can manually clear clipboard contents at any time. There is **no automatic clearing** to avoid silently overwriting user data.

### User Responsibility & Shared Responsibility Model:
**System Provides:**
*   Reasonable security measures (local storage, auto-deletion, path filtering)
*   Clear security notices and warnings
*   Size limits (1MB for automatic transmission, 5MB for file downloads) and rate limiting for API access

**User Responsible For:**
*   Copy & paste actions to External Services
*   Clipboard management and clearing
*   Understanding clipboard is a shared resource
*   Reviewing External Service provider policies before uploading data
*   Managing transmission mode settings (Manual Upload, Review & Send, Auto-Send)
*   Disabling Auto-Send mode when no longer needed

## 6. Data Retention & Deletion
**Retention Periods:**
*   **Session data:** Maximum 7 days (SESSION_MAX_TTL), automatically deleted upon expiration
*   **Connection logs:** 30 days, then automatically purged
*   **Tool execution logs:** Retained for debugging, purged after 30 days or upon service termination
*   **Consent evidence (S3):** 60 days by default

**Deletion Criteria:**
Data is deleted when: (a) retention period expires, (b) you request deletion, (c) service is terminated, or (d) no longer necessary for stated purposes. Deletion is performed securely and irreversibly.

## 7. Your Rights & How to Exercise Them
You have the following rights regarding your data:

### Rights:
*   **Access:** Request a copy of your data
*   **Rectification:** Correct inaccurate data (contact us)
*   **Erasure ("Right to be Forgotten"):** Request deletion of your data
*   **Restriction:** Request limitation of processing
*   **Data Portability:** Receive your data in machine-readable format
*   **Object:** Object to processing based on legitimate interest
*   **Withdraw Consent:** Disconnect session at any time

### How to Exercise Rights:
*   **Contact:** Email us at [isekaitravel.pathfinder@gmail.com](mailto:isekaitravel.pathfinder@gmail.com) for privacy requests
*   **Response Time:** We will respond within 30 days (GDPR standard)

### Complaints:
If you are not satisfied with our response, you have the right to lodge a complaint with your local data protection authority.

## 8. Third-Party Services
This Portal connects to External Services. Each service has its own privacy policy:
*   OpenAI: https://openai.com/privacy
*   Anthropic: https://www.anthropic.com/privacy
*   Google (Gemini): https://policies.google.com/privacy

We recommend reviewing their policies before transmitting sensitive information.

## 9. Security Measures
*   TLS 1.2+ encryption for all transmissions
*   Local portal activation uses a 12-digit time-limited code
*   OAuth/JWT may be used for the separate ChatGPT connector (not for local activation)
*   Rate limiting to prevent abuse
*   Localhost-only web interface binding

**Zero Data Retention (Relay):** When transmitting data to External Services via our backend relay, we employ a "Zero Data Retention" policy. The data payload is encrypted in transit and is strictly relayed without being stored on our backend servers.

While we apply reasonable technical and organizational measures, we cannot guarantee absolute security of any transmission over the Internet or method of electronic storage.

## 10. Children's Privacy
This service is intended for developers 13+ years old. We do not knowingly collect data from children under 13.

## 11. Changes to Privacy Policy
We may update this policy. Material changes will be notified through the Portal interface. Continued use constitutes acceptance of the updated policy.

## 12. Contact & Data Protection Officer
For privacy-related questions, data subject rights requests, or complaints, contact us via:
*   **Email:** [isekaitravel.pathfinder@gmail.com](mailto:isekaitravel.pathfinder@gmail.com)
*   **GitHub Issues:** [https://github.com/LSG7/UnrealEngine-AI-Bridge-Door-to-isekai/issues](https://github.com/LSG7/UnrealEngine-AI-Bridge-Door-to-isekai/issues) (preferred for tracking)
*   **Response Time:** Within 30 days as required by GDPR

We will respond to all legitimate requests within the timeframe required by applicable law.

## 13. Supervisory Authority
If you are in the EU/EEA or South Korea, you have the right to lodge a complaint with:
*   **EU/EEA:** Your local Data Protection Authority
*   **South Korea:** Personal Information Protection Commission (PIPC) - https://www.pipc.go.kr

## 14. Regional Specific Rights & Notices

### For EU/EEA/UK Residents (GDPR/UK GDPR)
*   **Legal Basis:** Consent (Article 6(1)(a) GDPR) and Legitimate Interest (Article 6(1)(f))
*   **Data Minimization:** We only process data necessary for the specific MCP tool operation you request
*   **Right to Withdraw Consent:** You may withdraw consent at any time without affecting the lawfulness of processing before withdrawal
*   **Data Protection Officer:** Contact at isekaitravel.pathfinder@gmail.com
*   **Cross-Border Transfer Safeguards:** Standard Contractual Clauses (SCCs) where applicable

### For California Residents (CCPA/CPRA)
**Your California Privacy Rights:**
*   **Right to Know:** You have the right to request what personal information we collect, use, disclose, and sell
*   **Right to Delete:** You may request deletion of your personal information
*   **Right to Opt-Out:** We do not sell personal information, but you have the right to opt-out if this changes
*   **Right to Non-Discrimination:** We will not discriminate against you for exercising your privacy rights
*   **Categories of Information Collected:**
    *   Identifiers (session ID, machine ID)
    *   Internet activity (connection logs, tool usage)
    *   Professional information (project data)
*   **"Do Not Sell My Personal Information":** While we do not sell data, you may make a request at isekaitravel.pathfinder@gmail.com

### For Canadian Residents (PIPEDA)
*   **Meaningful Consent:** We obtain your express consent for cross-border data transfers to External Services
*   **Purpose Limitation:** Data is only used for processing by External Services as described
*   **Accountability:** We remain responsible for data transferred to third parties

### For Australian Residents (Privacy Act)
*   **APPs Compliance:** We comply with the Australian Privacy Principles
*   **Overseas Disclosure:** Your data will be disclosed to entities in the United States
*   **Correction Rights:** You may request correction of inaccurate information

### For Japanese Residents (APPI)
*   **Purpose of Use:** AI & Tool-assisted development as specified
*   **Foreign Transfer:** Data transferred to US with your consent
*   **Disclosure Requests:** Contact isekaitravel.pathfinder@gmail.com

### For Brazilian Residents (LGPD)
*   **Legal Basis:** Consent for international transfer
*   **Your Rights:** Access, correction, deletion, portability, and objection
*   **International Transfer:** Based on your express consent

### For Chinese Residents
**Service Limitation:** Due to data localization requirements under PIPL, this service is currently not available for users in mainland China. Users from Hong Kong SAR and Macau SAR may use the service subject to their local laws.

### For Indian Residents (DPDP Act)
*   **Consent:** Your explicit consent is obtained for data processing
*   **Data Principal Rights:** Access, correction, erasure, and grievance redressal
*   **Age Restriction:** Service only available for users 18 years and above

## Intellectual Property Notice
Unreal® is a trademark or registered trademark of Epic Games, Inc. in the United States of America and elsewhere.
Unreal® Engine, Copyright 1998 – 2025, Epic Games, Inc. All rights reserved.

This service is a third-party tool and is not affiliated with, endorsed by, or sponsored by Epic Games, Inc.
