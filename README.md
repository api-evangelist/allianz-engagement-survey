# Allianz Engagement Survey (allianz-engagement-survey)
The Allianz Engagement Survey API enables management of employee engagement surveys across the Allianz organization. It provides capabilities for survey lifecycle management, participant management, response collection, and analytics reporting to support Allianz's global employee experience initiatives.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/allianz-engagement-survey/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Analytics, Enterprise, Human Resources, Insurance, Surveys, Employee Experience

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-04-19

## APIs

### Allianz Engagement Survey API
REST API for managing the full lifecycle of employee engagement surveys at Allianz. Supports survey creation and configuration, participant management, response collection, results analysis, and reporting across business units and geographies.

**Human URL:** [https://www.allianz.com/en/careers/working-at-allianz.html](https://www.allianz.com/en/careers/working-at-allianz.html)

#### Tags:

 - Surveys, Human Resources, Employee Experience, Analytics

#### Properties

- [Documentation](https://www.allianz.com/en/careers/working-at-allianz.html)
- [OpenAPI](openapi/allianz-engagement-survey.yaml)
- [JSONSchema](json-schema/engagement-survey-survey-schema.json)
- [JSONSchema](json-schema/engagement-survey-response-schema.json)
- [JSONSchema](json-schema/engagement-survey-analytics-schema.json)
- [JSONStructure](json-structure/engagement-survey-survey-structure.json)
- [JSONStructure](json-structure/engagement-survey-response-structure.json)
- [JSONLD](json-ld/allianz-engagement-survey-context.jsonld)
- [Example](examples/engagement-survey-survey-example.json)
- [Example](examples/engagement-survey-analytics-example.json)

## Common Properties

- [Website](https://www.allianz.com/)
- [GitHubOrganization](https://github.com/allianz)
- [SpectralRules](rules/allianz-engagement-survey-spectral-rules.yml)
- [Vocabulary](vocabulary/allianz-engagement-survey-vocabulary.yaml)
- [NaftikoCapability](capabilities/employee-engagement-workflow.yaml)

## Features

| Name | Description |
|------|-------------|
| Survey Lifecycle Management | Create, configure, publish, and close employee engagement surveys with full lifecycle tracking and audit capabilities. |
| Participant Management | Manage survey participants, send invitations, track response rates, and send reminders to boost participation across business units. |
| Response Collection | Collect structured survey responses with support for multiple question types including Likert scales, open text, and multiple choice. |
| Analytics and Reporting | Generate engagement analytics, participation metrics, and comparative reports across departments, regions, and time periods. |
| Segmentation | Segment survey results by business unit, geography, role, tenure, and demographic dimensions for targeted insights. |
| Action Planning | Track and manage action plans created in response to survey insights to drive employee experience improvements. |

## Use Cases

| Name | Description |
|------|-------------|
| Annual Engagement Survey | Run company-wide annual employee engagement surveys to measure satisfaction, commitment, and advocacy across all Allianz entities. |
| Pulse Surveys | Deploy frequent short pulse surveys to track engagement trends and respond quickly to changing employee sentiment. |
| Onboarding Surveys | Capture new employee experience feedback during onboarding to improve the joining experience and early retention. |
| Exit Surveys | Collect departing employee feedback to understand attrition drivers and improve retention strategies. |

## Integrations

| Name | Description |
|------|-------------|
| Workday | Integration with Workday HCM for automated participant roster management and organizational hierarchy synchronization. |
| Microsoft Teams | Survey notifications and reminders delivered through Microsoft Teams to increase employee participation rates. |
| Power BI | Export engagement analytics to Power BI for advanced visualization and executive dashboard reporting. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Allianz Engagement Survey API](openapi/allianz-engagement-survey.yaml)

### JSON Schema

- [engagement-survey-survey-schema.json](json-schema/engagement-survey-survey-schema.json)
- [engagement-survey-survey-list-schema.json](json-schema/engagement-survey-survey-list-schema.json)
- [engagement-survey-create-survey-request-schema.json](json-schema/engagement-survey-create-survey-request-schema.json)
- [engagement-survey-participant-schema.json](json-schema/engagement-survey-participant-schema.json)
- [engagement-survey-participant-list-schema.json](json-schema/engagement-survey-participant-list-schema.json)
- [engagement-survey-add-participants-request-schema.json](json-schema/engagement-survey-add-participants-request-schema.json)
- [engagement-survey-add-participants-response-schema.json](json-schema/engagement-survey-add-participants-response-schema.json)
- [engagement-survey-survey-response-schema.json](json-schema/engagement-survey-survey-response-schema.json)
- [engagement-survey-answer-schema.json](json-schema/engagement-survey-answer-schema.json)
- [engagement-survey-response-list-schema.json](json-schema/engagement-survey-response-list-schema.json)
- [engagement-survey-survey-analytics-schema.json](json-schema/engagement-survey-survey-analytics-schema.json)
- [engagement-survey-question-score-schema.json](json-schema/engagement-survey-question-score-schema.json)
- [engagement-survey-action-plan-schema.json](json-schema/engagement-survey-action-plan-schema.json)
- [engagement-survey-action-plan-list-schema.json](json-schema/engagement-survey-action-plan-list-schema.json)
- [engagement-survey-create-action-plan-request-schema.json](json-schema/engagement-survey-create-action-plan-request-schema.json)

### JSON Structure

- [engagement-survey-survey-structure.json](json-structure/engagement-survey-survey-structure.json)
- [engagement-survey-survey-analytics-structure.json](json-structure/engagement-survey-survey-analytics-structure.json)
- [engagement-survey-action-plan-structure.json](json-structure/engagement-survey-action-plan-structure.json)

### JSON-LD

- [allianz-engagement-survey-context.jsonld](json-ld/allianz-engagement-survey-context.jsonld)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Allianz Engagement Survey API](capabilities/shared/engagement-survey.yaml) — 8 operations for employee engagement survey management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Allianz Employee Engagement Workflow](capabilities/employee-engagement-workflow.yaml) | Allianz Engagement Survey API | 8 | HR Business Partner, People Analytics Analyst, Team Manager |

## Vocabulary

- [Allianz Engagement Survey Vocabulary](vocabulary/allianz-engagement-survey-vocabulary.yaml) — Unified taxonomy mapping 5 resources, 4 actions, 1 workflow, and 3 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Allianz Engagement Survey Spectral Rules](rules/allianz-engagement-survey-spectral-rules.yml) — 21 rules across 8 categories enforcing Allianz Engagement Survey API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
