# Claims Agent \(Copilot Studio\)

## Overview

This repository contains the sample files used to demonstrate how to build a multi\-agent Claims solution in Microsoft Copilot Studio as demonstrated in the Agent Maker course which you can register for here: https://aka.ms/FounderzRegister 

The scenario demonstrates how an orchestration agent can coordinate specialist agents to assess insurance claims, recommend next actions, and automate triage activities using plain\-English instructions rather than code.

This repository is intended for learners, makers, architects, and IT professionals who want to recreate the scenario in their own environment.

---

## Business Scenario

Insurance claims teams receive a constant stream of claims that must be assessed before work can begin.

The process is often manual and requires staff to:

- Review claim details
- Determine claim priority
- Identify potential fraud indicators
- Decide next actions
- Route work to the appropriate teams

This demonstration shows how Microsoft Copilot Studio can automate those activities using multiple collaborating agents.

---

## Solution Architecture

### Claims Agent \(Orchestrator\)

The primary agent receives the claim and coordinates work across specialist agents.

### Claims Triage Assistant

Responsible for:

- Reading the claims playbook
- Assessing claim priority
- Detecting fraud indicators
- Recommending next actions
- Updating claim records

### Preferred Supplier Agent

Responsible for:

- Identifying the most appropriate supplier for the claim
- Recommending suppliers based on business rules
- Returning supplier recommendations to the Claims Agent

The Claims Agent combines the output of both specialist agents into a single recommendation.

---

## Repository Contents

| File | Purpose |
| --- | --- |
| Claims\-Triage\-Agent\-Instructions.docx | Initial instructions used when creating the Claims Triage Assistant |
| Claims\-Triage\-Playbook.docx | Knowledge source used by the Claims Triage Assistant |
| Claims\-List.csv | Sample claims data used during the demonstration |
| Claims\-Triage\-Agent\-Instructions\-Updated.docx | Updated instructions used for the Claims Triage Assistant once Tools and Triggers have been added |
| Preferred\-Supplier\-Agent\-Instructions.docx | Instructions used when creating the Preferred Supplier Agent |
| Preferred\-Supplier\-Agent\-Supplier\-List.docx | Knowledge source used by Preferred Supplier Ageent |

---

## What You'll Build

By using these files you will learn how to:

1. Create a Copilot Studio agent
2. Add knowledge sources
3. Configure tools
4. Configure triggers
5. Build specialist agents
6. Build an orchestration agent
7. Test an end\-to\-end business scenario

---

## Prerequisites

- Microsoft 365 work account
- Access to Microsoft Copilot Studio
- Access to SharePoint
- Permission to create SharePoint Lists

---

## Expected Outcome

At the completion of this exercise you will have a working Claims Agent solution capable of:

- Answering claims handling questions
- Automatically triaging incoming claims
- Recommending next actions
- Identifying potential fraud indicators
- Coordinating specialist agents to deliver a unified recommendation

<img width="1334" height="267" alt="image" src="https://github.com/user-attachments/assets/874ef4f6-04f1-4d77-ac03-a96042d2fc3f" />

---

## Disclaimer

This repository is provided for demonstration and learning purposes only. Sample data, business rules, thresholds, suppliers, and claims information should be replaced with production\-ready content before any real\-world implementation.

