# IT Support Copilot Agent

## Overview
This project is an AI-powered IT Support Assistant built using Microsoft Copilot Studio.
The agent helps users troubleshoot common IT issues, provides step-by-step solutions, and automates ticket classification for faster support resolution.

---

## Features
- Interactive chatbot for IT support
- Troubleshooting flows for:
- Internet issues
- Slow computer performance
- Login problems
- Email issues
- Ticket classification system:
- Issue category (Network, Software, Access, Hardware)
- Priority level (Low, Medium, High)
- Suggested support team
- Escalation to human IT support when needed
- Knowledge base support using SOP documents

---

## How It Works
1. User starts a conversation with the Copilot Agent
2. User describes their IT issue
3. The agent provides step-by-step troubleshooting guidance
4. If the issue is not resolved, the agent escalates it
5. The system classifies the ticket automatically
6. Link https://m365.cloud.microsoft/chat/?titleId=T_1f4561a0-06e6-5f12-b3bc-4228394e097c&source=embedded-builder

---

## Troubleshooting Flows

### 1. Internet Issues
- Checks Wi-Fi or network connection
- Tests internet access
- Suggests router restart
- Escalates if unresolved

### 2. Slow Computer
- Checks running applications
- Suggests closing unnecessary programs
- Recommends restarting the device
- Escalates if unresolved

### 3. Login Problems
- Verifies username and password
- Suggests password reset
- Checks account status
- Escalates if unresolved

### 4. Email Issues
- Identifies email service
- Checks internet connection
- Troubleshoots send/receive errors
- Escalates if unresolved

---

## Ticket Classification
The agent automatically classifies support requests:
- Issue category
- Priority level
- Recommended support team
- Summary of the issue

---

## Architecture (Simple Flow)
User → Copilot Agent → Troubleshooting Flow →
Resolved OR Escalation → Ticket Classification → IT Support Team

---

## Testing
The agent was tested using multiple real-world scenarios:
- Internet connectivity issues
- Slow device performance
- Login failures
- Email sending/receiving problems

All scenarios successfully triggered correct troubleshooting paths and escalation when needed.

---

## Screenshots
(Add your screenshots here)

---

## Knowledge Base
The agent uses SOP documents including:
- Password reset guide
- VPN setup guide
- Printer setup guide
- Outlook configuration guide
- Device compliance procedures


---

## Conclusion
This project demonstrates how AI can automate Tier-1 IT support by guiding users through troubleshooting, resolving common issues, and reducing workload for IT teams.
