# GCP MCP: Algolia Ask AI / Gemini Project Guide

Use these prompts with the `gcloud` MCP server to monitor and debug the
`algolia-gemini` GCP project powering the Algolia Ask AI integration.

---

## API Health & Status

- What APIs are enabled on my algolia-gemini project?
- Is the Generative Language API enabled and healthy in algolia-gemini?
- Show me the status of the aiplatform and generativelanguage APIs in algolia-gemini.

---

## Logging & Error Debugging

- Look for errors in Cloud Logging for generativelanguage.googleapis.com in algolia-gemini in the last 24 hours.
- Show me any 429 or RESOURCE_EXHAUSTED errors in algolia-gemini in the last 7 days.
- Are there any permission denied errors for the algolia-ask-ai-gemini service account in the last 7 days?
- Show me recent API errors across all services in algolia-gemini.
- Check for any errors related to the algolia-ask-ai-gemini service account in Cloud Logging.

---

## Service Account & IAM

- List all service accounts in algolia-gemini and their roles.
- What roles does algolia-ask-ai-gemini@algolia-gemini.iam.gserviceaccount.com have?
- Does the algolia-ask-ai-gemini service account have permission to call the Generative Language API?
- Show me recent activity for the algolia-ask-ai-gemini service account.
- Are there any IAM policy changes in algolia-gemini in the last 30 days?

---

## API Keys

- List all API keys in the algolia-gemini project.
- Are there any API keys restricted to the Generative Language API in algolia-gemini?
- Show me the restrictions and allowed referrers for API keys in algolia-gemini.

---

## Quota & Usage

- Check if data access audit logging is enabled for generativelanguage.googleapis.com in algolia-gemini.
- Show me API usage metrics for generativelanguage.googleapis.com in the last 7 days.
- Are there any quota limit alerts configured in algolia-gemini?

---

## Monitoring & Alerts

- List all alert policies in algolia-gemini.
- Are there any Cloud Monitoring alerts configured for the Generative Language API?
- Show me uptime check results for algolia-gemini.
- List recent Cloud Monitoring incidents in algolia-gemini.

---

## Billing & Cost

- What is the current billing status for algolia-gemini?
- Show me the most expensive services by usage in algolia-gemini this month.

---

## General Diagnostics

- Give me a health summary of the algolia-gemini project.
- What has changed in algolia-gemini in the last 7 days (new services, IAM changes, etc.)?
- Are there any Cloud Build failures in algolia-gemini recently?
- List all Cloud Run services deployed in algolia-gemini.
