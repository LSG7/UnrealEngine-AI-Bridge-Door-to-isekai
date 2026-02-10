# Terms of Service - Door to Isekai

**Version 2.0** | **Last Updated: 2026-02-11**

---

## 1. Service Description

Door to Isekai ("the Portal") is a development tool that connects your Unreal Engine editor to AI services (GPT, Claude, Gemini, etc.) through encrypted channels. Your project data and commands may be transmitted when you opt in (connectors) or manually upload MCP responses; there is no automatic transmission.

The local portal uses a **12-digit, time-limited activation code** to enable MCP tools on your machine. OAuth/JWT may be used *only* for connecting to external AI services (e.g., ChatGPT, Claude, Gemini, local LLMs) and is not required for local portal activation.

## 2. Security Protections

### What We Provide:
*   HTTPS/WSS encryption for all data in transit
*   TLS 1.3 preferred with industry-standard ciphers
*   Certificate validation for backend connections
*   **HSTS (Strict-Transport-Security)** and HTTPS-only (HTTP blocked)
*   Localhost-only web interface (127.0.0.1)
*   Activation via 12-digit time-limited code for local portal

### What We Cannot Protect:
If your computer has been compromised by malware, hacking, or unauthorized access **("conquered by a Demon Lord" - i.e., third-party illegal system intrusion and loss of device control)**, our encryption cannot prevent data exposure at the device level. The attacker already controls your system before data enters our protection.

We also cannot control untrusted networks (e.g., rogue Wi‑Fi). We enforce HTTPS-only, HSTS, and certificate validation/pinning to mitigate MITM/SSL stripping, but your network environment remains outside our control.

## 3. Limitation of Liability

**TO THE EXTENT PERMITTED BY LAW, WE ARE NOT LIABLE FOR:**
*   Data breaches caused by compromised, hacked, or malware-infected user devices
*   Security incidents resulting from user's failure to maintain device security
*   Damages from third-party attacks on user's computer or network
*   Losses from user's installation of untrusted software or negligent security practices
*   Vulnerabilities in user's operating system, browser, or other software

**DAMAGE SCOPE:** To the extent permitted by law, we are liable only for reasonably foreseeable, direct damages. All indirect, special, incidental, punitive, and consequential damages (including lost profits, loss of data, or business interruption) are excluded.

**LIABILITY CAP:**
To the extent permitted by law, our total aggregate liability for all claims arising out of or relating to the services shall not exceed the greater of **(a) USD $20** and **(b) the total amounts paid by you to us for the Services during the twelve (12) months preceding the event giving rise to liability**.

**EXCEPTIONS (We Remain Liable For):**
*   Intentional misconduct or gross negligence on our part
*   Violations of mandatory consumer protection laws
*   Personal injury or death caused by our product defects
*   Breaches of applicable data protection regulations (GDPR, etc.) within our control

## 4. Your Responsibilities

You agree to:
*   Maintain your device security (anti-virus, firewall, OS updates)
*   Use strong passwords and enable two-factor authentication where available
*   Avoid installing untrusted software or visiting malicious websites
*   Promptly address security warnings from your operating system or security software
*   Not transmit confidential or regulated information (PII, trade secrets, etc.) without proper safeguards

**Always backup your project (Version Control) before running automated tools. We are not responsible for irreversible data loss.**

## 4.1 User Eligibility & Age Requirements

**This service is a professional development tool intended for software developers.**

**Minimum Age Requirements by Region:**
*   **United States:** 13 years (COPPA compliance)
*   **European Union/EEA:** 13-16 years (depending on country specific laws)
*   **South Korea:** 14 years
*   **Japan:** 13 years
*   **Australia:** 13 years
*   **Canada:** 13 years (varies by province)
*   **Brazil:** 13 years
*   **India:** 18 years (DPDP Act requirement)
*   **China:** Service not available (see Privacy Policy Section 13)

**Age Verification and Parental Consent:**
*   By using this Portal, you confirm that you meet the minimum age requirement for your region
*   If you are under 18 (or the age of majority in your jurisdiction), you must have parental or guardian consent
*   We do not knowingly collect information from anyone below the minimum age without parental consent
*   If we discover a user is below the minimum age, we will immediately terminate their access and delete their data

**Professional Use Declaration:**
This service processes professional development content (source code, project files). Users represent that they have the legal right to transmit any project data to External Services.

## 4.2 Indemnification

To the fullest extent permitted by applicable law, you agree to indemnify, defend, and hold harmless **Door to Isekai**, its developers, affiliates, officers, directors, employees, agents, and licensors (collectively, the "Indemnified Parties") from and against any and all claims, damages, obligations, losses, liabilities, costs, and expenses (including but not limited to reasonable attorney's fees) arising from or related to:

*   Your access to or use of the Service, including any data, content, or work product (e.g., code, assets) you generate, transmit, or display using the Service;
*   Your violation of these Terms of Service;
*   Your violation of any third-party right, including without limitation any copyright, property, or privacy right;
*   Any claim that your content caused damage to a third party.

This defense and indemnification obligation will survive these Terms of Service and your use of the Service. You agree to cooperate as fully as reasonably required in the defense of any claim. We reserve the right to assume the exclusive defense and control of any matter otherwise subject to indemnification by you, and you shall not in any event settle any matter without our written consent.

## 5. Data Transmission Notice

By using the Portal, you acknowledge and agree that:
*   **Local by Default:** Your Unreal Engine project data (blueprints, C++ code, assets) is processed locally. It is **NOT** transmitted to External Services automatically by default.
*   **User-Initiated Transmission:** Transmission to External Services (e.g., ChatGPT, Claude) occurs only when you:
    *   Manually copy/upload MCP tool responses
    *   Explicitly enable "Auto-Send" mode (opt-in, time-limited)
    *   Use the "Review & Send" feature to approve specific responses
*   **Local Direct Connections:** You may connect local MCP clients directly via localhost. In this case, data bypasses our backend relay.
*   **Third-Party Services:** Data is transmitted to **External Services or local tools that YOU explicitly connect and configure**. We do not control these services.
*   **Provider Independence:** Each External Service provider is an independent entity with its own terms and privacy policy.
*   **Your Responsibility:** You should review each External Service provider's terms and privacy policy before transmitting sensitive or confidential information.
*   **International Transfer:** If you choose to transmit data, it will be transferred to the United States and other countries where External Service providers operate.

## 5.1 MCP Tool Response Local Storage

**Privacy-by-Design Approach:** To minimize data exposure risks, MCP tool responses are saved locally on your machine.
*   **Local Files:** Responses are saved to `Saved/MCPResponse/` in your project.
*   **No Auto-Upload:** The system does NOT upload these files to any server automatically.
*   **Auto-Deletion:** Files are deleted after 1 hour or when the Editor closes.
*   **Path Filtering:** Absolute paths are converted to relative paths to hide your system structure.

**Note:** While we apply sensitive data filtering, error messages may inherently contain specific file names or partial paths necessary for debugging.

## 5.2 Transmission Modes (Auto-Send & Review)

The Portal offers optional modes to streamline your workflow. These are **disabled by default**.
*   **Review & Send (Recommended):** Allows you to preview the tool response locally and explicitly click "Send".
*   **Auto-Send (Opt-in):** Automatically transmits tool responses for a limited time (1 hour). Requires explicit activation and consent.

## 5.3 Tool Execution Approval

To prevent unintended changes to your project, the system enforces a **Tool Execution Approval** flow by default.
*   **Default ON:** All MCP tool executions require your manual approval in the Web UI.
*   **User Control:** You can Approve or Deny any execution request.
*   **Timeout:** Pending requests automatically expire if not approved within a set time.
*   **Opt-Out:** You may disable this protection (Auto-Run), but doing so increases the risk of unintended project modifications.

## 5.4 AI Output & Development Tool Disclaimer

**Nature of Service:** This service is strictly a **development aid tool**. It is NOT a runtime library intended to be shipped with your final game or application.

*   **Verification Responsibility:** You acknowledge that AI-generated code, blueprints, or assets may contain errors, bugs, security vulnerabilities, or hallucinations. You are solely responsible for reviewing, testing, and debugging all AI outputs before incorporating them into your project.
*   **No Runtime Warranty:** We explicitly disclaim any liability for issues arising in your compiled game or application (e.g., crashes, performance drops, logic errors) resulting from the use of AI-generated content.
*   **Intellectual Property of Output:** You are responsible for ensuring that the AI-generated content does not infringe upon third-party rights. We make no warranties regarding the uniqueness or copyright status of AI outputs.

## 6. Warranty Disclaimer

**TO THE EXTENT PERMITTED BY LAW, THIS SERVICE IS PROVIDED "AS IS" AND "AS AVAILABLE" WITHOUT WARRANTIES OF ANY KIND, EITHER EXPRESS OR IMPLIED...**
We do not warrant that the Portal will meet your requirements or that defects will be corrected. Use is at your sole risk.

## 6.1 Force Majeure

Neither party is liable for any delay or failure to perform to the extent caused by events beyond its reasonable control ("Force Majeure").

## 7. Severability

If any provision of these terms is found unenforceable, the remaining provisions remain in full force and effect.

## 8. Entire Agreement

These Terms of Service, together with the Privacy Policy, constitute the entire agreement between you and us regarding the Portal service.

## 9. No Waiver

Our failure to enforce any right or provision of these terms shall not be deemed a waiver of such right or provision.

## 10. Assignment

You may not assign or transfer these terms without our prior written consent. We may assign these terms without restriction.

## 11. Governing Law & Jurisdiction

These terms are governed by the laws of the **Republic of Korea**, without prejudice to any mandatory consumer protection laws of your country of residence. Subject to mandatory laws, any disputes shall be subject to the exclusive jurisdiction of the courts of **Seoul, Republic of Korea**.

## 11.1 Dispute Resolution (US Residents)

If you are a resident of the United States, any dispute shall be resolved by **binding individual arbitration**. **Class actions and class arbitrations are not permitted.** You may opt out of this arbitration agreement within 30 days.

## 12. Language

In the event of any inconsistency or conflict between translations, the **English version** shall control to the extent permitted by law.

## 13. Changes to Terms

We may update these terms. Continued use after changes constitutes acceptance.

## 14. Contact

Email: **isekaitravel.pathfinder@gmail.com**
GitHub: **https://github.com/LSG7/UnrealEngine-AI-Bridge-Door-to-isekai**

## 15. Intellectual Property & Licenses

Unreal® is a trademark or registered trademark of Epic Games, Inc. This service is a third-party tool and is not affiliated with, endorsed by, or sponsored by Epic Games, Inc.
