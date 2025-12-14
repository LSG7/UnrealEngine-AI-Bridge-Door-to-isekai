# Door to Isekai Service License

**Copyright (c) 2025 Isekai Travel. All rights reserved.**

**Version 1.9** | Last Updated: 2025-12-07

---

## Service Overview

Door to Isekai is an integrated platform that enables collaborative game development between LLMs and developers using Unreal Engine. The service consists of the following components:

| Component | Description | Location |
|-----------|-------------|----------|
| **Plugin** | UnrealEngine_AI_Bridge - MCP server with 672 tools | GitHub Releases Page |
| **Backend Server** | AWS-hosted activation and relay service | door-to-isekai.world |
| **Mobile App** | Flutter app for ad-based activation | Google Play Store / Apple App Store |

By using any component of this service, you agree to the terms outlined below and the full Terms of Service and Privacy Policy available at:
- **Terms of Service**: http://127.0.0.1:{port}/terms (local web server)
- **Privacy Policy**: http://127.0.0.1:{port}/privacy (local web server)

Note: Terms and Privacy Policy are served from the plugin's local web server (127.0.0.1) for security and offline accessibility.

---

## Grant of License

Isekai Travel grants you a non-exclusive, worldwide, royalty-free license to use the Door to Isekai service components in accordance with the following terms.

---

## Permitted Uses

**You MAY:**

### General Use
- Use the service as a development tool for creating games, applications, and content with AI assistance
- Sell games, applications, and content created using the service as a development tool
- Use the service within your organization, team, or company
- Use the service for learning, teaching, or research purposes

### Plugin (UnrealEngine_AI_Bridge)
- Use the plugin as a development tool in Unreal Engine projects
- Modify configuration files, settings, and plugin parameters
- Integrate the plugin into development processes and AI-assisted workflows
- Connect the plugin to third-party AI services via Model Context Protocol

### Mobile App
- Use the app to activate MCP tools through ad viewing
- Install the app on personal or company-owned devices

### Backend Service
- Connect to the backend service for activation and relay functionality
- Use SSE and WebSocket connections as documented

---

## Restrictions

**You MAY NOT:**

### General Restrictions
- Sell any component of this service as a standalone commercial product
- Reverse engineer, decompile, or disassemble any component
- Use the service to create competing AI integration tools for Unreal Engine
- Offer the service as a hosted service or API without explicit permission
- Circumvent the ad-based activation system
- Use automated tools to bypass security measures or rate limits

### Plugin Restrictions
- Distribute the plugin binaries as part of your final products, games, or applications
- Include the plugin in products where end-users can access or use the plugin directly
- Repackage or rebrand the plugin as your own
- Extract individual components for separate distribution

### Backend/API Restrictions
- Access the backend API in ways not documented or intended
- Attempt to overwhelm the service with excessive requests (DDoS)
- Exploit vulnerabilities in the service

---

## Component-Specific Terms

### Plugin (UnrealEngine_AI_Bridge)

The plugin is a **development-time tool only**. It should NOT be included in shipped games or applications.

**Allowed:**
- Using during development with third-party AI services to build game features
- Using the MCP server for AI-assisted Blueprints and C++ code generation
- Creating commercial games or applications with AI assistance, then shipping without the plugin

**Not Allowed:**
- Shipping a game or application that contains UnrealEngine_AI_Bridge plugin files
- Including the MCP server binaries in packaged products
- Distributing apps where end-users can access AI Bridge functionality

### Mobile App (MCP Activation App)

The mobile app is provided for use by individual developers or within organizations to activate MCP tools.

**Allowed:**
- Installing on personal or company-owned devices
- Viewing ads to activate MCP tools
- Using test mode for development purposes (as documented)

**Not Allowed:**
- Modifying the app to bypass ad viewing
- Redistributing modified versions of the app
- Using automated tools to simulate ad views

### Backend Service

The backend service is operated by Isekai Travel and accessed via door-to-isekai.world.

**Service Level:**
- No SLA guaranteed for free tier
- Service may be modified or discontinued with notice
- Rate limiting applies (see Terms of Service)

---

## Attribution (Optional)

Since Door to Isekai is used only during development and not included in final products, attribution is optional but appreciated:

```
Developed with Door to Isekai by Isekai Travel
```

---

## Privacy and Data

### Data Processing
- **Plugin**: Processes data locally on your development machine
- **Backend**: Processes session and activation data (see Privacy Policy)
- **Mobile App**: Collects data for activation and advertising purposes (see Privacy Policy)

### Data Transmission
- Data is transmitted to External Services (AI providers) ONLY when you explicitly opt in
- Local-first approach: MCP tool responses are saved locally by default
- See Privacy Policy for full details

### Third-Party Services
When using third-party AI services or External Services, you are bound by their respective terms of service and privacy policies. You are responsible for reviewing and complying with the terms of any service you connect to via the plugin.

---

## Security

### What We Provide
- TLS 1.3 encryption for all data in transit
- HSTS (Strict-Transport-Security) enforcement
- Certificate pinning for backend connections
- Localhost-only web interface binding
- 12-digit time-limited activation codes

### What We Cannot Protect
- Compromised user devices (malware, hacking)
- Untrusted network environments
- User's failure to maintain device security

See Terms of Service Section 2-3 for full security disclosure and liability limitations.

---

## Warranty Disclaimer

THE SERVICE IS PROVIDED "AS IS" WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.

THE SERVICE IS PROVIDED FOR DEVELOPMENT USE ONLY. WE DO NOT WARRANT THAT THE SERVICE WILL MEET YOUR REQUIREMENTS OR THAT DEFECTS WILL BE CORRECTED.

---

## Limitation of Liability

TO THE EXTENT PERMITTED BY LAW, ISEKAI TRAVEL SHALL NOT BE LIABLE FOR:
- Data breaches caused by compromised user devices
- Security incidents from user's failure to maintain device security
- Damages from third-party attacks on user's systems
- AI-generated code or content issues
- Service interruptions or discontinuation

**LIABILITY CAP**: Total aggregate liability shall not exceed USD $20 or the amounts paid by you for the service during the preceding 12 months, whichever is greater.

**EXCEPTIONS** (We Remain Liable For):
- Intentional misconduct or gross negligence
- Violations of mandatory consumer protection laws
- Personal injury or death caused by product defects
- Breaches of applicable data protection regulations within our control

---

## Age Requirements

This service is intended for software developers. Minimum age requirements vary by region:
- **United States**: 13 years (COPPA)
- **European Union**: 13-16 years (varies by country, see Terms of Service)
- **South Korea**: 14 years
- **India**: 18 years (DPDP Act)
- **China**: Service not available

See Terms of Service Section 4.1 for complete regional requirements.

---

## Governing Law

These terms are governed by the laws of the **Republic of Korea**, without prejudice to mandatory consumer protection laws of your country of residence.

Disputes shall be subject to the exclusive jurisdiction of the courts of **Seoul, Republic of Korea**, except where local consumer protection laws require otherwise.

For US residents: Binding individual arbitration applies (see Terms of Service Section 11.1).

---

## Termination

This license terminates automatically if you violate any terms. Upon termination:
- Stop using all service components
- Delete all copies of the plugin
- Uninstall the mobile app

---

## Changes to License

We may update this license. Material changes will be notified through the service interface. Continued use constitutes acceptance.

---

## Contact

For licensing questions, commercial use permissions, or support:
- **Email**: pathfinder@door-to-isekai.world
- **GitHub**: https://github.com/LSG7/UnrealEngine-AI-Bridge-Door-to-isekai
- **Response Time**: Within 30 days

---

## Full Legal Documents

This license is a summary. For complete legal terms, please refer to:
- **Terms of Service**: http://127.0.0.1:{port}/terms (local web server)
- **Privacy Policy**: http://127.0.0.1:{port}/privacy (local web server)

In case of conflict between this license and the Terms of Service, the Terms of Service shall prevail.

---

**License Version**: 1.9
**Effective Date**: 2025-12-07
**Previous Versions**:
- 2.0 (2025-01-13) - Plugin-only license (shared-files/LICENSE)
- 1.0 (2025-01-01) - Initial version

Note: Version number aligned with Terms of Service (terms.html v1.9) for consistency.

---

## Third-Party Notices

### Model Context Protocol (MCP)
- **Specification**: Open protocol by Anthropic for AI tool integration
- **Documentation**: https://modelcontextprotocol.io/
- **License**: Open specification (implementation is original work)

### Unreal Engine
- **Owner**: Epic Games, Inc.
- **License**: Unreal Engine EULA
- **Note**: This plugin requires a valid Unreal Engine license

---

## License Summary

| Component | Use Allowed | Distribution Allowed | Runtime Inclusion |
|-----------|-------------|---------------------|-------------------|
| Plugin | Development only | No | No |
| Mobile App | Internal use | No | N/A |
| Backend | Via API | N/A | N/A |

**For Game Developers:**
- Use freely during development with AI assistance
- Ship commercial products without the plugin
- Don't include plugin binaries in final products
- Don't sell the plugin itself

**For AI Service Providers:**
- Connect to MCP server for development assistance
- Users may access via localhost endpoint
- Don't redistribute the plugin
- Don't offer hosted versions without permission

**For Educators:**
- Encouraged for use in teaching and learning
- Share with students for educational purposes
- Direct students to official download channels instead of redistributing files

