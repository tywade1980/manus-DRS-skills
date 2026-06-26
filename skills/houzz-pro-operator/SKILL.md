---
name: houzz-pro-operator
description: Provides Manus with the procedural knowledge to navigate, operate, and manage Wade Custom Carpentry's Houzz Pro account. Use for managing leads, creating estimates, building schedules, logging daily work, managing financial documents, or navigating Houzz Pro.
---

# Houzz Pro Operator Skill

This skill enables Manus to act as the primary operator for Wade Custom Carpentry's Houzz Pro account. It integrates Houzz Pro operations with Wade's existing tech stack, including `wade-custom-carpentry`, `wade-project-scheduler`, and `rsmeans-cost-estimator`.

## Core Principles

1.  **Real-time User Approval:** All changes, entries, estimates, and messages created for Houzz Pro must be approved by Wade in real-time before finalizing or sending.
2.  **Integration First:** 
    *   Before creating an estimate in Houzz Pro, use `rsmeans-cost-estimator` to determine accurate job costing.
    *   When building schedules in Houzz Pro, adhere to the principles outlined in `wade-project-scheduler`.
3.  **Client Expectations:** Always schedule client expectations from the upper-end labor-hour estimate unless an internal best-case target is explicitly requested.

## Workflows

The operational knowledge for Houzz Pro is organized into specific reference files based on the task domain. Load the appropriate reference file from the `references/` directory based on the user's request.

### 1. Platform Navigation
When asked to navigate to a specific section of Houzz Pro or locate a feature, refer to:
*   `references/platform_map.md`

### 2. Lead Management (CRM)
When asked to manage leads, respond to inquiries, or update pipeline stages, refer to:
*   `references/lead_workflow.md`

### 3. Project Management (Estimates, Schedules, Logs)
When asked to create an estimate, build a project schedule, log daily work, or manage tasks, refer to:
*   `references/project_workflow.md`

### 4. Financial Management
When asked to create an invoice, process a change order, or manage payments, refer to:
*   `references/financial_workflow.md`

### 5. Utilizing AutoMate AI
When asked to leverage AI features within Houzz Pro (e.g., generating estimates from text, cleaning up logs, drafting messages), refer to:
*   `references/automate_ai.md`

## Using Templates

When generating content to be pasted into Houzz Pro (such as a daily log entry or a lead response), utilize the standardized formats found in `templates/prompt_templates.md`.
