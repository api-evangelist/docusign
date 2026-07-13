---
title: "Clearer Docusign API error message and status code improvements"
url: "https://www.docusign.com/blog/clearer-docusign-api-error-message-and-status-code-improvements"
date: ""
author: "Cassandra Grey"
feed_url: "https://www.docusign.com/blog/developers"
---
Docusign updated 16 API error messages to be clearer and more actionable, adjusted HTTP status codes for rate-limiting scenarios to align with standard protocols, and introduced a new ENVELOPE_SEND_LIMIT_EXCEEDED error. Integrations that parse the errorCode field should be unaffected, but those relying on exact message strings or specific status codes may need updates before the production rollout completes in July 2026.
