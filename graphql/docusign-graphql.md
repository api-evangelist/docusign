# DocuSign GraphQL

## Description

DocuSign does not currently offer a native GraphQL API. The platform exposes its functionality through a suite of REST APIs — including the eSignature REST API, Admin API, Click API, Maestro API, Monitor API, Rooms API, and others. All official integration is performed over REST endpoints documented at https://developers.docusign.com/docs/esign-rest-api/reference/.

## Conceptual Schema

The GraphQL schema in `docusign-schema.graphql` is a conceptual representation derived from the DocuSign eSignature REST API resource and type definitions. It covers envelopes, documents, recipients, tabs, templates, accounts, folders, bulk send, Connect webhooks, PowerForms, and supporting types. It is provided as a design reference and interoperability aid — not as a live endpoint.

## Endpoint

None. DocuSign does not publish a GraphQL endpoint.

## Reference Documentation

- REST API Reference: https://developers.docusign.com/docs/esign-rest-api/reference/
- Developer Portal: https://developers.docusign.com/
- GitHub Organization: https://github.com/docusign

## Note

This schema was derived from publicly available DocuSign REST API documentation and type definitions. It is a conceptual/community schema intended to support tooling, schema mapping, and interoperability workflows. It is not affiliated with or endorsed by DocuSign.
