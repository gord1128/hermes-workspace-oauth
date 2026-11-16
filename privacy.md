---
layout: default
title: Privacy Policy — Hermes Workspace OAuth
---
# Privacy Policy

## Operator and scope
Hermes Workspace OAuth is a personal automation operated by GitHub user [gord1128](https://github.com/gord1128). This policy covers its Google Workspace integration and related personal automation. This site is an informational site, not an OAuth token collection endpoint.

## Data accessed and use
Authorized tools can access Gmail message headers, snippets, bodies, labels and metadata; calendar events; Drive files; contacts; and Sheets and Docs content, as needed for owner-requested tasks and granted permissions. The scheduled Gmail organizer examines headers, snippets and labels to categorize mail and move nonessential mail out of the Inbox. Other Workspace permissions are used only for authorized tasks.

## Storage and processing
OAuth credentials are stored in the owner’s local Hermes configuration and sent to Google to authorize API requests. Local automation logs may retain message identifiers, categories, timestamps, counts and errors. Credentials and mailbox content are not published in this repository or on this website. Data processed through agent-assisted workflows may be sent to the configured AI service provider as required to fulfill the owner’s request; the rule-based scheduled Gmail classifier itself uses local rules rather than an AI classification API.

## Sharing
The mail automation sends summaries to the owner’s configured Discord destination. Summaries may contain category counts and limited samples of sender names and subject lines. Google processes API requests, Discord processes delivered summaries, and GitHub hosts these public informational pages. Google user data is not sold, used for advertising, or used by this integration to train generalized AI models. Disclosures are limited to requested functionality, authorized service providers, or legal obligations.

## Retention and control
Google source data remains in the owner’s account unless an authorized action changes it. Local credentials remain until removed or replaced; local logs and delivered Discord reports remain until removed under the owner’s management. There is no automatic fixed deletion period promised for logs or reports. Access can be revoked in [Google Account third-party connections](https://myaccount.google.com/connections); revocation does not itself remove existing logs or reports. The owner can delete local credentials, logs and Discord reports separately. Gmail folder moves are reversible and do not permanently delete messages.

## Google API compliance
Use and transfer of information received from Google APIs will adhere to the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including its Limited Use requirements.

## Contact and updates
Contact the operator through [GitHub issues](https://github.com/gord1128/hermes-workspace-oauth/issues) without posting sensitive information. Material changes will be reflected on this page and in the repository history.

[Back to app homepage](./)
