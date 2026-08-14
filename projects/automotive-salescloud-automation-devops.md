---
title: Project: Sales Cloud Automation & DevOps
layout: page
---

<div class="project-page">

<h1>Project: Sales Cloud Automation & DevOps</h1>

<p class="project-role">Role: Salesforce Lead Developer</p>

Worked as a Salesforce Consultant/Developer for an automotive services company, delivering Salesforce Sales Cloud enhancements, Monday.com-Salesforce bidirectional integration, custom lead conversion automation, data quality controls, opportunity/account lifecycle automation, calendar/event automation, configurable metadata frameworks, production hotfixes, and Salesforce DX/GitHub DevOps setup for an existing customized production org.

## Key Contributions

- Designed and implemented a custom Lead Conversion framework for multi-location business scenarios, dynamically creating parent/child Accounts, Opportunities, Contacts, and Opportunity Contact Roles.
- Built metadata-driven validation and mapping frameworks using Salesforce Custom Metadata Types to reduce hardcoded Apex dependencies.
- Refactored Lead and Location automation to prevent duplicate Location creation, enforce required data before conversion, and support shop-count changes.
- Developed Account and Opportunity lifecycle automation, including two-way field sync and Opportunity Stage to Account Status automation.
- Delivered production hotfixes for validation rules, security/sharing, calendar events, status automation, and lead conversion edge cases.
- Established Salesforce DX and GitHub-based DevOps practices for an existing production Salesforce org, including production metadata baselining, sandbox development, feature branches, hotfix branches, pull requests, and manifest-based deployments.

## Selected Technical Work

### Monday.com-Salesforce Bidirectional Integration

Designed and documented a Monday.com-Salesforce synchronization approach for location and LOI lifecycle data. The approach covered initial one-time data alignment, ongoing two-way sync rules, field mapping strategy, Salesforce Account identifiers on Monday boards, Monday item identifiers in Salesforce, and controlled duplicate resolution during migration.

Key elements included:

- Defined bidirectional field mappings between Monday boards and Salesforce Account records.
- Designed one-way identifier sync patterns, including Monday item IDs into Salesforce and Salesforce Account IDs back to Monday.
- Planned first-time sync for existing location records, including criteria-based sync triggers and duplicate Account merge strategy.
- Designed post-migration safeguards using unique Location Number enforcement to prevent future duplicate Account creation.
- Defined ongoing sync criteria based on Account lifecycle/status values for LOI and acquired-location workflows.
- Prepared a controlled merge-script approach with dry-run mode, single-record filtering, max-merge limits, debug summaries, and CSV audit output for migration validation.

### Custom Lead Conversion Automation

Built a custom conversion process to support leads with one or many locations. The solution created the correct Account and Opportunity structure based on the number of shops, validated required Location data before conversion, and preserved conversion traceability in background records.

### Account and Opportunity Lifecycle Automation

Implemented automation to synchronize selected Account and Opportunity fields, derive Account Status from Opportunity Stage, and restrict manual changes where business rules required system-managed values.

### Metadata-Driven Validation and Mapping

Designed configurable metadata patterns for required-field validation and field mapping across Lead, Location, Account, Contact, and Opportunity objects. This allowed admins and developers to extend mappings and validation rules without deeply changing Apex logic.

### DevOps and Project Governance

Created a GitHub-backed Salesforce DX baseline for an existing production org, supported feature/hotfix branching, PR-based review, sandbox validation, and deployment planning. Also documented repeatable workflows for future AI-assisted Salesforce development.

## Technology Stack

Salesforce Sales Cloud, Apex, Apex Triggers, Screen Flows, Custom Metadata Types, Custom Labels, Validation Rules, Lightning Record Pages, Page Layouts, Permission Sets, Salesforce DX, Salesforce CLI, Git, GitHub, GitHub Actions, Monday.com Integration.

## Confidentiality Note

This project summary is intentionally sanitized. It does not include client source code, org-specific metadata, record data, screenshots, credentials, or confidential business logic.

</div>
