# IT-Support-Copilot-Agent




## Overview

This project is an AI-powered IT Support Assistant built using Microsoft Copilot Studio.  

The agent helps users troubleshoot common IT issues, provides step-by-step solutions, and automates ticket classification.



---



## Features

- Interactive chatbot for IT support

- Troubleshooting flows for:

  - Internet issues

  - Slow computer

  - Login problems

  - Email issues

- Ticket classification:

  - Category (Network, Software, Access, etc.)

  - Priority (Low, Medium, High)

  - Suggested team assignment

- Escalation to human support when needed



---



## How to Use

1. Start the agent

2. Type your issue (e.g. "my internet is not working")

3. Follow the guided troubleshooting steps

4. If the issue is not resolved, the agent will escalate



---



## Troubleshooting Flows



### 1. Internet Issue

- Checks Wi-Fi connection

- Tests website access

- Suggests router restart

- Escalates if unresolved



### 2. Slow Computer

- Checks running programs

- Suggests closing apps

- Suggests restart

- Escalates if unresolved



### 3. Login Issue

- Verifies credentials

- Suggests password reset

- Checks account status

- Escalates if unresolved



### 4. Email Issue

- Identifies email type

- Checks connection

- Checks send/receive issues

- Escalates if unresolved



---



## Ticket Classification

The agent analyzes user input and outputs:

- Issue category

- Priority level

- Recommended support team

- Summary of the issue



---



## Architecture (Simple)

User → Copilot Agent → Troubleshooting Flow →  

→ Resolved OR → Escalation + Ticket Classification



---



## Testing

The agent was tested using different scenarios:

- Internet not working

- Slow performance

- Login failure

- Email issues



All flows successfully guided the user and escalated when needed.



---



## Screenshots

(Add your screenshots here)



---



## Knowledge Base

SOP documents include:

- Password reset

- VPN setup

- Printer setup

- Outlook setup

- Device compliance



---



## Conclusion

This project demonstrates how AI can automate Tier-1 IT support by guiding users, solving common issues, and reducing workload for IT teams.
