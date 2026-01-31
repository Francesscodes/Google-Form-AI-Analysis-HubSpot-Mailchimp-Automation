This project documents a Zapier automation workflow that captures Google Form responses, analyzes the data using AI, filters qualified leads, and automatically syncs them to HubSpot CRM and Mailchimp.

The automation reduces manual data handling, improves lead qualification, and ensures marketing and CRM tools stay in sync.

Use Case - Automatically process form submissions, Use AI to analyze or enrich responses, Filter responses based on predefined conditions, Create CRM contacts only when criteria are met, Add/update email subscribers for marketing campaigns

Tools & Technologies - Zapier, Google Forms, AI by Zapier, HubSpot CRM, Mailchimp

Workflow Breakdown

* Trigger: Google Forms - Event: New or Updated Form Response, Captures user submissions in real time

* AI Processing: AI by Zapier - Analyzes form responses, Can be used for: Lead qualification, Intent detection, Data cleanup or summarization

* Filtering: Filter by Zapier- Applies logic-based condition(@email address required), Ensures only qualified or relevant responses continue in the workflow

* CRM Sync: HubSpot - Action: Create Contact, Automatically creates a new contact in HubSpot with the processed data

*  Email Marketing: Mailchimp - Action: Add or Update Subscriber, Syncs contacts into Mailchimp for newsletters and campaigns

  Benefits - Eliminates manual data entry, Improves lead quality using AI, Ensures CRM and email lists are always updated, Scales easily for growing teams or campaigns

  Example Use Cases - Newsletter signups, Event registrations, Lead generation forms, Customer onboarding, Application screening

Repository Structure
  /
├── README.md
├── zap-workflow.png  

Notes - No API keys or credentials are stored in this repository and This project focuses on workflow design and automation logic

Future Improvements : Add Slack notifications for qualified leads, Log submissions to Google Sheets or Airtable, Add error handling and fallback paths, Introduce multi-path Zaps for different lead types


 Author
Francess Ekezie
