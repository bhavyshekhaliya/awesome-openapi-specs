# Awesome OpenAPI Specs [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated directory of official API specifications for popular business and developer platforms. Browse by familiar use case, then use the linked OpenAPI JSON or YAML files with automation, integrations, documentation, testing, and MCP tools.

Created and maintained by [0mcp.io](https://0mcp.io).

## Contents

- [Sales and Marketing](#sales-and-marketing)
- [Productivity](#productivity)
- [Payments](#payments)
- [Finance](#finance)
- [Communication](#communication)
- [AI and Data](#ai-and-data)
- [Identity](#identity)
- [Developer Tools](#developer-tools)
- [Cloud and Infrastructure](#cloud-and-infrastructure)
- [Legend](#legend)
- [Maintainer](#maintainer)

## Sales and Marketing

Official OpenAPI definitions for sales engagement, outreach, and marketing platforms.

| Provider  | OpenAPI spec                                                              | Format | Version | Tags                          |
| --------- | ------------------------------------------------------------------------- | ------ | ------- | ----------------------------- |
| SendPilot | [API specification](https://docs.sendpilot.ai/api-reference/openapi.yaml) | YAML   | 3.0     | `official` `sales-engagement` |

## Productivity

Official OpenAPI definitions for work management, content, and business platforms.

| Provider | OpenAPI spec                                                                                         | Format     | Version | Tags                            |
| -------- | ---------------------------------------------------------------------------------------------------- | ---------- | ------- | ------------------------------- |
| Asana    | [API specification](https://github.com/Asana/openapi)                                                | JSON, YAML | 3.0     | `official` `project-management` |
| Box      | [API specification](https://github.com/box/box-openapi)                                              | JSON, YAML | 3.0     | `official` `content-management` |
| HubSpot  | [Public API specification collection](https://github.com/HubSpot/HubSpot-public-api-spec-collection) | JSON       | 3.0     | `official` `crm`                |

## Payments

Official OpenAPI definitions for payment processing platforms.

| Provider | OpenAPI spec                                                                        | Format     | Version | Tags                                |
| -------- | ----------------------------------------------------------------------------------- | ---------- | ------- | ----------------------------------- |
| Adyen    | [API specifications](https://github.com/Adyen/adyen-openapi)                        | JSON       | 3.1     | `official` `payments`               |
| Mollie   | [API specification](https://github.com/mollie/openapi)                              | YAML       | 3.0     | `official` `payments` `open-source` |
| PayPal   | [REST API specifications](https://github.com/paypal/paypal-rest-api-specifications) | JSON       | 3.0     | `official` `payments`               |
| Stripe   | [API specifications](https://github.com/stripe/openapi)                             | JSON, YAML | 3.0     | `official` `payments`               |
| SumUp    | [API specification](https://github.com/sumup/sumup-openapi)                         | YAML       | 3.0     | `official` `payments` `open-source` |

## Finance

Official OpenAPI definitions for banking, accounting, and financial data APIs.

| Provider | OpenAPI spec                                                             | Format | Version | Tags                    |
| -------- | ------------------------------------------------------------------------ | ------ | ------- | ----------------------- |
| Plaid    | [API specification](https://github.com/plaid/plaid-openapi)              | YAML   | 3.0     | `official` `fintech`    |
| Xero     | [Accounting API specifications](https://github.com/XeroAPI/Xero-OpenAPI) | YAML   | 3.0     | `official` `accounting` |

## Communication

Official OpenAPI definitions for messaging, collaboration, and communications APIs.

| Provider | OpenAPI spec                                                          | Format     | Version | Tags                                     |
| -------- | --------------------------------------------------------------------- | ---------- | ------- | ---------------------------------------- |
| Slack    | [Web API specifications](https://github.com/slackapi/slack-api-specs) | JSON, YAML | 2.0     | `official` `collaboration` `open-source` |
| Twilio   | [API specifications](https://github.com/twilio/twilio-oai)            | JSON       | 3.0     | `official` `communications`              |

## AI and Data

Official OpenAPI definitions for AI platforms, search engines, and databases.

| Provider    | OpenAPI spec                                                                           | Format     | Version | Tags                                       |
| ----------- | -------------------------------------------------------------------------------------- | ---------- | ------- | ------------------------------------------ |
| Meilisearch | [Specification repository](https://github.com/meilisearch/specifications)              | YAML       | 3.0     | `official` `open-source` `search`          |
| OpenAI      | [JSON and YAML specifications](https://github.com/openai/openai-openapi)               | JSON, YAML | 3.1     | `official` `ai`                            |
| Pinecone    | [Specification repository](https://github.com/pinecone-io/pinecone-api)                | YAML       | 3.0     | `official` `vector-database`               |
| Qdrant      | [REST API specification](https://github.com/qdrant/qdrant/tree/master/docs/redoc)      | YAML       | 3.0     | `official` `open-source` `vector-database` |
| Typesense   | [Specification repository](https://github.com/typesense/typesense-api-spec)            | YAML       | 3.0     | `official` `open-source` `search`          |
| Weaviate    | [REST API specification](https://github.com/weaviate/weaviate/tree/main/openapi-specs) | YAML       | 3.0     | `official` `open-source` `vector-database` |

## Identity

Official OpenAPI definitions for authentication, authorization, and identity management.

| Provider | OpenAPI spec                                                                         | Format     | Version | Tags                                |
| -------- | ------------------------------------------------------------------------------------ | ---------- | ------- | ----------------------------------- |
| Clerk    | [API specifications](https://github.com/clerk/openapi-specs)                         | JSON       | 3.0     | `official` `authentication`         |
| Okta     | [Management API specification](https://github.com/okta/okta-management-openapi-spec) | JSON, YAML | 3.0     | `official` `identity`               |
| Ory      | [API specifications](https://github.com/ory/sdk/tree/master/spec)                    | JSON       | 3.0     | `official` `identity` `open-source` |

## Developer Tools

Official OpenAPI definitions for observability, dashboards, and software development platforms.

| Provider      | OpenAPI spec                                                                                  | Format | Version | Tags                                     |
| ------------- | --------------------------------------------------------------------------------------------- | ------ | ------- | ---------------------------------------- |
| Docker Engine | [API specification](https://github.com/moby/moby/tree/master/docs/api)                        | YAML   | 2.0     | `official` `containers` `open-source`    |
| Grafana       | [HTTP API specification](https://github.com/grafana/grafana/blob/main/public/api-merged.json) | JSON   | 2.0     | `official` `observability` `open-source` |
| Sentry        | [API schema](https://github.com/getsentry/sentry-api-schema)                                  | JSON   | 3.0     | `official` `observability` `open-source` |

## Cloud and Infrastructure

Official OpenAPI definitions for cloud platforms, container systems, and infrastructure APIs.

| Provider     | OpenAPI spec                                                                                           | Format | Version  | Tags                                          |
| ------------ | ------------------------------------------------------------------------------------------------------ | ------ | -------- | --------------------------------------------- |
| Cloudflare   | [API schemas](https://github.com/cloudflare/api-schemas)                                               | YAML   | 3.0      | `official` `cloud` `open-source`              |
| DigitalOcean | [Public API specification](https://github.com/digitalocean/openapi)                                    | YAML   | 3.0      | `official` `cloud` `open-source`              |
| GitHub       | [REST API descriptions](https://github.com/github/rest-api-description)                                | JSON   | 3.0, 3.1 | `official` `developer-platform` `open-source` |
| Kubernetes   | [Generated OpenAPI definitions](https://github.com/kubernetes/kubernetes/tree/master/api/openapi-spec) | JSON   | 2.0      | `official` `containers` `open-source`         |

## Legend

**Format** identifies the machine-readable files published by the provider. **Version** identifies the OpenAPI or Swagger specification version, not the provider's API version.

The `official` tag means the provider publishes or maintains the linked source. The `open-source` tag means the implementation or specification accepts community development under an open-source license.

Links point to official repositories or directories when a provider publishes multiple API definitions or generated variants. Each provider retains ownership of its API definitions, trademarks, and licenses.

Last reviewed: July 29, 2026.

## Contributing

Contributions are welcome. Read [CONTRIBUTING.md](CONTRIBUTING.md) for the acceptance criteria and pull request format.

## Maintainer

0mcp.io creates and maintains Awesome OpenAPI Specs. This curated list is dedicated to the public domain under [CC0 1.0 Universal](LICENSE). Linked OpenAPI documents remain subject to their respective owners' licenses and terms.
