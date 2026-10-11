# Retell AI — Loan Against Property Voice Agent

An AI-powered voice agent built using **Retell AI** for a Loan Against Property (LAP) customer qualification workflow. This project focuses on conversational prompt engineering, structured eligibility screening, handling customer responses, and evaluating voice-agent call records.

## Project Overview

The voice agent is designed to contact existing customers about a pre-approved Loan Against Property offer, gather relevant eligibility information, and determine whether a customer meets the defined qualification criteria.

The project demonstrates how prompt engineering can guide an AI voice agent through a structured conversation while handling interruptions, clarifications, and different customer responses.

## Objectives

- Design a structured prompt for an AI voice agent.
- Guide customers through a sequential eligibility questionnaire.
- Handle interruptions, incomplete answers, and out-of-order responses.
- Apply the defined eligibility and disqualification rules consistently.
- Handle requests for loan amounts above the specified limit.
- Identify qualified leads for handoff to a senior loan expert.
- Review call transcripts and call outcomes to identify opportunities for improvement.

## Technology Stack

- **Retell AI** — Voice agent platform
- **Prompt Engineering** — Conversation instructions, qualification logic, and response handling
- **Call Transcripts and Logs** — Testing, review, and debugging
- **GitHub** — Version control and project documentation
- **Google Drive** — Supporting call records and submission documentation

## Key Features

### 1. Customer Interaction
Initiates a conversation about a Loan Against Property offer and checks whether the intended customer is available to continue.

### 2. Structured Eligibility Screening
Collects the required information through a guided conversational flow:

1. Property type
2. Property ownership
3. Availability of original property documents
4. Desired loan amount
5. Occupation
6. Income mode
7. Property market value and desired loan tenure, as captured in the qualification flow

### 3. Eligibility Rule Handling
The agent follows the specified assignment criteria:

| Criterion | Defined rule |
|---|---|
| Property type | Residential, commercial, and industrial properties are eligible; agricultural property is disqualified |
| Ownership | Sole or joint ownership is eligible |
| Original documents | Original documents must be available |
| Loan amount | Up to ₹75 lakh; a ₹75 lakh alternative is offered when a higher amount is requested |
| Occupation | Salaried or self-employed |
| Income mode | Bank-based income is eligible; cash-based income is disqualified |
| Property market value | Recorded during qualification; no minimum threshold is specified in the assignment |
| Loan tenure | 3–15 years, inclusive |

### 4. Conversation Management
The prompt is designed to handle interruptions, clarification requests, diversions, and answers provided out of sequence while maintaining the qualification flow.

### 5. Lead Qualification and Handoff
A qualified lead is handed off to a senior loan expert only after the required eligibility information has been collected and all mandatory criteria have been satisfied.

### 6. Call Record Evaluation
Call-history exports, transcripts, recording links, and available summaries support the review of agent behavior and identification of prompt improvements.

## Project Resources

- **Retell AI Agent:** Add your intended public agent-sharing link here.
- **Call Records and Documentation:** [Open the Google Drive folder](https://drive.google.com/drive/folders/1Ub2xG9cHKOBmOYf6N5VmHNO27ERQI20d?usp=sharing)

## Repository Structure

```text
retell-ai-lap-voice-agent/
├── README.md
├── docs/
│   └── call-records-and-testing.md
└── test-cases/
    └── eligibility-and-conversation-tests.md
```

*The structure above is a suggested organization. Add the folders and files only when you create them.*

## Testing and Evaluation

Call records can be reviewed against the following checks:

- Did the agent follow the intended conversation flow?
- Did it collect the required eligibility information?
- Did it apply the defined rules correctly?
- Did it handle interruptions and incomplete responses appropriately?
- Did it avoid premature lead handoff?
- Did the recorded call outcome match the conversation?

A call marked successful does not automatically mean the agent handled the conversation correctly. Transcripts and available recordings should also be reviewed.

## Learning Outcomes

- Practical experience designing prompts for conversational AI.
- Understanding structured voice-agent workflows.
- Translating business requirements into explicit qualification rules.
- Designing conversation handling for real-world customer responses.
- Reviewing call logs to identify and improve agent behavior.
- Documenting an AI project for technical review and evaluation.

## Scope and Disclaimer

This project documents a voice-agent workflow created for an assignment. Eligibility rules reflect the supplied assignment requirements and should not be interpreted as a complete lending policy, an approval decision, or a guarantee of loan availability.

Customer information and call recordings should be shared only when authorized. Sensitive information and credentials must not be committed to a public repository.

## Author

**AI Prompt Engineering Project**

Focus areas: Conversational AI, Voice Agents, Prompt Engineering, and AI Workflow Design.
