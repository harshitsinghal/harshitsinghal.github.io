# Hersh Singhal

Salesforce Consultant / Developer specializing in Salesforce Sales Cloud automation, Apex, Flow, integrations, metadata-driven frameworks, and Salesforce DevOps.

## Featured Project

### Salesforce Sales Cloud Automation & DevOps Case Study

Worked as a Salesforce Consultant/Developer for an automotive services company, delivering Salesforce Sales Cloud enhancements, Monday.com-Salesforce bidirectional integration, custom lead conversion automation, data quality controls, opportunity/account lifecycle automation, calendar/event automation, configurable metadata frameworks, production hotfixes, and Salesforce DX/GitHub DevOps setup for an existing customized production org.

## Key Contributions

- Designed and implemented a custom Lead Conversion framework for multi-location business scenarios, dynamically creating parent/child Accounts, Opportunities, Contacts, and Opportunity Contact Roles.
- Built metadata-driven validation and mapping frameworks using Salesforce Custom Metadata Types to reduce hardcoded Apex dependencies.
- Refactored Lead and Location automation to prevent duplicate Location creation, enforce required data before conversion, and support shop-count changes.
- Developed Account and Opportunity lifecycle automation, including two-way field sync and Opportunity Stage to Account Status automation.
- Delivered production hotfixes for validation rules, security/sharing, calendar events, status automation, and lead conversion edge cases.
- Established Salesforce DX and GitHub-based DevOps practices for an existing production Salesforce org, including production metadata baselining, sandbox development, feature branches, hotfix branches, pull requests, and manifest-based deployments.

## Selected Technical Work

### Custom Lead Conversion Automation

Built a custom conversion process to support leads with one or many locations. The solution created the correct Account and Opportunity structure based on the number of shops, validated required Location data before conversion, and preserved conversion traceability in background records.

### Metadata-Driven Validation and Mapping

Designed configurable metadata patterns for required-field validation and field mapping across Lead, Location, Account, Contact, and Opportunity objects. This allowed admins and developers to extend mappings and validation rules without deeply changing Apex logic.

### Account and Opportunity Lifecycle Automation

Implemented automation to synchronize selected Account and Opportunity fields, derive Account Status from Opportunity Stage, and restrict manual changes where business rules required system-managed values.

### Production Hotfix Delivery

Delivered time-sensitive production changes using isolated hotfix branches and controlled metadata deployments. Examples included Lead Gate 1 validations, Opportunity date validations, broker-user visibility restrictions, Account Status automation, and calendar/event sync fixes.

### DevOps and Project Governance

Created a GitHub-backed Salesforce DX baseline for an existing production org, supported feature/hotfix branching, PR-based review, sandbox validation, and deployment planning. Also documented repeatable workflows for future AI-assisted Salesforce development.

## Technology Stack

Salesforce Sales Cloud, Apex, Apex Triggers, Screen Flows, Custom Metadata Types, Custom Labels, Validation Rules, Lightning Record Pages, Page Layouts, Permission Sets, Salesforce DX, Salesforce CLI, Git, GitHub, GitHub Actions, Monday.com Integration.

## Confidentiality Note

This case study is intentionally sanitized. It does not include client source code, org-specific metadata, record data, screenshots, credentials, or confidential business logic.
